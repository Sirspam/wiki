---
sidebar: auto
---

# Quest Modding

## はじめに

* このガイドはQuest1とQuest2のためのものです。
* 今までModによってBANされたことはありません。

::: danger 注意 しっかりと理解してからModを利用しましょう

* 初期設定（バニラ）には存在しない問題が発生する可能性があります。 99.9％のバグ、クラッシュや遅延はModによるものです。
* Modはゲームのアップデートによって動かなくなる可能性がありますが、普通のことです。このようなことが起きた場合は忍耐強く、敬意をもって待ちましょう。Mod作成者はボランティアです。
* Beat Gamesは、意図的にMODを破壊しようとはしていません。 コードベースで動作することを想定しているので、Modを壊すこともありますが、Modを排除しようとはしません。

Modに関連する問題でゲーム開発者を非難しないでください。 ただのクレーマーになってはいけません。 :::

:::warning Youtubeのビデオチュートリアルを見たのですが、うまくいかず困っています。 どうすればいいですか？ BSMGでは、改造のためにビデオチュートリアルを使用しないことを**強く**お勧めします。 多くの場合、それらの情報は古いものであったり、不完全であったり、誤った情報であったりすることがあります。

代わりに、ここで書かれたガイドに従うか、 [BSMG Discord](https://discord.gg/beatsabermods) のヘルプを探してください。（いくつかの日本語サイトも古い情報を含んでいるので注意してください） :::

## インストール
現在、カスタム曲やMODをインストールする唯一の推奨方法は、[パソコンでSideQuestから](#installing-bmbf-with-sidequest)BMBFをロードすることです。

PCを使えない場合は、 [Android端末でModを導入する](/support/modding-with-android.md) を参照してください。 iPhoneやiPadなどのChromebookやiOSデバイスはサポートされていません。

:::warning 警告 BMBFをインストールすると公式のマルチプレイモードや公式のリーダーボードへのスコアの送信、リプレイの記録ができなくなります。 もしModが導入された状態でマルチプレイを行いたい場合は`Beat Together`と`MultiQuestensions`が必要になります。これはPCとQuestのクロスプレイを可能にします。また、両方とものカスタムソングで遊ぶことができます。 BMBFを設定する際には、これらのMODを自動的にインストールする必要があります。

ランク付けされた曲からパフォーマンスポイント(PP)を得るためには、 [ScoreSaber](https://new.scoresaber.com/quest) modが必要です。 [このリンク](https://new.scoresaber.com/quest) では、 ScoreSaberページに移動して設定する方法が書いてあります。 Scoresaberは公式のリーダーボードを置き換えるものではなく、カスタム曲のリーダーボードだけが追加されます。

**注意** [ScoreSaber Discord](https://discord.gg/WpuDMwU)のサーバーでModが現在のゲームバージョンで使えるかチェックしてください。 :::

### SideQuestでBMBFをインストールする
SideQuestをまだ設定していない場合は、 [SideQuest Easy Installer](https://sidequestvr.com/setup-howto) をダウンロードしてセットアップしてください。

**注意:** iOSをお使いの場合は、 `ステップ4:開発者モードを有効にして再起動` の代わりに次の手順に従ってください。

![iOSHowTo](~@images/beginners-guide/EnableDevModeIOS.png)

BMBFを取得するには3つの方法があります。

* [PC/Mac上のSideQuestストア](#download-from-the-sidequest-store)
* PCをお持ちでない場合は、 [AndroidのSideQuestストア](/support/modding-with-android.md) を使用できます。
  * ChromebookやiPhoneやiPadなどのiOSデバイスはサポートされていません。 :::tip 以前にModが導入されたBeat Saberやスコアがあれば、 [あらかじめデータをバックアップしてください!](#backup-save-data-using-sidequest) :::

#### SideQuest Storeからダウンロード

1. SideQuestを設定した後、 `BMBF` を検索するか、ヘッドセットのゲーム & アプリのページで検索します。
2. ページの `ダウンロード (Sideload)` ボタンをクリックし、プロンプトが表示されたら `インストール` ボタンをクリックします。
3. BMBFがヘッドセットにインストールされるのを待ち、必要に応じて不明なソースからアプリをインストールできるようにします。

#### BMBFのセットアップ

BMBFのインストールが完了したら、BMBFがサポートしている最新のBeatSaberがインストールされていて、Modが入っていない事を確認してください。 [BSMG Discord](https://discord.gg/beatsabermods) の `#modding-announcements` チャンネルや、[QuestBoard](https://www.questmodding.com/) で、対応バージョンやModを確認してください。

:::warning Modを入れる前にBeatSaberを一度起動し、任意の曲を一回プレイしてください。すぐに失敗しても大丈夫です。

現在、マルチユーザー機能を利用している場合、Modは動作しません。 Modを導入する前に一時的にサブアカウントをすべて取り除く必要があります。 希望のModをインストールし終えたらあとで元に戻すことができます。 :::

Beat Saberを一度実行した後、以下の写真のように、unknown sourcesからBMBFを開きます。 ![UnknownSources](~@images/beginners-guide/quest_home-menu.jpg)

開いたら、BMBFの各手順に沿ってModを導入してください。 完了後[QuestBoard](https://www.questmodding.com/)と[BeastSaber](https://www.bsaber.com)がBMBFにアプリとしてロードされます。 そこで利用可能な任意のカスタム曲をダウンロードすることができます。 また、BeatSaverボタンをクリックして曲をダウンロードすることもできます。

ゲームの改造に成功すると、 `アプリを復元する` ポップアップが表示されます。 `閉じる` をクリックして下さい

Modを入れた後にBeat Saberを起動しようとすると、アプリの復元を確認するポップアップが再び表示される可能性があります。 そこで アプリを開くを選択します (この時点で閉じるを押すと何も行われません)。 この警告は、海賊版のゲームを対象としているので、Modを導入しているだけの場合無視をしてもほとんど影響はありません。

![RestoreApp](~@images/beginners-guide/restoreapp.png)

引き続き[コアMod](#core-mods)のインストールステップに進んでください。

## 保存データの管理

:::warning セーブデータを管理するには、SideQuest Advanced Installerが必要です。 続行する前に、 [SideQuest サイト](https://sidequestvr.com/setup-howto) から取得してインストールしてください。 :::

### SideQuest を使用してセーブデータをバックアップ

SideQuestを開き、QuestをPCに接続します。

SideQuest ファイルエクスプローラを使用して、 `sdcard/Android/data/com.beatgames.beatsaber/files` に移動します。

![SideQuest Files](~@images/beginners-guide/sqfiles.png)

`AvatarData.dat`と`PlayerData.dat` と `settings.cfg` を PC 上のフォルダに保存します。 これらにはあなたのスコアやその他の設定が含まれているので，失くさないようにしてください。

### SideQuest を使用してセーブデータを復元

データを復元するにはSideQuestを開き、PCに接続します。  
SideQuestのファイルから[SideQuest を使用してセーブデータをバックアップ](#backup-save-data-using-sidequest)で保存した3つのファイル`AvatarData.dat`、`PlayerData.dat`と`settings.cfg`を`sdcard/Android/data/com.beatgames.beatsaber/files`に入れます

## Modをインストール

### コアMod
追加のMODをインストールする前に、BMBFウェブインターフェースの右上に「`Sync to Beat Saber`」という赤いボタンが表示されています。 これをクリックして同期を完了させます。 BMBFの `mods` タブに移動します。 12つのコアModがあることを確認してください:

* BeatTogether
* MultiplayerCore
* Codegen
* Custom Types
* PlayerData Keeper
* Pink Core
* Playlist Core
* Playlist Manager
* Quest UI
* Song Downloader
* Song Loader
* Mod List

:::danger 注意 これらのコアModが無いと他のModは動作しません！

もしリストにModがない場合はBMBFの`Tools`タブの`Reload Mods`と`Check Core Mod Updates`ボタンを押してください。 それでもModが表示されない、もしくは表示されるがゲーム内で動作しない場合はトラブルシューティングの[コアModが動かない場合](#core-mods-don-t-work)を参照してください。 :::

### Quest 内での操作
:::warning すべてのModがQuestBoardで使えるわけではありません!  
もしお探しのModがここで見当たらない場合は [PCを使った方法](#using-your-pc) を代わりにお試しください。 :::

QuestでBMBFを開き、`Browser` タブに移動します。 QuestBoard は自動的に開きます。  
そうでない場合は、`Choose Website` をクリックし、`QuestBoard` ボタンをクリックします。

![globequestboard](~@images/beginners-guide/globequestboard.png)

以下の [QuestBoard](https://www.questmodding.com/) ウェブサイトにアクセスしてください 次に、 `Get Mods` タブを選択します。

![questboardhome](~@images/beginners-guide/questboardhome.png)

ポインタをドラッグして下にスクロールします。 そのリストから任意のModを選択し、その隣のダウンロードボタンを押してダウンロードすることができます。 一部のダウンロードは、ウェブサイトまたはGitHubページにリダイレクトされる場合があります。 その場合は、画面上の指示に従うか、リリースリストで最新の `.qmod` をそれぞれ選択します。

![questboardmods](~@images/beginners-guide/questboardmods.png)

### PCを使った方法
[BSMG Discord](https://discord.com/invite/beatsabermods)の`#quest-mods`チャンネルで他のModを探してインストールすることができます。

:::warning
QuestとPCが同じネットワークに接続されていること、httpsではなくhttpであることを確認してください。
:::

QuestでBMBFを開き、 `Tools` タブに移動します そこにウェブアドレスとバージョン番号が表示されます

![ip](~@images/beginners-guide/ip.png)

お使いの PC でブラウザを開き、検索バーにアドレスを入力します。

以下の画面にアクセスできるはずです。

これがうまくいかない場合は、 [こちら](#bmbf-web-interface-not-loading) をクリックしてトラブルシューティングの手順にしたがってください。

![bmbfweb](~@images/beginners-guide/bmbfweb.png)

Quest互換のModをアップロードボックスにドラッグして、同期してください。 古いバージョン用のModとして作られていた場合、自動的に有効にはなりません。 古いModを有効にするには、 `Mods` タブに移動し、そこから有効にします。

## 曲のインストール
::: tip 譜面の探し方
「すべての曲から」「レート順」「ダウンロード数」「プレイ数」によってソートできます。ここにあるほとんどの曲は「よいマップの作り方ガイド」ができる前に作られたものです。 2019年後半から今の間にリリースされた曲をダウンロードして、最高の
カスタムマップを体験してみてください。
:::

### ゲーム内でダウンロードする方法
SongDownloader (コア mod) を使ってゲーム内で曲をダウンロードできるようになりました。 ゲーム内で曲をダウンロードするにはいくつかのステップがあります。

1. Beat Saberを開く
2. メインメニューの左側にある「Mods」パネルを見る
3. SongDownloader タブを開く
4. 曲を検索してダウンロードします。

ゲーム内で曲をダウンロードするときは、ゲームを再起動する必要はありません。 SongLoader を使用して自動的に曲をロードします。

![songdownloader](~@images/beginners-guide/songdownloader.png)

### BMBFからダウンロードする方法
ブラウザを使用してQuest内にカスタム曲を取得するには、2つの方法があります。

* キュレーションされたマップとプレイリストをお探しなら、 [BeastSaber](https://bsaber.com/) をご覧ください。
* BeastSaberのUIが気に入らない場合は、 [BeatSaver](https://beatsaver.com/)を試すこともできます。

どちらにもOneClick™ ボタンがあり、Questにその曲を簡単にインストールできます。 ブラウザウィンドウの右上にある地球儀アイコンを使用して、これらのウェブサイトを切り替えることができます。

`Syncsaber`を使うことで様々な種類の曲を簡単にダウンロードできます。QuestのBMBFから`Syncsaber`というタブをクリックしてください。 ここではボタンをクリックして曲をダウンロードすることができます。様々な設定から選ぶことができます。 例えば[Beatsaver's](https://beatsaver.com/)でのトップ20をダウンロードしたい場合は"hot"を選んでください。もしくは50個の最も難しい曲を選ぶこともできます。

### PCを使った方法
Quest内でマップをインストールできない場合は、modのインストールと同様にコンピュータを使用してマップをインストールできます。

1. お使いのコンピューターで [BeastSaber](https://bsaber.com/) または [BeatSaver](https://beatsaver.com/) にアクセスしてください。
2. zipファイルをダウンロード
3. [PC を使用して Mod をインストールする](#using-your-pc) の手順に従って、ファイルのアップロード画面を開きます。
4. マップのzipファイルをドラッグアンドドロップするとインストールされます！

これがうまくいかない場合は、 [こちら](#bmbf-web-interface-not-loading) をクリックしてトラブルシューティングの手順に従ってください 。

:::tip プレイリストも同様にダウンロードできます。 様々なプレイリストを[BeastSaber](https://bsaber.com/category/playlists/)やDiscordのチャンネルで見つけることができます。 [BMBF マネージャー](https://github.com/ComputerElite/BM#bmbf-manager) を使用して独自のものを作ることもできます。

作成したマップをテストしたい場合は、 [Questでテストプレイ](/mapping/#testing-on-a-quest) の譜面作成セクション内の「テスト用」セクションを参照してください。 :::

## モデルのインストール
[Qosmetics Community](https://discord.gg/qosmetics) に参加して、メニューのタイトル、セイバー、ノーツ、壁の見た目を変えましょう！

## ダウングレード
[BSMG](https://www.discord.gg/beatsabermods)の`#modding-announcements`チャンネルで最新バージョンがModに対応しているかを確認してください。 Modが最新バージョン向けに対応されていない場合は、Modが利用できるようにダウングレードする必要があります。

簡単な方法は[Quest用Mod](https://www.questmodding.com/)ページに行き、ダウングレードの説明欄から適切なバージョンに設定することです。

これらの手順でModを導入することができます。

::: tip うまく動作しない場合は [BSLG Discord](https://discord.gg/MrwMx5e) で質問してください。 :::

## 関連リンク

* [Qosmetics Community](https://discord.gg/qosmetics) - Quest用にセイバー、ノーツ、壁が保存されているサーバー。
* [Qosmetics Creation Guides](https://github.com/RedBrumbler/Qosmetics/wiki) - Quest用に独自のカスタムセイバー、ノーツ、壁を作成するためのガイド。
* [Quest用Mod開発ガイド](./modding/README.md#quest-mod-development) - Quest用のMODを作成するためのガイド。
* [Questboard website](https://questmodding.com) - Beat Saber関連のニュースや最新の modsリリースの情報など！
* [Questboard discord server](https://discord.gg/P7sUKVnP) - Quest版BeatSaberに関係する情報があります。またModがリリースされたときに通知を受けることもできます。
* [オーディオ同期ズレの修正](https://bsaber.com/quest-out-of-sync/)
* [ScoreSaber](https://new.scoresaber.com/quest) - カスタムマップのゲーム内ランキング
* [ScoreSaber](https://scoresaber.com) - カスタムマップのリーダーボードを閲覧できるウェブサイト。

## トラブルシューティング
:::warning YouTubeのビデオチュートリアルを見たのですが、うまくいかず困っています。 どうすればいいですか？ BSMGでは、改造のためにビデオチュートリアルを使用しないことを**強く**お勧めします。 多くの場合、それらの情報は古いものであったり、不完全であったり、誤った情報であったりすることがあります。

代わりに、ここで書かれたガイドに従うか、 [BSMG Discord](https://discord.gg/beatsabermods) のヘルプを参照してください。 :::

### beatmods.comまたはmodelsaber.comから手に入れたModが動きません。
[BeatMods](https://beatmods.com/) や [ModelSaber](https://modelsaber.com/) のMODが動作しないのはそれらがPC用であるからです。

Questに互換性のあるModは [Questboard](https://www.questmodding.com/) かBeat Saber ModdingのDiscordチャンネル`#quest-mods`から、セイバー、ブロック、壁は[Qosmetics Community](https://discord.gg/qosmetics)から入手してください。 ModまたはモデルのZIPを取得したら、 [BMBF Webインターフェイス](#using-your-pc) を使用してインストールします。

### BMBFのサイドローディングに失敗しました。
BMBFをサイドローディングするとエラーが表示されます `INSTALL_FAILED_UPDATE_INCOMPATIBLE: Package com.weloveoculus.BMBF signatures do not match the previously installed version; ignoring!`

QuestでBMBFバージョンをアンインストールする必要があります。 SideQuestの `My Apps` メニューから行うことができます。

### コアMod が動かない場合

コアMod に問題がある場合は、古いModを使用していないかを確認してください。 古いバージョンで作成されたModはすべて古いModとして認識されます。 一度それらを削除し、下の手順に従ってください。

1. `Tools`に移動します。
2. `Delete Mods` をクリックします。
3. `Sync to Beat Saberをクリック`

すでにModがインストールされている場合は一度アンインストールしてから再インストールしてください。

---

### BMBF Web インターフェイスが読み込まれていません
BMBF Webインターフェイスが読み込まれない場合は、同じWi-Fiネットワーク上にあるコンピュータのブラウザにQuestのIPアドレスを入力していることを確認してください。 それでも読み込まれない場合は、次の操作を行っていることを確認してください:

* BMBF がヘッドセットで開かれていて、ヘッドセットがスリープモードではない
* リンクの先頭に http:// があり、 https:// ではない
* IPアドレスが常に同じである
* リンクの最後に :50000 がある
* PCとQuestが同じネットワークにある (イーサネットは*接続を混乱させる可能性がある*ことに注意してください。他のすべての修正を試みた場合は、ワイヤレスまたは別のデバイスを試してみてください。)
* VPNを使用していない
* IPアドレスが `127.0.0.1` ではない場合、ヘッドセットやルーターを再起動する

---

### セイバーとModが有効になりません！
これは、BMBFアプリが古いことが原因である可能性が高いため、最新の BMBFを入手してください。 適切なBeat SaberのBMBFバージョンがない場合は、BMBFが更新されるまでしばらくお待ちください。

* マップのプレイボタンが押せない場合は、右上の？マークを押して必要なModを確認し、インストールしてください。
* あなたのBMBFが最新バージョンで、ゲーム内でMODが有効になっていない場合 BMBF ToolsタブのUninstall BSボタンでBeat Saberをアンインストールし、再インストールしてもう一度Modを入れなおしてください。

---

### Beat Saber がクラッシュした
Modをひとつひとつ無効にしてチェックしてください。それでも問題が解決しない場合はDiscordのサポートチャンネルにお問い合わせください。

### BMBFを開くと白い画面が表示されます
unknown sources(提供元不明)からBMBFを開くときに白い画面が表示されることがありますが、数秒間待ってください。 動作しない場合は、Questを再起動してもう一度BMBFを開いてください。
