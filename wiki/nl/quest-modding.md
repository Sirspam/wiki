---
sidebar: auto
---

# Quest Modding

## Voorwoord

* Deze gids is van toepassing voor zowel Quest 1 als Quest 2.
* Niemand is tot nu toe gebanned voor het modden van het spel.

<<<<<<< HEAD
::: danger DISCLAIMER Door mods te gebruiken, begrijp je dat:
=======
::: danger DISCLAIMER 
Door mods te gebruiken, begrijp je dat:
>>>>>>> master

* Je ervaart mogelijk problemen die niet voorkomen in de onaangepaste versie van het spel. 99,9% van de bugs, crashes en lag zijn te wijten aan mods.
* Mods worden vrijwel altijd onbruikbaar bij game updates en dat is normaal - wees geduldig en blijf respectvol wanneer dit gebeurt, want de modders zijn vrijwilligers met andere dingen in hun leven naast het maken van mods.
* Beat Games probeert niet met opzet ervoor te zorgen dat mods niet meer werken. Ze willen enkel aan hun eigen code werken en soms maakt dit mods onbruikbaar, maar dit betekent dus niet dat ze expres mods in de weg zitten.

<<<<<<< HEAD
Val de ontwikkelaars niet aan voor problemen gerelateerd aan het gebruik van mods, en vice versa - de modders en spel ontwikkelaars zijn twee aparte groepen. Wees gewoon geen eikel. :::

:::warning Ik heb een video tutorial bekeken op YouTube, maar ik liep vast / het werkte niet. Waarom? Wij van de BSMG raden het **sterk** af om video tutorials te gebruiken voor het modden. Vaak vinden we dat de inhoud is verouderd, of dat ze incompleet zijn, of dat ze foute of gewoon incorrecte informatie bevatten.

In plaats daarvan is het beter de geschreven gidsen te volgen die hier op de wiki beschikbaar zijn, of om hulp te vragen in de [BSMG Discord](https://discord.gg/beatsabermods). :::

## Installatie
Currently the only recommended way to install custom songs and mods is BMBF sideloaded with [SideQuest using a PC](#installing-bmbf-with-sidequest).

If you do not have access to a PC you can use an [Android Phone or Tablet](/support/modding-with-android.md). Chromebooks and iOS devices such as iPhones or iPads are not supported.

:::warning Installing BMBF and modding your game will disable Official Multiplayer as well as viewing and uploading scores on the base game leaderboards. If you would like to play modded multiplayer, you need the mods, `Beat Together` and `MultiQuestensions`, which allows for cross-play between PC and Quest and allows for custom songs to be used. These mods can be found in the [Beat Saber Modding Group](discord.gg/beatsabermods) in `#quest-mods` or on the [Questboard](https://questmodding.com) site.

To get leaderboards on custom songs and to be able to get Performance Points (PP) from ranked songs you need the [ScoreSaber](https://new.scoresaber.com/quest) mod. [This link](https://new.scoresaber.com/quest) will take you to the ScoreSaber page to set it up. ScoreSaber does not replace the base game leaderboards, it only adds leaderboards for custom songs.

**Note:** Check the updates channel in the [ScoreSaber Discord](https://discord.gg/WpuDMwU) to see if the mod is available for the current game version. :::

### Het installeren van BMBF met SideQuest
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

## Gegevens beheren

### Backup Save Data using SideQuest

Open SideQuest and connect your Quest to your PC.

Navigate to `sdcard/Android/data/com.beatgames.beatsaber/files` using the SideQuest file explorer.

![SideQuest Files](~@images/beginners-guide/sqfiles.png)

Save the files: `AvatarData.dat`, `PlayerData.dat` and `settings.cfg` into a folder on your PC. Do not lose these, as they contain your scores and other settings!

### Restoring Save Data using SideQuest

To restore your data, open SideQuest and connect your Quest to your PC.  
Using the SideQuest file explorer, take the 3 files you saved from the [Backup Save Data using SideQuest](#backup-save-data-using-sidequest) steps `AvatarData.dat`, `PlayerData.dat` and `settings.cfg` and put them in the `sdcard/Android/data/com.beatgames.beatsaber/files` folder.

## Het installeren van mods

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

## Het installeren van nummers
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

## Het installeren van modellen
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
Val de ontwikkelaars niet aan voor problemen gerelateerd aan het gebruik van mods, en vice versa - de modders en spel ontwikkelaars zijn twee aparte groepen. Wees gewoon geen eikel.
:::

:::warning Ik heb een video tutorial bekeken op YouTube, maar ik liep vast / het werkte niet. Waarom? 
Wij van de BSMG raden het **sterk** af om video tutorials te gebruiken voor het modden. Vaak vinden we dat de inhoud is verouderd, of dat ze incompleet zijn, of dat ze foute of gewoon incorrecte informatie bevatten.

In plaats daarvan is het beter de geschreven gidsen te volgen die hier op de wiki beschikbaar zijn, of om hulp te vragen in de [BSMG Discord](https://discord.gg/beatsabermods).
:::

## Installatie
Op dit moment is het installeren van BMBF met SideQuest op een PC de enige aanbevolen manier om custom levels en mods te installeren.

Als je geen toegang hebt tot een PC, kan je ook een [Android telefoon](#het-installeren-van-bmbf-met-een-android-telefoon) gebruiken.

* [BMBF apk](https://bmbf.dev/stable) 

:::warning Waarschuwing
Het installeren van BMBF en het modden van je spel zal de officiële multiplayer, en het bekijken en uploaden van scores op de officiële scoreborden van het spel uitschakelen. Als je modded multiplayer wil spelen, dan heb je de `Beat Together` mod nodig. Deze mod maakt het mogelijk om multiplayer samen te kunnen spelen ongeacht het platform, dus zowel met spelers die gebruik maken van Quest of PC, en het zorgt ervoor dat custom levels kunnen worden gespeeld op voorwaarde dat iedereen het liedje al gedownload heeft. De mod kan worden gevonden in de Beat Saber Modding Group in het `#quest-mods` kanaal of op de [Questboard](https://questmodding.com) website.

Je hebt de [ScoreSaber](https://new.scoresaber.com/quest) mod nodig als je scoreborden voor custom levels wil hebben en Performance Points (PP) van gerangschikte nummers wil kunnen verdienen. [Deze link](https://new.scoresaber.com/quest) zal je naar de ScoreSaber pagina brengen om het in te stellen. ScoreSaber vervangt de de officiële scoreborden van het spel niet, het voegt alleen scoreborden voor custom levels toe.

**Opmerking:** Controleer het updates kanaal in de [ScoreSaber discord](https://discord.gg/WpuDMwU) om te zien of de mod beschikbaar is voor de huidige versie van het spel. 
:::

### Het installeren van BMBF met SideQuest
Download en stel [SideQuest](https://sidequestvr.com/#/setup-howto) in als je dat nog niet gedaan hebt.

Open SideQuest en verbind je Quest met je PC.

:::tip Hint
Als je eerder een Beat Saber hebt gemod of scores hebt waarvan je een back-up wilt maken, [maak dan eerst een back-up van je gegevens!](#een-back-up-maken-van-je-gegevens-met-sidequest) 
:::

Als je al het spel hebt gemod, dan moet je het ook verwijderen door op de `UNINSTALL APP` knop te drukken. Na het modden kan je jouw gegevens weer herstellen vanuit hetzelfde menu.

Klik op de `Install APK from folder` knop, wat hieronder word aangeduid, en zoek de nieuwste BMBF apk die je hebt gedownload en klik er op, of sleep simpelweg de BMBF apk naar SideQuest. Beide methodes zullen BMBF op je Quest installeren.

![Installeren van de APK](~@images/beginners-guide/apkfromfolder.png)

Zodra het succesvol is geïnstalleerd, controleer dan zeker dat je de nieuwste versie van Beat Saber hebt geïnstalleerd en dat het niet is gemod.

:::warning Waarschuwing
Voordat je begint met modden, start Beat Saber een keer en speel en faal een level!

Het modden werkt momenteel niet als de experimentele multi-user functie in gebruik is. Je zal tijdelijk alle secundaire accounts moeten verwijderen voordat je het spel mod. Je kan ze later opnieuw toevoegen wanneer je je gewenste mods hebt geïnstalleerd. 
:::

Nadat je Beat Saber een keer hebt gestart, open je BMBF vanuit unknown sources zoals aangeduid op de afbeelding hieronder. ![Unknown Sources](~@images/beginners-guide/quest_home-menu.jpg)

Eens geopend, volg je elke stap in BMBF zoals hierin wordt verteld om je spel te modden. Wanneer je klaar bent, zou je [bsaber.com](https://www.bsaber.com) moeten zien in de BMBF app. Dit is de website waarvan je alle beschikbare custom levels kan downloaden. Je kan ook op het wereldbol icoontje in de rechterbovenhoek klikken en naar BeatSaver gaan om nummers te downloaden.

Als je op enig moment tijdens het installatieproces de `Restore App` pop-up krijgt te zien, klik dan op `Close`. Deze waarschuwing is meer gericht op illegale versies van het spel, dus als je alleen maar het spel mod, zullen er hoogstwaarschijnlijk geen consequenties zijn als je het negeert.

![Restore App](~@images/beginners-guide/restoreapp.png)

Ga verder naar de [Core mods](#core-mods) stap van het installatieproces.

### Het installeren van BMBF met een Android telefoon
Dit is **NIET** de aanbevolen manier om BMBF te installeren en zou alleen moeten worden gebruikt als je geen toegang hebt tot een PC.

* [Vereisten.](#vereisten)
* [Het instellen van je telefoon.](#het-instellen-van-je-telefoon)
* [Het installeren van BMBF met jouw telefoon.](#het-installeren-van-bmbf-met-jouw-telefoon)
* [Het instellen van Beat Saber.](#het-instellen-van-beat-saber)

#### Vereisten

* Een Android telefoon of Android tablet (iPhones en iPads worden niet ondersteund).
* Een **betaalde** versie van Beat Saber in de Oculus Quest Store.
* Een kabel om jouw Quest aan te sluiten op jouw telefoon (als jouw telefoon oplaadt via USB C zou de oplaadkabel die samen met je Quest werd meegeleverd moeten werken).

#### Het instellen van je telefoon

1. Download de [Bugjaeger app vanaf de Google Play store](https://play.google.com/store/apps/details?id=eu.sisik.hackendebug&hl=gsw&gl=US).
2. Download de nieuwste [BMBF APK van bmbf.dev/stable](https://bmbf.dev/stable).
3. Volg [deze gids](https://github.com/ComputerElite/wiki/wiki/Enable-Developer-Mode-for-OQ) om de ontwikkelaarsmodus op je Quest in te schakelen.
4. Ontwikkelaarsmodus inschakelen op jouw telefoon.
    1. Ga naar jouw Android-instellingen.
    2. Scroll naar "Over de telefoon" en open het.
    3. Druk op "Software informatie".
    4. Druk op het "Build-number" veld totdat je de melding ontvangt dat zegt dat ontwikkelaarsmodus is ingeschakeld. Dit zou na ongeveer 7 keer klikken moeten gebeuren.
5. USB-foutopsporing inschakelen op jouw telefoon.
    1. Ga terug naar instellingen.
    2. Druk op "Ontwikkelaarsopties".
    3. Activeer USB-foutopsporing.

#### Het installeren van BMBF met jouw telefoon
:::warning Waarschuwing
Voordat je begint met modden, start Beat Saber een keer en speel en faal een level! 
:::

Open Bugjaeger op jouw telefoon en verbindt jouw Quest. Je zou een USB-foutopsporingspop-up moeten krijgen in jouw Quest en op jouw telefoon. Selecteer 'allow' op beide apparaten, of als je het liever hebt, kan je ook op 'always allow' selecteren. Zodra Bugjaeger jouw Quest detecteert, installeer je de BMBF APK door het volgende te doen:

![Installeren van de APK met een telefoon](~@images/beginners-guide/InstallAPK.png)

Nadat je op ok hebt gedrukt, geef dan toegang tot de bestanden en selecteer het gedownloade APK-bestand met de naam `com.weloveoculus.BMBF.apk`. Het apk-bestand zou nu geïnstalleerd moeten worden op jouw Quest.

#### Het instellen van Beat Saber
Na het installeren van BMBF op je Quest, kan je het terugvinden in je Quest bibliotheek onder 'unknown sources'.

![Unknown Menu](~@images/beginners-guide/quest_home-menu.jpg)

Open het en sta bestandstoegang toe als ernaar word gevraagd. Volg nu zorgvuldig de instructies op het scherm. Als je klaar bent zou je [BeastSaber](https://bsaber.com) moeten zien in de BMBF app.

Als je op enig moment tijdens het installatieproces de `Restore App` pop-up krijgt te zien, klik dan op `Close`. Deze waarschuwing is meer gericht op illegale versies van het spel, dus als je alleen maar het spel mod, zullen er hoogstwaarschijnlijk geen consequenties zijn als je het negeert.

Nu kan je verder gaan naar de [Core Mods](#core-mods) stap van het installatieproces.

## Gegevens beheren

### Een back-up maken van je gegevens met SideQuest

Open SideQuest en verbind je Quest met je PC. Ga naar `My Apps` in de bovenste balk van het venster en zoek Beat Saber.

Navigeer naar `sdcard/Android/data/com.beatgames.beatsaber/files` met behulp van de SideQuest bestandsverkenner.

Sla de volgende bestanden: `AvatarData.dat`, `PlayerData.dat` en `settings.cfg` op in een map op jouw PC. Raak deze niet kwijt, omdat deze bestanden jouw scores en andere instellingen bevatten!

### Het herstellen van je gegevens met SideQuest

Om je gegevens te herstellen, open je SideQuest en verbind je jouw Quest met jouw PC. Ga naar `My Apps` in de bovenste balk van het venster en zoek Beat Saber. Met behulp van de SideQuest bestandsverkenner selecteer je de 3 bestanden die je hebt opgeslagen met de [Een back-up maken van je gegevens met SideQuest](#een-back-up-maken-van-je-gegevens-met-sidequest) stappen, `AvatarData.dat`, `spelerData.dat` en `settings.cfg`, en plaats ze in de `sdcard/Android/data/com.beatgames.beatsaber/files` map.

Ga terug naar het menu en druk op de ronddraaiende pijlen naast jouw nieuwste back-up. Jouw scores en instellingen zouden nu moeten worden hersteld.

## Het installeren van mods

### Core mods
Voordat je extra mods gaat installeren, kijk dan eerst naar de rechterbovenhoek in de BMBF webinterface, je zou daar een rode knop moeten zien waarop `Sync to Beat Saber` staat. Klik hierop en wacht tot het synchroniseren klaar is. Ga vervolgens naar het `mods` tabblad in BMBF. Zorg ervoor dat je de 5 core mods hebt:

* Codegen.
* Goodbye Bug.
* PinkCore.
* QuestUI.
* Custom Types.

:::danger Waarschuwing
Alle andere mods zullen niet werken als deze core mods niet geïnstalleerd en ingeschakeld zijn.

Als één van de core mods niet kan worden inschakelt, verwijder dan de mod en klik op `Sync to Beat Saber` om deze opnieuw te downloaden. Controleer vervolgens opnieuw of het gedownload en ingeschakeld is. Als het nog steeds niet werkt, of mods lijken ingeschakeld te zijn maar werken niet in het spel, zie dan [Core mods werken niet](#core-mods-don-t-work) voor stappen om het probleem op te lossen. 
:::

### Vanuit je Quest
:::warning Waarschuwing
Niet alle mods zijn beschikbaar op QuestBoard!  
Als een mod hier niet op staat, moet je de [Met behulp van jouw PC](#met-behulp-van-jouw-pc) methode gebruiken. 
:::

Open BMBF in je Quest en ga naar het tabblad `Browser`, daar zie je een wereldbol icoon, vergelijkbaar met wat hieronder word getoond. Klik hierop en klik vervolgens op de `QuestBoard` knop.

![Wereldbol icoon naar QuestBoard](~@images/beginners-guide/globequestboard.png)

Je zou begroet moeten worden met de [QuestBoard](https://www.questmodding.com/) website zoals hieronder staat. Selecteer vervolgens het `DOWNLOAD MODS` tabblad.

![QuestBoard hoofdpagina](~@images/beginners-guide/questboardhome.png)

Scroll naar beneden met je thumbsticks. Je kan nu elke mod selecteren uit de onderstaande lijst en deze downloaden door op de downloadknop te drukken. Sommige downloads kunnen je doorverwijzen naar een website of GitHub pagina. Als dat het geval is, volg dan de instructies op het scherm of selecteer de nieuwste `.zip` in de Releases lijst.

![QuestBoard mods](~@images/beginners-guide/questboardmods.png)

### Met behulp van jouw PC
Je kan Quest mods vinden en downloaden in de [BSMG Discord](https://discord.com/invite/beatsabermods) in het `#quest-mods` kanaal.

:::warning Waarschuwing
Zorg ervoor dat jouw Quest en PC op hetzelfde netwerk zijn en dat je "http" gebruikt en niet "https"! 
:::

Open BMBF in je Quest en ga naar het tabblad `Tools`, daar zie je een webadres en een versienummer vergelijkbaar met wat hieronder word getoond.

![IP adres in BMBF](~@images/beginners-guide/ip.png)

Open een browser op jouw PC, en typ het adres in de zoekbalk.

Je zou nu moeten worden begroet met het scherm hieronder.

Als dit niet werkt klik dan [hier](#de-bmbf-webinterface-laad-niet) voor enkele stappen om problemen op te lossen.

![BMBF webinterface](~@images/beginners-guide/bmbfweb.png)

Sleep nu alle mods die gemaakt zijn voor de Quest naar het uploadvak en synchroniseer. Als een mod oorspronkelijk is gemaakt voor een oudere versie van het spel, zal deze niet automatisch worden ingeschakeld. Om een mod in te schakelen die gemaakt is voor een oudere versie van het spel, ga je naar het tabblad `Mods` en schakel het daar in.

## Het installeren van nummers
::: tip Hint
De meeste levels in de "Top All", "Rating", "Downloads" of "Plays" sorteerfilters werden gemaakt voordat er best practices voor het maken van levels werden vastgelegd. Probeer levels te downloaden die tussen eind 2019 en nu gemaakt zijn voor de beste custom levels ervaring. 
:::

### Vanuit je Quest
Er zijn 2 websites waar je levels kan vinden vanuit je Quest via het browservenster.

* Als je op zoek bent naar playlists en nummers die worden aanbevolen, ga dan naar [BeastSaber](https://bsaber.com/).
* Als je de interface van BeastSaber niet tof vindt, kan je ook [BeatSaver](https://beatsaver.com/) proberen.

Beiden hebben een OneClick™ knop die het level gemakkelijk op je Quest installeert. Je kan wisselen tussen deze websites door gebruik te maken van het wereldbol-pictogram rechts bovenin het browservenster.

Een makkelijke manier om verschillende soorten nummers te downloaden, is door `Syncsaber` te gebruiken. Je kan het vinden in het `Syncsaber` tabblad in BMBF. Hier kan je levels downloaden met één enkele klik op een knop, en je kan uit verschillende "instellingen" kiezen. Je kan bijvoorbeeld de top 20 levels downloaden in de "hot" sectie van [BeatSaver](https://beatsaver.com/) of de 50 moeilijkste gerangschikte levels.

Een andere manier is het gebruik van de `Bookmark` functie op [BeastSaber](https://bsaber.com/). Nadat je een account hebt aangemaakt, kan je op het bookmark icoontje van een level klikken, en als je later al je levels van je Quest verwijderd, kan je al de levels die je gebookmarkt hebt opnieuw downloaden door middel van OneClick™.

### Met behulp van jouw PC
Als je geen levels kan installeren vanuit je Quest, kan je dat ook proberen met behulp van je computer, wat vergelijkbaar is met het installeren van mods.

1. Ga naar [BeastSaber](https://bsaber.com/) of [BeatSaver](https://beatsaver.com/) op je computer.
2. Download de zip.
3. Volg de [Het installeren van mods met behulp van jouw PC](#met-behulp-van-jouw-pc) stappen voor het uploaden van bestanden via het upload-scherm.
4. Sleep de zip in het upload venster en het zou geïnstalleerd moeten worden!

Als het webinterface niet laad, klik dan [hier](#de-bmbf-webinterface-laad-niet) voor enkele stappen die het probleem kunnen oplossen.

:::tip Hint
Je kan ook afspeellijsten op dezelfde manier downloaden. Je kan verschillende afspeellijsten vinden op [BeastSaber](https://bsaber.com/category/playlists/) of in verschillende community discords. Je kan ook je eigen afspeellijsten maken met [BMBF Manager](https://github.com/ComputerElite/BM#bmbf-manager) of [Playlist Editor Pro](https://beatsaberquest.com/playlisteditor-pro/).

Als je een level wilt testen, bekijk dan de [nummers testen op een Quest](/nl/mapping/#testing-on-a-quest) sectie in de mapping wiki voor stappen voor het klaar maken om nummers te testen! 
:::

## Het installeren van modellen
Wordt lid van de [Qosmetics Community](https://discord.gg/qosmetics) om te aan te kunnen passen hoe jouw menu titel, sabers, blokken en/of muren er uitzien in het spel!

## Handige links

* [Qosmetics Community](https://discord.gg/qosmetics) - Server gericht op het maken en gebruiken van sabers, blokken en muren voor Quest.
* [Qosmetics Creatie gidsen](https://github.com/RedBrumbler/Qosmetics/wiki) - Handleidingen om je eigen custom sabers, blokken en muren voor de Quest te maken.
* [QuestBoard website](https://questmodding.com) - Een plek om gerelateerd nieuws en informatie te krijgen over zowel Beat Saber als de nieuwste mods releases!
* [QuestBoard discord server](https://discord.gg/P7sUKVnP) - Een Quest community om in rond te hangen en te praten over Beat Saber gerelateerde zaken, je kan ook een rol krijgen om een notificatie te krijgen wanneer er een nieuwe mod wordt vrijgegeven!
* [Het oplossen van out-of-sync audio.](https://bsaber.com/quest-out-of-sync/)
* [ScoreSaber](https://new.scoresaber.com/quest) - In-game scoreborden voor custom levels.

## Probleemoplossing
:::warning Ik heb een video tutorial bekeken op YouTube, maar ik liep vast / het werkte niet. Waarom? 
Wij van de BSMG raden het **sterk** af om video tutorials te gebruiken voor het modden. Vaak vinden we dat de inhoud is verouderd, of dat ze incompleet zijn, of dat ze foute of gewoon incorrecte informatie bevatten.

In plaats daarvan is het beter de geschreven gidsen te volgen die hier op de wiki beschikbaar zijn, of om hulp te vragen in de [BSMG Discord](https://discord.gg/beatsabermods). 
:::

### Het toevoegen van mods van beatmods.com of modellen van modelsaber.com werkt niet
De reden dat het toevoegen van mods van [BeatMods](https://beatmods.com/) of modellen van [ModelSaber](https://modelsaber.com/) niet werkt, is omdat dat deze mods en modellen voor de PC versie van het spel gemaakt zijn.

Je kan Quest compatibele Mods op [QuestBoard](https://www.questmodding.com/) of in `#quest-mods` in de Beat Saber Modding Group Discord terugvinden, je kan ook Quest compatibele sabers, blokken en muren in de [Qosmetics Community](https://discord.gg/qosmetics) vinden. Als je je mod of model zip hebt, gebruik dan het [BMBF webinterface](#met-behulp-van-jouw-pc) om deze te installeren.

### Het installeren van BMBF is mislukt
Je krijgt de volgende error tijdens het installeren van BMBF `INSTALL_FAILED_UPDATE_INCOMPATIBLE: Package com.weloveoculus.BMBF
signatures do not match the previously installed version; ignoring!`

Je moet de geïnstalleerde BMBF versie de-installeren van je Quest. Je kan dit doen via het `My Apps` menu in SideQuest.

### De core mods werken niet

Als je problemen hebt met de core mods, controleer dan of je geen verouderde mods probeert te gebruiken. Elke mod dat gemaakt is voor een eerdere versie van het spel word gezien als verouderd. Van zodra je ze hebt verwijderd:

1. Ga naar `Tools`.
2. Klik op `exit BMBF`.
3. Open BMBF opnieuw.
4. Ga opnieuw naar `Tools`.
5. Klik op `Quick fix`.
6. Ga naar de `Browser` sectie van de BMBF app.
7. Klik op het kleine wereldbol icoontje rechts bovenaan.
8. Klik op `QuestBoard`.
9. Klik op `Download Mods`.
10. Scroll naar beneden en klik op `Download All Core Mods`.
11. Klik op `Sync to Beat Saber`.

---

### De BMBF webinterface laad niet
Als de BMBF webinterface niet laadt, zorg er dan voor dat het IP adres dat je in een browser op je computer typt, dat zich trouwens op hetzelfde netwerk bevindt, hetzelfde is als hetgene in het tools tabblad. Zorg ervoor dat:

1. Jouw IP adres niet `127.0.0.1` is. Als dat verschijnt, probeer dan jouw Quest en/of de router opnieuw op te starten.
2. BMBF geopend is in de headset.
3. Er `http://` staat aan het begin van de link, en niet `https://`.
4. Er `:50000` staat aan het einde van de link.
5. Jouw PC en Quest zich op hetzelfde wifi-netwerk bevinden.
6. Jouw IP adres nog steeds hetzelfde is omdat het van tijd tot tijd kan veranderen.

Als geen van deze dingen werken, start dan je Quest opnieuw op en probeer het nog een keer.

---

### BMBF laad het configuratiescherm niet na een paar minuten
Dit komt waarschijnlijk door het gebruik van BMBF op een versie van het spel waar het niet voor gemaakt is. Zoals het gebruik van BMBF voor Beat Saber versie `1.13.0` terwijl de versie van het spel dat geïnstalleerd is op de headset `1.12.2` is.   
Als de versie van het spel overeenkomt met wat de BMBF release pagina zegt, probeer dan je headset opnieuw op te starten. Als het nog steeds niet werkt, gebruik dan de [BMBF Webinterface](#met-behulp-van-jouw-pc) en klik dan op `Quick Fix` in het Tools tabblad.

### Beat Saber is zwart nadat ik het opstart
Open de bibliotheek op je Quest. Klik op de drie stippen naast Saber en klik vervolgens op `Permissions`. Schakel storage permissions in in het menu dat tevoorschijn komt, en start het spel opnieuw op.

---

### Mijn sabers en mods willen niet worden aangezet/werken
Dit komt waarschijnlijk omdat je een oude BMBF hebt geïnstalleerd, je kan [hier](https://bmbf.dev/stable) de nieuwste versie vinden. Als er geen BMBF versie is voor de Beat Saber versie dat jij hebt, wacht dan geduldig tot de unicorns BMBF hebben geüpdated.

* Als de mod gemaakt is voor de versie van BMBF dat jij hebt, zorg er dan voor dat er geen map in de zip zit die de inhoud van de zip van elkaar scheidt.
* Als een level niet laad, probeer dan de Mapping Extensions mod te installeren die te vinden is in #quest-mods. Het kan ook zijn dat het de "Noodle Extensions" mod nodig heeft, deze is er nog niet voor de Quest.
* Als BMBF up-to-date is en mods niet worden ingeschakeld in het spel, verwijder dan Beat Saber met de "uninstall BS" knop in het BMBF Tools menu en herinstalleer het.
* In het zeer zeldzame geval dat BMBF geen toegang tot bestanden heeft om mods naar de juiste locatie te kopiëren. Kijk dan in SideQuest en controleer dat BMBF bestandspermissies heeft.

---

### Beat Saber crasht
Als jouw spel crasht wanneer je iets doet of gedaan hebt, schakel dan je mods één voor één uit, en start het spel telkens weer opnieuw op om te kijken of het probleem opgelost is voordat je om hulp gaat vragen in een support kanaal.

### Ik zie alleen maar een wit scherm als ik BMBF open
Als je alleen maar een wit scherm ziet wanneer je BMBF opent vanuit unknown sources, start je Quest dan opnieuw op en dan zou het opgelost moeten zijn.

### Mijn Beat Saber laat 3 bollen zien wanneer ik het start
Als jouw Beat Saber 3 bollen laat zien bij het opstarten, zorg er dan voor dat:

1. Je één level hebt gestart én gespeeld voordat je het spel hebt gemod.
2. Je geen illegale versie van het spel hebt.
3. Je de nieuwste versie van BMBF gebruikt.
>>>>>>> master
