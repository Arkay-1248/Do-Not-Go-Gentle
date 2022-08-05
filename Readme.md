# Do Not Go Gentle

![image](https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/AVOAENewLogo.webp)

Wabbajack Modlist Installer by Abandoned_by_Arkay (Arkay-1248)

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/GitHub.png" width="72px" /></td>
<td><a href="https://discord.gg/DffHKcszfg">Support Discord</a></td>
</tr>
</table>

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
      - [Downloading and Installing DNGG](#downloading-and-installing-avo-ae)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
    - .[Updating the modlist].(#Updating-the-modlist)
    - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

**NOTE**: Do Not Go Gentle **REQUIRES** the paid update to Skyrim.

Do Not Go Gentle is designed as requiem modlist with Bruma, Wyrmstooth, and lots of other additions to extend the life of your character playthrough.  It uses [Solas Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/49004) by default.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/do-not-go-gentle)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements



Space required: Approx 188GB (63 GB of downloads included)

## Installation

Installing DNGG is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing DNGG, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. You also need to start the games to the main menu in order to download all the creations.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing DNGG

Downloading and installing DNGG can take a while depending on your internet connection and computer. To install DNGG, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Make sure the `show unofficial lists` checkbox is ticked
![UnofficialListHelp](https://github.com/chri3i/Ruvaak-Readme/blob/main/.github/UnofficialListHelp.png)
3. Press the download button on DNGG and wait for it to download.
4. Set the installation folder to be somewhere like `C:\DNGG`. **Do not install it to your desktop or downloads folder.**
5. The download location does not need to be on a SSD but it makes installing a bit faster
6. Press the play button to begin.
7. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
8. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
	- Make sure that you have downloaded **all** of the creation club content. **THIS LIST WILL NOT RUN WITHOUT IT!**

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder

DNGG uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called `Game Root`. You don’t need to copy anything at all.

### ENB
DNGG is designed for use with an ENB and comes with [E.V.C. ENB]([https://www.nexusmods.com/skyrimspecialedition/mods/71743]), already activated and ready for use. The ENB has been custom tweaked for the list to match the intended look, feel and performance of the list. 

I have also included Heidel's Reshade, as I love the combined look with EVC ENB

If you wish to install your own ENB, however, an ENB manager is included. Simply put your new ENB into a seperate folder in `DNGG\Tools\ENB Organizer\Games\SkyrimSE\Presets`.

#### Using ENB Manager

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big `Run` button next to it. Run the program named `Pick Your ENB` from Mod Organizer 2.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%201.png?raw=true)

If the image below comes up, simply press OK. It is nothing to be concerned about.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/Ignore%20Warning.png?raw=true)

Navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%203.png?raw=true)

Activate the ENB you wish to use by pressing the slider. To deactivate it, simply press the slider.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%205.png)

For adding your own presets and more details, take a look at [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) for more information.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### In-Game MCM options

DNGG has no MCM options required, since MCM recorder will run automatically. However, please test out the different smoothcam presets available and feel free to tinker any settings in the MCM menu.

### Starting the Game

By default, DNGG uses [Optional Quick Start](https://www.nexusmods.com/skyrimspecialedition/mods/63953).
I suggest skipping the intro when prompted, unless by some magic this is your first time playing Skyrim. 
	
## Adding mods to DNGG

I know you may want to add some extra mods on top of this. I also know I will not stop you from doing so; therefore, I have to say that I can only help you to the fullest of my ability if you _have not_ added any mods. ENBs, racemenu presets, and cbbe bodyslide presets are an exception to this rule. 

As a suggestion: _DO NOT_ put any additional mods with plugins below the paper maps, but preferably they should go above DynDOLOD.esp.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

Placehoder for your Readme.

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

#### ENB

DNGG ships with an ENB and Reshade setup that is configured to match the look of the list. If you wish to make some changes though, here are a few common tweaks. I recommend opening the console before doing edits.

##### Removing the letterbox (in general as the default ENB doesn't have that effect enabled)

1. Press [Shift+Enter] to open the ENB menu.
2. In the tab called Shader Parameters, select the `ENBPOSTPASS.FX` section. It will open once you click on it.
3. Scroll down until you see letterbox and untick it.
4. Press the save configuration button.
5. Press [Shift+Enter] to return to the game.

##### Turning off settings for FPS

If you are struggling for frames but want the colour correction and realism, turn off the following items.

- DetailedShadows
- ComplexFireLights
- ComplexParticleLights – Disable Big Range
- Reflection
- Complex Grass Collision
- Complex Grass

If you really cannot handle the ENB, uncheck `useEffect`. Note that this will make the list look much worse and it's not intended to be played like that.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team for helping me learn so much about modding and being so kind.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## Contact

Whilst I am available primarily on [my server](https://discord.gg/DffHKcszfg), please check the [issues](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.

You are welcome to [contribute](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Changelog.md) before you do.

## The Animonculory Team
- Althro - Leader & Head of Development
- Styyx - Senior Management Team & Dev Team
- Chef/Para0x - Senior Management Team & Dev Team
- The Spaniard -Senior Management Team & Documentation
- Annakins - Dev Team, Testing, Graphics & Documentation
- Astro - Dev Team & Testing
- DestinySlayer - Dev Team & Community Engagement
