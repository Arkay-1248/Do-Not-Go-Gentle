# Animonculory Visual Overhaul

Wabbajack Modlist Installer by The Animonculory Team

**Modlist Download: [Needs to be Changed]()**

**Modlist Support: [The Animonculory Server](https://discord.gg/DffHKcszfg)**

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing AVO](#downloading-and-installing-AVO)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating AVO](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)


  ## Preamble

  AVO should be a base for your own modlist. It contains mostly graphical enhancements and mandatory bug fixes. AVO is made for Skyrim Anniversary Edition (AE) and uses the .exe of it as well (important for making your list) 

  This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

AVO as a base is aimed at mid tier machines so a system like the following is adviced:

### 1080p (my specs)
- CPU: AMD Ryzen 7 3700X
- RAM: 16GB DDR4
- Drive: SSD
- GPU: NVIDIA GeForce RTX 3070 8GB

It will prob run good on lower specs as well but I recommend at least 6GB VRAM (GPU)

Space required: Approx TBC(NeedsChangeLater)GB (Downloads included)

## Installation

Installing AVO is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing AVO, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside /Documents/My Games/.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like C:\Games is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. You also need to start the games to the main menu in order to download all the creations

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing AVO

Downloading and installing AVO can take a while depending on your internet connection and computer. To install AVO, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on AVO and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\AVO. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder

AVO uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.


### ENB
//needs to be changed later on//


AVO comes already set up with [Ominous ENB](https://www.nexusmods.com/skyrimspecialedition/mods/27333) for Obsidian Weathers. In the executables drop down menu in MO2, you will find an ENB Organizer that provides you with **two** options. Depending on your PC you might want to check them out. If you want to install your own ENB put them into a seperate folder in AVO/tools/Enb Manager/Managed ENB. You need to manually add them in the ENB Manager program afterwards. Click on Skyrim --> Go to the preset Tab --> Add preset.\
Take a look at [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) for more information.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the run button.

### In-Game MCM options

- This serves as a placeholder in case you want to use the Readme as some sort of template

### Starting the Game

Placeholder for your Readme, by default AVO uses the vanilla start


## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

Placehoder for your readme

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must then you can.

## Removing the Modlist
Simply delete the folder and you have uninstalled it.


## Credits and Thanks

- _YOU_ for reading this.
- Althro for assisting with so many things. And allowing me to fork the readme. You’re awesome.
- Chef for the help with the armors
- Spaniard for being an invaluable source of knowledge and helping me a lot with the mod choices.
- Destiny for proofreading the readme and pointing out many errors. Also for testing the list and giving helpful suggestion to improve it
- Astro for testing and giving reports, more detailed than I ever expected. Seriously, thanks a lot
- The Animonculory Dev Team.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

