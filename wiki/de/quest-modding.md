---
sidebar: auto
---

# Quest Modding

## Vorwort

* Diese Anleitung ist sowohl für die Quest 1 als auch Quest 2.
* Niemand wurde bisher wegen Moddings gebannt.

<<<<<<< HEAD
::: danger DISCLAIMER Solltest Du Mods verwenden, sollte dir bewusst sein:
=======
::: danger WARNUNG
Solltest Du Mods verwenden, sollte dir bewusst sein:
>>>>>>> master

* Dass du möglicherweise Probleme bekommst, die im normalen Spiel nicht existieren. 99,9% aller Fehler, Abstürzen und Verzögerungen entstehen aufgrund von Mods.
* Mods werden durch Updates oft unbrauchbar und das ist normal - Bitte sei geduldig und respektvoll wenn dies passiert. Modder sind Freiwillige mit einem richtigen Leben.
* Beat Games versucht nicht mit Absicht, Mods kaputt zu machen. Sie versuchen an der Code-Grundlage zu arbeiten, welches Mods manchmal unbrauchbar macht. Dies geschieht aber nicht mit Absicht.

<<<<<<< HEAD
Bitte greife die Entwickler im Bezug mit Problemen bei Mods nicht an. Modder und Entwickler sind zwei verschiedene Gruppen. Sei kein Trottel. :::

:::warning Ich habe ein Video Tutorial angeschaut, aber es hägt/hat nicht funktioniert. Was bedeutet das? Wir, die BSMG raten **strikt** von Video Tutorials für's Modding ab. Meistens ist es so, dass diese veraltet, unvollständig, irrtümlich oder einfach falsch sind.

Stattdessen solltest du den schriftlichen Anleitungen hier im Wiki folgen oder Hilfe im [BSMG Discord](https://discord.gg/beatsabermods) suchen. :::

## Installation
Momentan ist der einzige empfohlene Weg custom Songs un Mods zu installieren BMBF, welches du mit [SideQuest installierst über einen PC](#installing-bmbf-with-sidequest).

Wenn du keinen Zugang zu einem PC hast, kannst du ein [Android Handy](/support/modding-with-android.md) verwenden. Chromebooks und iOS-Geräte wie iPhones oder iPads werden nicht unterstützt.

:::warning Wenn du BMBF installierst und dein Spiel modifizierst, wird der offizielle Mehrspielermodus sowie die Anzeige und das Hochladen von Spielständen in den Bestenlisten des Basisspiels deaktiviert. If you would like to play modded multiplayer, you need the mods, `Beat Together` and `MultiQuestensions`, which allows for cross-play between PC and Quest and allows for custom songs to be used. These mods can be found in the [Beat Saber Modding Group](discord.gg/beatsabermods) in `#quest-mods` or on the [Questboard](https://questmodding.com) site.

To get leaderboards on custom songs and to be able to get Performance Points (PP) from ranked songs you need the [ScoreSaber](https://new.scoresaber.com/quest) mod. [This link](https://new.scoresaber.com/quest) will take you to the ScoreSaber page to set it up. ScoreSaber does not replace the base game leaderboards, it only adds leaderboards for custom songs.

**Note:** Check the updates channel in the [ScoreSaber Discord](https://discord.gg/WpuDMwU) to see if the mod is available for the current game version. :::

### BMBF mit SideQuest installieren
If you haven't already, download and setup [SideQuest](https://sidequestvr.com/#/setup-howto).

**Note:** If you are on iOS, for `Step 4: Enable Developer Mode and Reboot` follow these steps instead

![iOSHowTo](~@images/beginners-guide/EnableDevModeIOS.png)

There are three methods available to obtain BMBF:

* [The SideQuest Store on PC](#download-from-the-sidequest-store)
* [The BMBF website](#download-the-from-the-bmbf-website)
* If you do not have a PC, you can use [the SideQuest Store on Android](/support/modding-with-android.md) as a last resort
  * Chromebooks and iOS devices such as iPhones or iPads are not supported. :::tip If you've previously modded Beat Saber or have scores you want to backup, [backup your Save Data first!](#backup-save-data-using-sidequest) :::

#### Download from the SideQuest Store

1. Connect your Quest to your PC, then go to [BMBF On SideQuest](https://sidequestvr.com/app/747).
2. Click the `Install To Headset` button. (Accept a prompt to open SideQuest if it appears.)
3. Wait for BMBF to finish installing onto your headset.

Once installed, skip to the [BMBF Setup](#bmbf-setup) section of the guide.

#### Download from the BMBF website
First download the [BMBF APK](https://bmbf.dev/stable) on your PC.

Open SideQuest and connect your Quest to your PC.

If you have a modded game you also need to uninstall it by going into the Apps tab on SideQuest (the waffle icon at the the top of the application), selecting the cog wheel next to Beat Saber, and press the `UNINSTALL APP` button. You can then download Beat Saber from the Quest Store and the game will be on its latest version, completely unmodded.

Select the `Install APK from folder` button shown below and find the latest BMBF apk you downloaded and click on it, or simply drag the BMBF apk into SideQuest. Either method will install BMBF to your Quest.

![InstallAPK](~@images/beginners-guide/apkfromfolder.png)

You can now continue to the [BMBF Setup](#bmbf-setup) section of the guide.

#### BMBF Setup

Once BMBF has been successfully installed, make sure you have the latest supported version of Beat Saber installed and unmodded. Check the BSMG `#modding-announcements` channel or [QuestBoard](https://www.questmodding.com/) to see which game version this is and for other modding news.

:::warning Before modding, run Beat Saber once, play a level and immediately fail!

Modding currently does not work if the experimental multi-user feature is in use. You will need to temporarily remove all secondary accounts before modding the game. You can add them back later once you have installed your desired mods. :::

After running Beat Saber once, open BMBF from unknown sources as the picture below shows. ![UnknownSources](~@images/beginners-guide/quest_home-menu.jpg)

Once opened, follow each step in BMBF exactly as you're told to mod your game. Once completed, you should see [QuestBoard](https://www.questmodding.com/) with [BeastSaber](https://www.bsaber.com) loaded inside of the BMBF app. This is where you can download any custom songs available. You can also click the BeatSaver button to download songs too.

After successfully modding your game, the `Restore App` popup will appear. You can just click `Close`.

When trying to launch Beat Saber after modding it, you will likely get the Restore App popup again. This time, select Open App instead (hitting Close at this point will do nothing). This warning is more directed to pirated versions of the game so if you're just modding there will likely be no consequences for ignoring it.

![RestoreApp](~@images/beginners-guide/restoreapp.png)

Continue to the [Core Mods](#core-mods) step of the installation process.

## Speicherdaten verwalten

### Backup Save Data using SideQuest

Open SideQuest and connect your Quest to your PC.

Navigate to `sdcard/Android/data/com.beatgames.beatsaber/files` using the SideQuest file explorer.

![SideQuest Files](~@images/beginners-guide/sqfiles.png)

Save the files: `AvatarData.dat`, `PlayerData.dat` and `settings.cfg` into a folder on your PC. Do not lose these, as they contain your scores and other settings!

### Restoring Save Data using SideQuest

To restore your data, open SideQuest and connect your Quest to your PC.  
Using the SideQuest file explorer, take the 3 files you saved from the [Backup Save Data using SideQuest](#backup-save-data-using-sidequest) steps `AvatarData.dat`, `PlayerData.dat` and `settings.cfg` and put them in the `sdcard/Android/data/com.beatgames.beatsaber/files` folder.

## Mods installieren

### Core Mods
Before installing any additional mods look in the top right of the BMBF web interface, you should see a red button that says, `Sync to Beat Saber`. Click this and let it finish syncing. Then go to your `mods` tab in BMBF. Make sure that you have the 7 core mods:

* Custom Types
* Codegen
* SongLoader
* Playlist Manager
* QuestUI
* SongDownloader
* PinkCore

:::danger Other mods will not work without these Core Mods!

If one of these mods are not listed, try the `Reload Mods` and `Check Core Mod Updates` button in the `Tools` Tab inside of BMBF. If it still does not appear, or mods appear but not working in-game, see [Core Mods don't work](#core-mods-don-t-work) for troubleshooting steps. :::

### Inside your Quest
:::warning Not all mods are available on QuestBoard!  
If a mod is not seen in here, you should follow the [Using Your PC](#using-your-pc) method instead. :::

Open BMBF in your Quest and go to the `Browser` tab. The QuestBoard website should automatically open.  
If not, click `Choose Website` at the top right, then click the `QuestBoard` button.

![globequestboard](~@images/beginners-guide/globequestboard.png)

You should be greeted with the [QuestBoard](https://www.questmodding.com/) website below. Next, select the `Get Mods` tab.

![questboardhome](~@images/beginners-guide/questboardhome.png)

Scroll down by clicking and dragging the pointer. You can now select any mod from the list, seen below, and download it by hitting the download button next to it. Some downloads may redirect you to a website or GitHub page. If so, follow the instructions onscreen, or select the latest `.qmod` in the Releases list, respectively.

![questboardmods](~@images/beginners-guide/questboardmods.png)

### Using your PC
You can find and download other Quest mods from the [BSMG Discord](https://discord.com/invite/beatsabermods) in the `#quest-mods` channel.

:::warning
Make sure your Quest and PC are on the same network and that you are using http and not https!
:::

Open BMBF in your Quest and go to the `Tools` tab, there you should see a web address and a version number similar to what's shown below.

![ip](~@images/beginners-guide/ip.png)

On your PC, open your browser and type the address into the search bar.

You should be greeted with this screen below.

If this doesn't work [click here](#bmbf-web-interface-not-loading) for some troubleshooting steps.

![bmbfweb](~@images/beginners-guide/bmbfweb.png)

Now just drag any Quest compatible mods into the upload box and sync. If the mod was originally made for an older version, then it won't automatically enable. To enable an old mod, go to the `Mods` tab and enable it from there.

## Songs installieren
::: tip
Most maps in the "Top All", "Rating", "Downloads" or "Plays" sort filters were created before
good mapping practices were established. Try downloading songs released between late 2019 and now to get the best
custom levels experience.
:::

### In-Game
You can now download songs in-game using SongDownloader (core mod) There are a few steps to downloading songs in-game:

1. Open Beat Saber
2. On the main menu, look at the Mods screen, on the left.
3. Open the SongDownloader tab
4. Search for a song and download it.

When downloading songs in-game you do not have to restart the game. It automatically loads the song using the SongLoader.

![songdownloader](~@images/beginners-guide/songdownloader.png)

### Inside BMBF
There are 2 sources to getting custom maps inside your Quest using the browser window.

* If you are looking for curated maps and playlists visit [BeastSaber](https://bsaber.com/)
* If you don't like the UI of BeastSaber you could also try [BeatSaver](https://beatsaver.com/)

Both have a OneClick™ button that easily installs that song onto your Quest. You can switch between these websites using the globe icon in the top right of the browser window.

An easy way to download different kinds of songs is to use `SyncSaber`, which you can access by going into BMBF on your Quest and clicking the tab called `SyncSaber`. Here, you can download songs with a click of a button by choosing from different "settings". For example, you can download the top 20 songs in [BeatSaver's](https://beatsaver.com/) "hot" section or the 50 hardest ranked songs.

Another method is using the `Bookmark` feature on [BeastSaber](https://bsaber.com/). After creating an account, you can click a little bookmark icon on a song and if you later delete all your songs from the Quest you can redownload the ones that are bookmarked with OneClick™.

### Using your PC
If you are unable to install songs inside your Quest, you can install maps using your computer similar to installing mods.

1. Visit [BeastSaber](https://bsaber.com/) or [BeatSaver](https://beatsaver.com/) on your computer
2. Download the zip
3. Follow the [Installing mods using your PC](#using-your-pc) steps up to the upload files screen.
4. Drag and drop the map zip in, and it should be installed!

If the web interface doesn't load [click here](#bmbf-web-interface-not-loading) for some troubleshooting steps.

:::tip You can also download playlists in the same way. You can find various playlists on [BeastSaber](https://bsaber.com/category/playlists/) or various community discords. You can also make your own using [BMBF Manager](https://github.com/ComputerElite/BM#bmbf-manager) or [Playlist Editor Pro](https://beatsaberquest.com/playlisteditor-pro/).

If you want to test a map you have created see the [Testing on a Quest](/mapping/#testing-on-a-quest) Section in the Mapping Wiki section for steps on packing it up for testing! :::

## Modelle installieren
Join the [Qosmetics Community](https://discord.gg/qosmetics) to change how your sabers, bloqs or walls look in-game!

## Downgrading
Check `#modding-announcements` in [BSMG](https://www.discord.gg/beatsabermods) to see if modding on the latest version of the game is possible. If mods are not updated for the latest version, you will need to downgrade to be able to mod.

The easiest method to get to the right version, is to go to the [QuestModding](https://www.questmodding.com/) page, click on How To Downgrade tab, and follow the steps.

With these steps done, you can now start modding your game!

::: tip Something not working? Go to the [BSLG Discord](https://discord.gg/MrwMx5e) for help. :::

## Useful Links

* [Qosmetics Community](https://discord.gg/qosmetics) - Server dedicated to making and using sabers, bloqs, walls, and more for Quest.
* [Qosmetics Creation Guides](https://github.com/RedBrumbler/Qosmetics/wiki) - Guides to create your own custom sabers, bloqs, and walls for Quest.
* [Quest Mod Development Guide](./modding/README.md#quest-mod-development) - Guides to create your own mods for Quest.
* [QuestBoard website](https://questmodding.com) - A place to get Beat Saber related news and info along with the latest mods releases!
* [QuestBoard Discord server](https://discord.gg/P7sUKVnP) - A quest community to hangout and talk about Beat Saber related stuff, you can also get a role to get notified when a new mod gets released!
* [Fixing Out of Sync Audio](https://bsaber.com/quest-out-of-sync/)
* [ScoreSaber Mod](https://new.scoresaber.com/quest) - Get in-game leaderboards for custom songs
* [ScoreSaber](https://scoresaber.com) - The website to view custom song leaderboards outside of the game.

## Troubleshooting
:::warning I watched a video tutorial on YouTube, but I got stuck/it didn't work. What gives? We at BSMG **strongly** advise against using any video tutorials for modding. Often, we find that they are either outdated or contain incomplete, erroneous, or straight up incorrect information.

Instead, you should follow the written guides here on the wiki or seek out help in the [BSMG Discord](https://discord.gg/beatsabermods). :::

### My Beat Saber gets 3 dots when I launch
If your Beat Saber is getting 3 dots when launching make sure that:

1. You launched and played one song before modding the game
2. You're not using a pirated version of the game
3. Make sure you're using the latest version of BMBF
4. Make sure you hit done instead of open when installing modded BeatSaber.

> If you did not do these last two, reinstall Beat Saber, and redo the BMBF setup process.

5. Make sure you have allowed Beat Saber permissions, you can check this by pressing the three dots next to beatsaber in the apps section and going into permissions.
6. If you have, try pressing Quick Fix in the Tools tab of BMBF.
7. Make sure you have given it 10-15 seconds to load.

If none of the above work, restart your headset and redo the modding process.

### Adding mods from beatmods.com or models from modelsaber.com does not work
The reason adding mods from [BeatMods](https://beatmods.com/) or models from [ModelSaber](https://modelsaber.com/) doesn't work is because those mods and models are for PC Only.

Get Quest compatible Mods from [QuestBoard](https://www.questmodding.com/) or `#quest-mods` in the Beat Saber Modding Group Discord, with Quest compatible sabers, bloqs, and walls in the [Qosmetics Community](https://discord.gg/qosmetics). Once you have your mod or model qmod use the [BMBF Web Interface](#using-your-pc) to install it.

### Sideloading BMBF failed
When sideloading BMBF and you get the error `INSTALL_FAILED_UPDATE_INCOMPATIBLE: Package com.weloveoculus.BMBF
signatures do not match the previously installed version; ignoring!`

You will need to uninstall the BMBF version on your Quest. You can do this from SideQuest's `My Apps` menu.

### Core mods don't work

If you are having problems with core mods, please verify that you are not trying to use any outdated mods. Any mod made for a previous game version is considered outdated. Once you have removed them:

1. Go to `Tools`
2. Click `Delete Mods`
3. Click `Sync to Beat Saber`

If you had mods installed before this, turn them off then on again to reinstall them.

---

### BMBF web interface not loading
If your BMBF Web Interface is not loading, Make sure you are typing the ip from the tools tab in the quest into your browser. If it still does not load, make sure you are doing the following:

* BMBF is open in the headset
* There is http:// at the beginning of the link, not https://
* You have :50000 at the end of your link
* Your pc and your quest are on the same Wifi
* Your ip hasn't changed, as it changes from time to time
* Your ip is not 127.0.0.1 If none of these work restart your quest and try them all again

---

### BMBF not loading configuration after a few minutes
This is likely due to using BMBF on a game version it was not built for. Such as using BMBF for Beat Saber version `1.13.0` when the version of the game installed on the headset is `1.12.2`.  
If the game version matches what the BMBF release page says its built for, try restarting your headset. If it still does not work use the [BMBF Web Interface](#using-your-pc) and click `Quick Fix` in the Tools tab.

---

### My Sabers and Mods wont enable/work
This is most likely due to having an outdated BMBF App, grab the latest [BMBF Release](https://bmbf.dev/stable). If the BMBF version for your Beat Saber is not there then please wait a while for the unicorns to update BMBF.

* If your level doesn't load then try installing mapping extensions from #quest-mods. It may also require the mod Noodle Extensions which isn't on Quest yet.
* If your BMBF is on the latest version and mods wont be enabled in game, uninstall Beat Saber with the uninstall BS button in the BMBF Tools tab then reinstall and remod.
* In very very very rare cases, BMBF does not have file permissions to copy mods into the right location. Check in SideQuest to make sure BMBF has file permissions.

---

### Beat Saber is crashing
If your game is crashing when doing something, disable your mods one by one, running your game each time to see if the issue is fixed before asking for help in a support channel.

### I only see a white screen when I open BMBF
If you only see a white screen when you open BMBF from unknown sources, try waiting a few seconds. If that does not work, restart your quest and try opening BMBF again.
=======
Bitte greife die Entwickler im Bezug mit Problemen bei Mods nicht an. Modder und Entwickler sind zwei verschiedene Gruppen. Sei kein Trottel. 
:::

## Installation
Derzeit ist BMBF auf SideQuest angewiesen. Die einzige Möglichkeit, Custom Songs und Mods zu installieren, ist, sich ebenfalls SideQuest auf einem Rechner zu installieren.

Wenn du keinen Zugang zu einem PC hast, kannst du ein [Android Handy](#bmbf-mit-einem-android-telefon-installieren) verwenden.

* [BMBF Apk](https://bmbf.dev/stable) 
:::warning WARNUNG
Wenn du BMBF installierst und du das Spiel modifizierst, wird der offizielle Multiplayer sowie das Anzeigen und Hochladen von Spielständen in den Basis-Spiel-Ranglisten deaktiviert. Wenn du den modifizierten Multiplayer spielen möchtest, benötigst du den Mod `Beat Together`, die Cross-Play zwischen Pc und Quest erlaubt und die Verwendung von Custom Songs, wenn beide Parteien den Song besitzen. Den Mod findest du in der Beat Saber Modding Group in `#quest-mods` oder auf der [Questboard](https://questmodding.com) Seite.

Um Ranglisten für Custom Songs zu erhalten und um Performance-Punkte (PP) aus gerankten Songs zu erhalten, benötigst du den [ScoreSaber](https://new.scoresaber.com/quest) Mod. [Dieser Link](https://new.scoresaber.com/quest) bringt dich auf die ScoreSaber Seite, um es einzurichten. ScoreSaber ersetzt nicht die Bestenlisten des Basis Games, sondern fügt nur Bestenlisten für Custom Songs hinzu.

**Hinweis:** Überprüfe den Aktualisierungskanal im [ScoreSaber Discord](https://discord.gg/WpuDMwU) , um zu sehen, ob die Mod für die aktuelle Spielversion verfügbar ist. 
:::

### BMBF mit SideQuest installieren
Solltest du dies nicht bereits getan haben, lade dir hier [SideQuest](https://sidequestvr.com/#/setup-howto) herunter und richte es ein

Öffne SideQuest und verbinde deine Quest mit deinem Computer.

:::tip TIPP
Wenn du Beat Saber bereits modifiziert hast oder Scores hast die du sichern willst, [Sichere zuerst deine Speicherdaten!](#Sichern-von-Speicherdaten-mit-Sidequest) 
:::

Wenn du ein modifiziertes Spiel hast, musst du es auch deinstallieren, indem du auf `UNINSTALL APP` drückst. Du kannst deinen Spielstand später im gleichen Menü wiederherstellen, nachdem du es modifiziert hast.

Wähle die unten gezeigte Schaltfläche `Apk aus Ordner installieren` und suche die neueste BMBF Apk, die du heruntergeladen hast, und klicke sie an, oder ziehe einfach die BMBF Apk in die SideQuest App. Bei beiden Methoden wird BMBF auf deiner Quest installiert.

![InstallAPK](~@images/beginners-guide/apkfromfolder.png)

Stelle nach erfolgreicher Installation sicher, dass du die neueste Version von Beat Saber installiert und unmodifiziert ist.

:::warning WARNUNG
Starte vor dem Modding Beat Saber einmal, starte ein Level und scheitere sofort! 
:::

Nachdem du Beat Saber einmal gestartet hast, öffne BMBF aus unbekannten Quellen, wie das untenstehende Bild zeigt. ![UnknownSources](~@images/beginners-guide/quest_home-menu.jpg)

Du solltest jeden Schritt so befolgen, wie er beschrieben ist. Danach solltest du dir [bsaber.com](https://www.bsaber.com) ansehen. Hier kannst du alle verfügbaren Custom Songs herunterladen. Du kannst auch auf das Globus-Symbol oben rechts klicken und dann auf BeatSaver gehen, um ebenfalls Lieder herunterzuladen.

Wenn du während des Installationsprozesses irgendwann das `App zurücksetzen` Popup siehst, klicke einfach auf `Schließen`. Diese Warnung richtet sich eher an raubkopierte Versionen des Spiels. Wenn du es also nur moddest, wird es wahrscheinlich keine Konsequenzen haben, wenn du sie ignorierest.

![RestoreApp](~@images/beginners-guide/restoreapp.png)

Nun kannst du mit dem Schritt [Kern Mods](#kern-mods) des Installationsvorgangs fortfahren.

### BMBF mit einem Android Telefon installieren
Dies ist **NICHT** der empfohlene Weg zur Installation von BMBF und sollte nur verwendet werden, wenn du keinen Zugang zu einem PC hast.

* [Anforderungen](#anforderungen)
* [Telefon einrichten](#telefon-einrichten)
* [BMBF mit deinem Telefon installieren](#bmbf-mit-deinem-telefon-installieren)
* [Beat Saber einrichten](#beat-saber-einrichten)

#### Anforderungen

* Ein Android-Telefon oder Android-Tablet (iPhones oder iPads werden nicht unterstützt)
* Eine **bezahlte** Version von Beat Saber im Oculus Quest Store
* Ein Kabel um deine Quest mit deinem Telefon zu verbinden (wenn dein Telefon über USB C geladen wird, sollte das Ladegerät, das mit deiner Quest mitgeliefert wurde, funktionieren).

#### Telefon einrichten

1. Lade die [bugjaeger-App aus dem Google Play Store](https://play.google.com/store/apps/details?id=eu.sisik.hackendebug&hl=gsw&gl=US) herunter
2. Lade die neueste [BMBF APK von bmbf.dev/stable](https://bmbf.dev/stable) herunter.
3. Folge [dieser schriftlichen Anleitung](https://github.com/ComputerElite/wiki/wiki/Enable-Developer-Mode-for-OQ) zum Aktivieren des Entwicklermodus auf Deiner Quest zu aktivieren.
4. Entwicklermodus auf Deinem Telefon aktivieren
    1. Gehe in deine Android Einstellungen
    2. Scrolle zu "Über Telefon" und öffne es
    3. Tippe auf "Software Informationen"
    4. Tippe auf das Feld "Build number", bis der Entwicklermodus aktiviert ist. Dies sollte etwa 7 Tippe erfordern.
5. USB-Debugging auf Deinem Telefon aktivieren
    1. Zurück zu Einstellungen
    2. Tippe auf "Entwickleroptionen"
    3. USB-Debugging aktivieren

#### BMBF mit Deinem Telefon installieren
:::warning WARNUNG
Starte vor dem Modding Beat Saber einmal, starte ein Level und scheitere sofort! 
:::

Öffne Bugjaeger auf deinem Telefon verbinden deine Quest. Du solltest ein USB-Debugging Pop-Up in deiner Quest und auf deinem Telefon erhalten. Wählen auf beiden Geräten "Zulassen" und wenn du möchtest, wähle "Immer zulassen". Sobald Bugjaeger deine Quest annimmt, installiere die BMBF APK indem du folgendes tust:

![installAPKusingPhone.png](~@images/beginners-guide/InstallAPK.png)

Nachdem du ok gedrückt hast, erlaube den Dateizugriff und wähle die Download-APK-Datei, die mit `com.weloveoculus.BMBF.apk` bezeichnet sein sollte. Die APK-Datei sollte nun auf deiner Quest installiert werden.

#### Beat Saber einrichten
Nach der erfolgreichen Installation von BMBF auf deiner Quest solltest du diese in deiner Quest-Bibliothek unter Unbekannten Quellen finden können.

![UnknownMenu](~@images/beginners-guide/quest_home-menu.jpg)

Öffne es und erlaube den Dateizugriff nach dem Start, wenn du dazu aufgefordert wirst. Folge nun sorgfältig den Anweisungen auf dem Bildschirm. Nachdem du fertig bist, solltest du [BeastSaber](https://bsaber.com) sehen.

Wenn du während des Installationsvorgangs das Popup-Fenster "App wiederherstellen" erhältst, klicke einfach auf "Schließen". Diese Warnung richtet sich an raubkopierte Versionen des Spiels, so dass es wahrscheinlich keine Konsequenzen hat, wenn du sie ignorierest, wenn du eine legitime Kopie besitzt.

Nun kannst du mit dem Schritt [Kern Mods](#kern-mods) des Installationsvorgangs fortfahren.

## Speicherdaten verwalten

### Sichere Speicherdaten mit SideQuest

Öffne SideQuest und verbinde deine Quest mit deinem Computer. Gehe zu `Meine Apps` in der oberen Leiste des Fensters und finde Beat Saber.

Navigiere zu `sdcard/Android/data/com.beatgames.beatsaber/files` mit Hilfe des SideQuest Datei-Explorers.

Speichere die Dateien: `AvatarData.dat`, `PlayerData.dat` und `settings.cfg` in einem Ordner auf Deinem PC. Verliere diese nicht, da sie deine Spielstände und andere Einstellungen enthalten!

### Sichere Speicherdaten mit SideQuest

Um deine Daten wiederherzustellen, öffne SideQuest und verbinde deine Quest mit dem PC. Gehe zu `Meine Apps` in der oberen Leiste des Fensters und suche Beat Saber. Finde mit dem SideQuest Datei-Explorer die 3 Dateien, die du aus den [Daten mit SideQuest wiederherstellen](#sichere-speicherdaten-mit-sidequest) Schritte `AvatarData.dat`, `PlayerData.dat` und `settings.cfg` und lege sie im Ordner `sdcard/Android/data/com.beatgames.beatsaber/files` ab.

Gehe danach zurück zum Menü und drücke auf die kreisförmigen Pfeile, die sich neben dem letzten Backup befinden. Deine Punkte und Einstellungen sollten nun wiederhergestellt werden.

## Mods installieren

### Kern-Mods
Bevor du weitere Mods installierst, solltest du in der BMBF-Weboberfläche oben rechts einen roten Button sehen, auf dem steht: `Sync to Beat Saber`. Klicke darauf und lass die Synchronisierung abschließen. Gehe dann zu deinem `Mods` Tab in BMBF. Stelle sicher, dass du die 5 Kern-Mods hast:

* Codegen
* Goodbye Bug
* PinkCore
* QuestUI
* Custom Types

:::danger WARNUNG
Alle anderen Mods funktionieren nicht, wenn diese Core-Mods nicht gelistet und aktiviert sind.

Wenn eine der Kern-Mods nicht aktiviert ist, lösche diese Mod und klicke erneut auf `Sync to Beat Saber`, um sie erneut herunterzuladen. Überprüfe mehrmals, ob alle Kern-Mods heruntergeladen und aktiviert wurden. Wenn es immer noch nicht funktioniert oder Mods aktiviert zu sein scheinen, aber im Spiel nicht funktionieren, findest du unter [Kern-Mods funktionieren nicht](#kern-mods-funktionieren-nicht) für Schritte zur Fehlersuche. 
:::

### In deiner Quest
:::warning WARNUNG
Nich alle Mods sind auf QuestBoard verfügbar  
Wenn dort eine Mod nicht zu finden ist, solltest du die [Von deinem PC](#von-deinem-pc) Methode benutzen. 
:::

Öffne BMBF auf deiner Quest und gehe zum `Browser` Tab. Dort solltest du ein Globus-Symbol sehen ähnlich zu dem unten gezeigten. Klicke es und dann klicke den `QuestBoard` Knopf.

![globequestboard](~@images/beginners-guide/globequestboard.png)

Du solltest mit der folgenden [QuestBoard](https://www.questmodding.com/)-Website begrüßt werden. Öffne dann den `DOWNLOAD MODS` Tab.

![questboardhome](~@images/beginners-guide/questboardhome.png)

Scrolle mit deinem Thumbstick herunter. Du kannst nun irgendwelche Mods von der Liste herunterladen, indem du auf den Download Button drückst. Manche Downloads könnten dich zu einer Webseite oder einer GitHub Seite weiterleiten. Wenn es so ist, dann folge den Anweisungen oder klicke auf die neuste `.zip` in der Release Liste.

![questboardmods](~@images/beginners-guide/questboardmods.png)

### Von deinem PC
Du kannst andere Quest-Mods im [BSMG-Discord](https://discord.com/invite/beatsabermods) finden und im `#quest-mods` Kanal herunterladen.

:::warning WARNUNG
Stelle sicher, dass deine Quest und dein PC im gleichen Netzwerk sind und dass du http und nicht https verwendest! 
:::

Öffne BMBF auf deiner Quest und gehe dort zu dem `Tools` Tab. Dort solltest du eine Webadresse und Versionsnummer sehen, die ähnlich zu der unten gezeigten ist.

![ip](~@images/beginners-guide/ip.png)

Öffne deinen Browser auf deinem PC und schreibe die Webadresse in die Suchleiste.

Dort solltest du folgenden Bildschirm sehen.

Wenn dies nicht funktioniert, [klicke hier](#das-bmbf-web-interface-ladt-nicht) für einige Schritte zur Fehlerbehebung.

![bmbfweb](~@images/beginners-guide/bmbfweb.png)

Ziehe jetzt eine Quest-kompatible Mod in das Upload Feld und synchronisiere diese. Wenn die Mod für eine ältere Version gemacht ist, wird sie nicht automatisch aktiviert. Um eine alte Mod zu aktivieren, gehe zum `Mods` Tab und aktivierst sie dort.

## Songs installieren
::: tip TIPP
Die meisten Maps in den Sortierfiltern "Top All", "Rating", "Downloads" oder "Plays" wurden erstellt, bevor gute Mapping-Praktiken etabliert wurden. Versuche Songs herunterzuladen, die zwischen Ende 2019 und jetzt veröffentlicht wurden, um die besten benutzerdefinierten Levels zu erleben. 
:::

### In deiner Quest
Es gibt zwei Quellen um eigene Songs in deiner Quest über das Browser Fenster zu bekommen.

* Wenn du nach kuratierten Songs und Playlists suchst besuche [BeastSaber](https://bsaber.com/)
* Wenn du die Benutzeroberfläche von BeastSaber nicht magst kannst du [BeatSaver](https://beatsaver.com/) ausprobieren

Beide haben einen OneClick Knopf welchen den Song einfach auf deine Quest installiert. Du kannst zwischen diesen Webseiten wechseln, indem du oben rechts in dem Browser Fenster auf das Globus Icon klickst.

Eine einfache Möglichkeit, verschiedene Arten von Song herunterzuladen, ist die Verwendung von `Syncsaber`. Du kannst darauf zugreifen, indem du auf deiner Suche in BMBF und auf die Registerkarte mit dem Namen `Syncsaber` klickst. Hier kannst du Songs mit einem Klick herunterladen. Du kannst aus verschiedenen "Einstellungen" auswählen. Zum Beispiel kannst du die Top 20 Songs im [Beatsaver's](https://beatsaver.com/) "Hot" Bereich herunterladen oder die 50 am besten bewerteten Songs.

Eine andere Methode ist die Verwendung der `Bookmark`-Funktion auf [Beastsaber](https://bsaber.com/). Nachdem du ein Konto erstellt hast, kannst du auf ein kleines Lesezeichen-Symbol auf einen Song klicken. Wenn du später alle deine Songs aus der Quest löschst, kannst du die Songs, die mit einem Lesezeichen versehen sind, mit OneClick™ erneut herunterladen.

### Von deinem PC
Wenn du keine Songs auf deiner Quest installieren kannst, kannst du sie über deinen Computer installieren, was ähnlich ist wie das installieren von Mods.

1. Öffne [BeastSaber](https://bsaber.com/) oder [BeatSaver](https://beatsaver.com/) auf deinem Computer
2. Lade die Zip herunter
3. Folge den [Installation von Mods mit Ihrem PC](#von-deinem-pc) Schritte bis zum Upload Datei Bildschirm.
4. Ziehe die Song Zip in das Upload Feld und er sollte installiert werden!

Wenn dies nicht funktioniert, [klicke hier](#problembehandlung) für einige Schritte zur Fehlerbehebung.

:::tip TIPP
Du kannst Playlists auch auf die gleiche Weise herunterladen. Du kannst verschiedene Playlists auf [BeastSaber](https://bsaber.com/category/playlists/) oder verschiedenen Community Discords finden. Du kannst auch deine eigenen erstellen, indem du den [BMBF Manager](https://github.com/ComputerElite/BM#bmbf-manager) oder [Playlist Editor Pro](https://beatsaberquest.com/playlisteditor-pro/) verwendest.

Wenn du eine von deinen erstellte Map testen möchtest, findest du im Abschnitt [Testen auf einer Quest](/de/mapping/#testen-auf-einer-quest) im Mapping Wiki Abschnitt für Schritte zum Verpacken für das Testen! 
:::

## Modelle installieren
Trete der [Qosmetics Community](https://discord.gg/qosmetics) bei um zu ändern wie dein Menütitel, deine Saber, Blöcke oder Walls im Spiel aussehen!

## Nützliche Links

* [Qosmetics Community](https://discord.gg/qosmetics) - Ein Server spezialisiert auf das Machen und Nutzen von Sabern, Noten und Wänden für die Quest.
* [Qosmetics Creation Guides](https://github.com/RedBrumbler/Qosmetics/wiki) - Anleitungen zum Erstellen von eigenen Sabern, Noten und Wänden für die Quest.
* [Questboard website](https://questmodding.com) - Ein Ort um die neuesten Informationen und Nachrichten zum Thema Beat Saber und die neuesten Mod Versionen!
* [Questboard Discord Server](https://discord.gg/P7sUKVnP) - Eine Quest-Community zum chillen und reden über Beat Saber und ähnliches. Du kannst auch eine Rolle bekommen um benachrichtigt zu werden, wenn eine neue Mod veröffentlicht wird!
* [Beheben von Audiosynchronisationsfehlern](https://bsaber.com/quest-out-of-sync/)
* [ScoreSaber](https://new.scoresaber.com/quest) - Ranglisten für eigene Songs im Spiel

## Problembehandlung
:::warning Ich habe das Video von Elite Eric angeschaut, aber ich hänge fest/Es hat nicht funktioniert. Wie kommts? 
BSMG rät **stark** davon ab, jegliche Beat Saber Tutorials von Elite Eric zu verweden. Nach Überprüfung seiner Videos haben wir festgestellt, dass sie viele unvollständige, fehlerhafte oder geradezu falsche Informationen enthalten. Versuche, auf ihn zuzugehen um diese Fehler zu korrigieren, wurden leider mit Schweigen und neuen (auch falschen) Tutorials erfüllt.

Stattdessen solltest du den Anleitungen auf dem Wiki folgen, überprüfte Tutorials von oben verlinkten BSMG-Mitgliedern anschauen oder im [BSMG Discord](https://discord.gg/beatsabermods) nach Hilfe fragen. 
:::

### Das Hinzufügen von Mods von beatmods.com oder Modellen von modelsaber.com funktioniert nicht
Der Grund, warum das Hinzufügen von Mods von [BeatMods](https://beatmods.com/) oder Modellen von [ModelSaber](https://modelsaber.com/) nicht funktioniert liegt darin, dass diese Mods und Saber nur für den PC geeignet sind.

Du kannst dir Quest kompatible Mods von [Questboard](https://www.questmodding.com/) oder `#quest-mods` aus dem Beat Saber Modding Group Discord holen und Quest kompatible Saber, Noten und Walls in der [Qosmetics Community](https://discord.gg/qosmetics). Sobald du deine Mod oder deine Modell ZIP hast, benutze das [BMBF Web Interface](#von-deinem-pc) um sie zu installieren.

### Sideloading von BMBF ist fehlgeschlagen
Wenn du während des Sideloadings von BMBF den Fehler `INSTALL_FAILED_UPDATE_INCOMPATIBLE: Package com.weloveoculus.BMBF signatures do not match the previously installed version; ignoring!` bekommst,

dann musst du die aktuelle BMBF-Version auf deiner Quest deinstallieren. Du kannst dies von dem Menü `My Apps` in Sidequest machen.

### Kern-Mods funktionieren nicht

Wenn du Probleme mit den Kern-Mods hast, stelle bitte sicher, dass du keine veralteten Mods verwenden möchtest. Jede Mod, die für eine frühere Spielversion erstellt wurde, gilt als veraltet. Sobald du diese entfernt hast:

1. Gehe zu `Tools`
2. Klicke auf `Exit BMBF`
3. Öffne BMBG erneut
4. Gehe nochmal zu `Tools`
5. Klicke auf `Quick Fix`
6. Gehe zum `Browser` Abschnitt der BMBF App.
7. Klicke auf das kleine Globus-Symbol in der oberen rechten Ecke
8. Klicke auf `QuestBoard`
9. Klicke auf `Download Mods`
10. Scrolle nach unten und klicke auf `Download All Core Mods`
11. Klicke dann auf `Sync to Beat Saber`

---

### Das BMBF Web Interface lädt nicht
Wenn dein BMBF Web-Interface nicht lädt, stelle sicher, dass du die IP von dem Tools Tab von BMBF in dem Browser auf deinen PC eingibst und deine Quest und dein Computer in dem selben Netzwerk sind. Stelle sicher, dass:

1. Deine IP nicht `127.0.0.1` ist. Wenn dies angezeigt wird, starte deine Quest und/oder Router neu.
2. BMBF im Headset geöffnet ist
3. Das `http://` am Anfang des Links steht, nicht `https://`
4. Du hast `:50000` am Ende des Links
5. Dein PC und deine Quest befinden sich im selben WLAN Netzwerk
6. Deine IP ist immer noch die gleiche, da sie sich von Zeit zu Zeit ändern kann

Wenn nichst davon funktioniert, starte deine Quest neu und gehe wieder durch die Liste.

---

### BMBF lädt die Konfiguration nicht nach ein paar Minuten
Wahrscheinlich wird eine BMBF Version verwendet, die nicht für diese Spielversion entwickelt wurde. Beispielsweise, wenn man eine BMBF Version verwendet, welche für Beat Saber `1.13.0` entwickelt wurde, die installierte Version auf dem Headset jedoch `1.12.2` ist.  
Falls die Spiel-Version dem entspricht was auf der BMBF Release Seite steht wofür es entwickelt wurde, starte bitte dein Headset neu. Falls es immer noch nicht funktionieren sollte, benutze das [BMBF Web Interface](#von-deinem-pc) und klicke auf `Quick Fix` unter dem Tab Tools.

### Beat Saber ist schwarz, wenn ich es starte
Öffne die Bibliothek auf deiner Quest. Klicke dort auf die drei Punkte neben Beat Saber und klicke auf `Berechtigungen`. Aktiviere dann in dem Menü dass sich öffnet die Speicher Berechtigung und versuche das Spiel erneut zu starten.

---

### Meine Mods und Saber funktionieren/aktivieren sich nicht
Dies ist vermutlich auf einen veralteten BMBF Client zurückzuführen . Nimm die neuste Version von den [BMBF Veröffentlichungen](https://bmbf.dev/stable). Wenn die BMBF Version für deine Beat Saber Version noch nicht da ist, dann warte bitte bis die Unicorns BMBF aktualisieren.

* Wenn deine Mod mit deiner Version kompatibel ist, dann stelle sicher, dass es keinen Order gibt der den Inhalt der Zip separiert.
* Wenn ein Level nicht lädt, versuche die Mapping Extensions von #quest-mods zu installieren. Es kann auch die Mod Noodle Extensions benötigen, die noch nicht auf Quest verfügbar ist.
* Wenn BMBF auf der neuesten Version ist und Mods im Spiel nicht aktiviert werden, deinstalliere Beat Saber mit der Schaltfläche "BS Deinstallieren" im Abschnitt Tools, installiere das Spiel neu und führe Mods erneut aus.
* In sehr sehr seltenen Fällen hat BMBF keine Dateirechte, um Mods an den richtigen Ort zu kopieren. Überprüfe in SideQuest ob BMBF über alle Dateirechte verfügt.

---

### Beat Saber stürzt ab
Sollte dein Spiel abstürzen, wenn du etwas machst, deaktiviere die Mods nacheinander und starte das Spiel jedes Mal, um zu sehen, ob das Problem behoben ist, bevor du in einem Support-Kanal um Hilfe bittest.

### Ich sehe nur einen weißen Bildschirm, wenn ich BMBF öffne
Wenn du beim Öffnen des BMBF aus unbekannten Quellen nur einen weißen Bildschirm siehst, starte deine Quest neu. Das Problem sollte dann behoben sein

### Mein Spiel zeigt mir den Ladebildschirm in Dauerschleife
Wenn Beat Saber beim Starten 3 Punkte hat(Ladebildschirm), stelle sicher, dass:

1. Du hast einen Song gestartet und gespielt, bevor du das Spiel modifiziert hast
2. Du verwendest keine raubkopierte Version des Spiels
3. Stelle sicher, dass du die neueste Version von BMBF verwendest
>>>>>>> master
