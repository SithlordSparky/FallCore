# JustinKringstad's FallCore Modlist
<img src="https://raw.githubusercontent.com/SithlordSparky/FallCore/refs/heads/main/Assets/Fallcore.webp" alt="FallCore">

FallCore runs on Next Gen, 1.10.163.


FallCore is a simple core setup for Fallout 4.  A great spot to start a new modlist.  All the mods and tools needed to get into the game.

It contains F4SE, Buffout 4 and several other F4SE based bugfixes and useful building utilities. In addition it contains the UFO4P, and Modding Tools needed for Fallout 4.

- [Quick Links](#quick-links)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behaviour](#change-steams-update-behaviour)
      - [Set the Game language to English](#set-the-game-language-to-english)
    - [Reverting a "cleaned" Fallout 4](#reverting-a-cleaned-fallout-4)
      - [Start Fallout 4](#start-fallout-4)
      - [Creation Club](#creation-club)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Automatic - Recommended](#automatic---recommended)
        - [Manual - Not Recommended](#manual---not-recommended)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
- [Setting Graphics options](#setting-graphics-options)
- [Installing owned Creation Club content](#installing-owned-creation-club-content)
- [Starting the Game](#starting-the-game)
- [Updating](#updating)
- [Other Post Installation FAQ](#other-post-installation-faq)
  - [Adjusting the resolution](#adjusting-the-resolution)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact and Technical Support](#contact-and-technical-support)

# Quick Links

- [Discord](https://discord.gg/dwGE5xFR) for community support with the mod list.

# Installation

## Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

It is unlikely that you are missing this. However it is needed for MO2 and several plugins, so please download it and install it anyway from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". This is [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Steam Config

#### Disable the Steam Overlay

![Steam_General_Settings](https://raw.githubusercontent.com/Yagisan/SS2-City-Plan-Contest-Helper/main/assets/images/Steam_General_Settings.webp)

The Steam Overlay can cause issues with ENB and is recommended to be turned off.
**Please note that this mod list does not use an ENB.**

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox. You should also un-tick the _Keep games saves in the Steam Cloud_.

#### Change Steams Update Behaviour

![Steam_Update_Settings](https://raw.githubusercontent.com/Yagisan/SS2-City-Plan-Contest-Helper/main/assets/images/Steam_Update_Settings.webp)

Fallout 4 is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_.

#### Set the Game language to English

![Steam_Language_Settings](https://raw.githubusercontent.com/Yagisan/SS2-City-Plan-Contest-Helper/main/assets/images/Steam_Language_Settings.webp)

This modlist is in English, and most of the mods you find are in English. **I can not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

### Reverting a "cleaned" Fallout 4

A lot of older modding guides recommended "cleaning" the Fallout 4 master esm files. **If you have "cleaned" your files this list will fail to install.** If you have done this, please re-verify the Fallout 4 files through Steam. Steam will fix your Fallout 4 master files, and you can then reinstall this list.

#### Start Fallout 4

![Fallout_Launcher](https://raw.githubusercontent.com/Yagisan/SS2-City-Plan-Contest-Helper/main/assets/images/Fallout_Launcher.webp)

On a brand new installation of Fallout 4, or after reverting a "cleaned" Fallout 4, you will need to launch Fallout 4 before you can install this mod list. Start the Launcher and open the _Options_ menu.

![Fallout_Launcher_Options](https://raw.githubusercontent.com/Yagisan/SS2-City-Plan-Contest-Helper/main/assets/images/Fallout_Launcher_Options.png)

1. Click on _Ultra_
2. Set the  _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _TAA_
4. **Do not** check _Windowed Mode_ and _Borderless_

**Start the game and exit once you're in the main menu.**

#### Creation Club

If you own any items from the Creation Club, they are not automatically reinstalled when you install Fallout 4. To reinstall Creation Club items, you must launch the game, select the Creation Club menu option, select the purchased option, then download each Creation club item individually.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [the Nexus](https://www.nexusmods.com/site/mods/403) and place the `Wabbajack.exe` file in a _working folder_.  The recommended working folder is `C:\WJ\WabbaJack`. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

##### Automatic - Recommended

1. Open Wabbajack.
2. Click on **Browse Modlists**. Under Games, select Fallout 4. Enable "Show Unofficial Lists". Select FallCore from the selection.
3. Set the _installation location_. The recommended installation location is `C:\WJ\FallCore`.  This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. **The rest of this document will assume you are using the recommended installation path.** Do not install to a _OneDrive_ folder.
4. Set the _download location_. The recommended download location is `C:\WJ\FallCore_downloads`.  This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. Do not install to a _OneDrive_ folder.
5. Check **Overwrite Installation**
6. Click the Go/Begin button
7. Wait for Wabbajack to finish
8. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Manual - Not Recommended

1. [Download the latest released .wabbajack file from GitHub](https://github.com/SithlordSparky/FallCore/tree/main/Releases). Save it to a temporary folder. The recommended temporary folder is `C:\Temp\FallCore`.
2. Open Wabbajack.
3. Click on Install from Disk. Set the target modlist to `C:\Temp\FallCore`
4. Set the _installation location_. The recommended installation location is `C:\WJ\FallCore`.  This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. **The rest of this document will assume you are using the recommended installation path.**
5. Set the _download location_. The recommended download location is `C:\WJ\FallCore_downloads`.  This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder.
6. If you have existing downloads from Vortex or MO2, you may copy the `.zip`, `.7z`, or `.rar` files only to the _download location_. The recommended download location is `C:\WJ\FallCore_downloads`. If the file you copy is exactly the same as what this wabbajack users, it will not be downloaded again, saving bandith.
7. Click the Go/Begin button. Wabbajack will check your downloads for matching files, and download any files it needs.
8. Wait for Wabbajack to finish
9. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

#### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you will not lose progress.

**Could not download x**:

If a mod updated and the old files were deleted, it is impossible to download them. You will need to be patient and wait for me to update the modlist.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

## Post-Installation

# Setting Graphics options

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. This will be `C:\WJ\FallCore\ModOrganizer.exe` if you have followed the recommended settings. Once it is launched, there will be a dropdown box on the top right and a big run button right next to it.

 Ensure it is set to **Fallout Launcher** by selecting it in the dropdown box and then hitting the run button. You have to run the Fallout Launcher through Mod Organizer 2 in order update your graphics settings for Yagisan's SimSettlements 2 City Plan Contest Helper.

 ![Fallout_Launcher_Options](https://raw.githubusercontent.com/Yagisan/SS2-City-Plan-Contest-Helper/main/assets/images/Fallout_Launcher_Options.png)

1. Click on _Ultra_
2. Set the  _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _TAA_
4. **Do not** check _Windowed Mode_ and _Borderless_
5. Click OK.
6. **Quit the Fallout 4 Launcher**

# Installing owned Creation Club content

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. This will be `C:\WJ\FallCore\ModOrganizer.exe` if you have followed the recommended settings. **Once it is launched, click on the jigsaw puzzle icon in the menu bar. Then select Creation Organizer. Then restart the SS2CPC Helper.** You should do this after you download new Creation Club content, to get changes and updates.

# Starting the Game

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. This will be `C:\WJ\FallCore\ModOrganizer.exe` if you have followed the recommended settings. Once it is launched, there will be a dropdown box on the top right and a big run button right next to it.

Ensure it is set to **F4SE** by selecting it in the dropdown box and then hitting the run button. You have to run F4SE through Mod Organizer 2 in order to play Yagisan's SimSettlements 2 City Plan Contest Helper.

# Updating

If this Modlist receives an update please check the [Changelog](CHANGELOG.md) before doing anything. The [Changelog](CHANGELOG.md) will advise you of any changes to addons. **Back up your save games before updating** Save files should be untouched when updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

Your downloads folder will not be touched.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.



# Other Post Installation FAQ

## Generating Textures and LOD's
If you are wanting to generate Textures and LOD's, All the required tools are included in this pack.
Use this guide: [LOD Generation Instructions](https://www.nexusmods.com/fallout4/articles/4162)

## Adjusting the resolution
By default the list ships with a safe 720p fullscreen configuration. To change this, click on `F4SE` in the dropdown list. Select `Fallout 4 Launcher` then click run. Adjust your settings as in vanilla, then  quit the launcher. Click on `Fallout 4 Launcher` in the dropdown list. Select `F4SE` then click run to start the game.

## Removing the Modlist
Simply delete the installation folder (`C:\WJ\FallCore` if you have been following this guide) and that will remove it, but why would you want to?

## Contact and Technical Support
Please check the [Issues](https://github.com/SithlordSparky/FallCore/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. If you believe you have found a bug in the mod list, please file bug report [here](https://github.com/SithlordSparky/FallCore/issues) with as much information as possible to replicate the issue. There is a [Support Discord](https://discord.gg/dwGE5xFR) for issues with the mod list. Requests for support on any other platform will be ignored.
