- - -
sidebar: auto
- - -

# Linux Mod 教程

## 阅前须知
大多数 Beat Saber Mod 安装器并不是为了 Linux 而编译的，因此我们需要做一些小改动才能让它在 Linux 上运行。 这非常类似于 Windows 安装，但还需要一些额外工作。

::: 警告
大多数 Mod 开发者并不支持在 Linux 中安装 Mod，所以你可能会遇到一些 bug。
:::

### 使用 Beataroni
在安装 Mod 之前，** 至少运行一次游戏 **。 重装游戏后也是这样。 :::

1. 从 [GitHub](https://github.com/geefr/beatsaber-linux-goodies/releases) 下载 Beataroni，然后解压到您系统上的某个目录。

```sh
tar -xzf Beataroni-linux64-1.0.tar.gz
```

2. 运行 `Beataroni-Linux.sh`。
3. 输入您的 Beat Saber 安装位置，选择正确的版本，然后按 ** Continue **。

![Beataroni Beat Saber Installation and Version Select Screen](~@images/modding/beataroni-start.png)

4. 选择您想要安装的模组，然后按 **Continue**。 您将需要 `BSIPA`（在列表顶部），因为它是所有其他 Mod 的依赖项。

![Beataroni Mod List Screen](~@images/modding/beataroni-mod-list.png)

5. 等待安装你的 Mod。

![Beataroni Log Screen](~@images/modding/beataroni-end.png)

6. 启动节奏光剑。 您的 Mod 应该都安装好了。

### 使用 Wine 和 Winetricks
在安装 Mod 之前，** 至少运行一次游戏 **。 重装游戏后也是这样。 :::

请确保您在启动前安装了 [Wine](https://wiki.winehq.org/Download) 和 [Winetricks](https://github.com/Winetricks/winetricks/blob/master/README.md)。

1. 创建一个新的 32 位 Wine prefix。

```bash
export WINEARCH="win32"
export WINEPREFIX=~/.winemods
wineboot -u
```

2. 使用 Winetricks 安装 dotnet472 和 d3dcompiler_47 软件包。 如果它请求重启，请选择“Restart later”。

```bash
winetricks dotnet472 d3dcompiler_47
```

![dotnet472](https://i.imgur.com/r62nmZW.png)

::: 警告
你将看到多次安装提示，这是正常的！
:::

3. 下载 [Mod 安装程序](/beginners-guide.md#installers) 并将其放入您的 [ 游戏文件夹 ](/faq/install-folder.md)。 <br/>![Install Folder](https://i.imgur.com/ap2ofvE.png)
4. 移动 Beat Saber 文件夹到桌面，并打开一个终端
5. 在终端中打开到您的 Beat Saber 文件夹，然后在 Wine 中运行安装程序。

```sh
cd Desktop
cd "Beat Saber"
wine BeatSaberModManager.exe
```

![BeatSaberModManager](https://i.imgur.com/sXUhA8x.png)

4. 将安装程序引导到您的 Beat Saber 目录 ![BeatSaberModManager](https://i.imgur.com/DzEaDaI.png)
5. 安装您的 Mod。 您现在应该有一个 Plugins 文件夹。
6. 关闭安装程序，并把 Beat Saber 文件夹移动回去。 ![Beat Saber folder](https://i.imgur.com/xWeN0TT.png)
7. 打开 Beat Saber 并检查 Mod 是否已安装。 如果 Mod 未正确安装，你可能将需要[进行 DLL 覆盖](#dll-override)

### 使用虚拟机
在安装 Mod 之前，** 至少运行一次游戏 **。 重装游戏后也是这样。 :::

请确保您在启动前安装 [VirtualBox](https://www.virtualbox.org/wiki/Linux_Downloads)。

1. [ 下载 Windows 10 ISO](https://www.microsoft.com/en-us/software-download/windows10ISO)。
2. 创建一个新的 Windows 10 虚拟机并启动。 ![VirtualBox](https://i.imgur.com/HJMwMSr.png)
3. 当问到时，请选择 Windows 10 ISO。 然后启动它。 ![VirtualBox](https://i.imgur.com/af0ikmV.png)
4. 安装 Windows 后，请在 VM 中下载 [Mod Assistant](/beginners-guide.md#installers)。 ![Mod Assistant Install](https://i.imgur.com/juZzw1j.png)
5. 前往 ' 设备 > 共享文件夹 > 共享文件夹...' 创建共享文件夹。 为 `/.local/share/steamapps/common/` 创建一个新共享文件夹，并打开自动挂载。 ![Shared Folder](https://i.imgur.com/FoV8BE3.png) ![Shared Folder](https://i.imgur.com/rcpnROc.png)
6. 运行您下载的 Mod 安装程序，手动选择您的 Beat Saber 文件夹，然后安装您的 Mod。
7. 退出虚拟机，并开启节奏光剑。 您的 Mod 应该都安装好了。 如果没有，那你需要[进行 DLL 覆盖](./linux.md#dll-override)

### 进行 DLL 覆盖
Wine 不像 Windows 那样使用 DLL，所以您必须修改一些项目才能让 IPA 注入正常工作。

::: danger DANGER 注册表文件可能是危险的，请确保您不触碰任何指南没有告诉您的内容。  
如果您收到注册表文件，要么验证您的游戏文件，要么在备份文件后重新安装 Beat Saber。 :::

1. Navigate to `/.local/share/Steam/steamapps/compatdata/620980/pfx/` and open `user.reg`
2. Inside the file, navigate to `[Software\\Wine\\DllOverrides]`. Try <kbd>Ctrl + F</kbd> and type DllOverrides to get there more quickly
3. Paste `"winhttp"="native,builtin"` on the bottom below the others, and save the file.

![DLL Overrides](https://i.imgur.com/dgemtef.png "DLL Overrides")

## Have questions?
Visit the [FAQ](/faq/) or drop by the `#support` tab in the [BSMG Discord](https://discord.gg/beatsabermods)!
