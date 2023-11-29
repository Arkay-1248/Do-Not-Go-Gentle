# Do Not Go Gentle

# This Skyrim modlist requires the AE content upgrade to be purchased and installed

Wabbajack Modlist Installer by [Abandoned_by_Arkay](https://www.patreon.com/Abandoned_by_Arkay) (Arkay-1248)

<table stlyle="border: none;">
<tr>
<td><img src="https://github.com/The-Animonculory/AVO-NG/blob/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>
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
    - [Community Shaders](#community-shaders)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
    - [Updating the modlist](#updating-the-modlist)
    - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble

**NOTE**: Do Not Go Gentle **REQUIRES** the paid AE update to Skyrim.

Do Not Go Gentle is designed as Requiem modlist with Bruma, Wyrmstooth, VIGILANT, and lots of other additions to extend the life of your character playthrough. I did not build this to be a painful list to play, but Requiem does make you plan out your actions more than vanilla Skyrim. I find my build to be a reasonable compromise between difficulty and enjoyment, and maybe you will too. [Here](https://youtu.be/fP1B2WA8GmQ) is a video of me playing the game to give you an idea of what it's like.

The full modlist can be viewed [here](https://loadorderlibrary.com/lists/do-not-go-gentle)

Notable Mods: Alternate Start- LAL, Precision, TDM, One Click Power Attack, Pit Fighter, VIGILANT, Bruma, Wyrmstooth, Leaps of Faith, College of Winterhold Quest Expansion, Pilgrim, Honed Metal, More Carriages, and Wait Carriage in Towns(adds an option to wait for a carriage at any inn not inside a walled city), and Just Sleep(Sleep increases carry weight while sleep deprivation decreases carry weight). I cannot include them all here, so check the link above 

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

My Specs: 
- Processor:	i9-12900k
- GPU: 		3090
- Ram: 		32GB
- Storage:	2TB m.2 nvme
- Pagefile:	40GB
- ShaderCache:	10GB

I tend to test in 4k, and play in 2k with these specs. In 4k, I rarely see it drop below 55fps except in some spots around Riverwood, Falkreath, or Riften. In 2k, it typically stays above 100fps.

As you might see, I have a problem suggesting minimum requirements because of my higher end computer. However, if you have run Serenity, AVO, or a list similar, I don't think you should have a problem with this. 

Recommended for 1080p:
- Processor:	8 Core/16 Thread CPU. i9-9900k or better.
- GPU: 		6-8GB or more
- Ram: 		16+GB
- Storage: 	SSD or m.2 nvme
- [Pagefile](https://github.com/Arkay-1248/Do-Not-Go-Gentle/blob/main/Pagefile.md):	20-40GB
- [ShaderCache](https://github.com/Arkay-1248/Do-Not-Go-Gentle/blob/main/.github/NVIDIA-Driver.png):	This is only available to those on Nvidia, but I recommend setting it to 10GB if you do have nVidia.

The last bit of advice is that it's lighter than [Elysium](https://github.com/TitansBane/Elysium-Remastered) or [Aldrnari](https://github.com/SovnSkyrim/Aldrnari) which are notable high ended lists.

Space required: Around 400GB; to see a more accurate size; use the card in the Wabbajack Gallery. 

## Installation

Installing DNGG is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing DNGG, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. Install the [Skyrim Special Edition Creation Kit from Steam](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/).
7. You also need to start the games to the main menu in order to download all the creations.

# Step 3 and 4 are only necessary if you modded the game without 'stock game' and cleaned the master files

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, in your documents, on your desktop, or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing DNGG

Downloading and installing DNGG can take a while depending on your internet connection and computer. To install DNGG, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on DNGG and wait for it to download. Then hit the play button.
3. Set the installation folder to be somewhere like `C:\DNGG`. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
	- Make sure that you have downloaded **all** of the creation club content. **THIS LIST WILL NOT RUN WITHOUT IT!**
 	- Commonly failing downloads can probably be found linked in the pins of the #dngg-install-help channel in the discord server linked in the [Contact](#contact) section.
    	- Commonly failing mods:
       		- [Lord Nicholas Armor:](https://drive.google.com/file/d/1cL7BC2Nrvi2HTVv-ppZzyOkcszD5g7gA/edit)
           	- [Slow Sprint Equip Bug Fix:](https://drive.google.com/file/d/1kG_pRhKGyl1uESaj60fsXD9dWmaXz-Z2/edit)

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
DNGG is designed for use with an ENB and comes with [Amon ENB Obsidian](https://www.nexusmods.com/skyrimspecialedition/mods/1089), already activated and ready for use. There are two other enbs included with the list, PiCho and Rudy. Feel free to switch between them.

If you wish to install your own ENB, simply put your new ENB into a new mod folder and put the enb files in `DNGG\mods\(name of enb)\Root\(enbfiles)`.

## Community Shaders

If you would prefer to have more performance, or you simply want to use Community Shaders instead of ENB, simply disable the 'ENB Binaries' mod and the enb preset that is enabled. You can choose to enable Amethyst Reshade and its related Kreate preset, if you want, but it is not necessary for Community Shaders to function. Amethyst is the best looking reshade for Community Shaders that I can find so far. It does'nt look quite as good as a good enb, but it performs better and looks pretty great. Try it out if you need more fps than you're getting with ENB

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

**_Before you launch_**, make sure check out the optionals tab in mo2. It should look something similar to this. ![image](https://github.com/Arkay-1248/Do-Not-Go-Gentle/blob/main/.github/Screenshot_20230214_034255.png) Feel free to enable or disable any of the mods in this section, but maybe read up on them before you do so. 

- Quick description of some optional mods:
  - Optional Nude bodies: seems obvious, but both underwear.dll and New Gentleman.dll are both inside this optional mod. This means that, when you enable optional nudity, both genders will be nude, but will automatically get underwear distributed to them that can be removed if you so choose
  - Three enb presets and Amethyst Reshade can be disabled at any time. 
  - Survival Mode is now included with patches and Survival Mode Control Panel, however, it will be turned off by default. You can turn it on in the vanilla settings page if you would so like.

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### Controller Support?

Yes, just refer to the picture in this [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/88974) after enabling the related "8-Hotkey Controller Map for OCPA" mod in the Optional separator

### In-Game MCM options

DNGG has no MCM options required, since MCM Recorder will run automatically. However, please test out the different smoothcam presets available and feel free to tinker any settings in the MCM menu.

### Starting the Game

By default, DNGG uses [Alternate Start - Live Another Life](https://www.nexusmods.com/skyrimspecialedition/mods/272), but has several addons for spawn locations.

This mod will spawn you into an abandoned prison. After you finish customizing and naming your new character, you should wait about 30 seconds for the mcm recorder to finish and the message box to pop up.Then, **_You will see a message pop up to initialize Requiem._ Open your inventory and close it to do this before leaving the starting prison cell.** 

You can use the ["Choose your Destiny!"](https://www.nexusmods.com/skyrimspecialedition/mods/72410) scroll in your inventory to choose a loadout specific to that class style. You can also choose your birthsign from the start by using the power also in your powers list. You do not have to use these, but the option is there.

One more thing, Requiem gives you three perks to start out with. I would suggest taking one in light or heavy armor, if you plan to use it for your character. Requiem makes survival and enjoyment slightly dependent on taking perks in the skill you would like to use. For instance, wearing Heavy Armor without the first perk will drain your stamina, which could spell death, in the right situation. Light Armor will also drain your stamina while running, without the first perk. Weapons become much more effective with the first perk, and spells are almost impossible without the first perk in the related school. Again, you get three to start out with, and I feel that is reasonable.

Last thing, please change the vanilla controls to your liking, but remember One Click Power Attack's key is set to the "M3(Middle Mouse Key)" key by default. You need it to be able to power attack. 

Once you are ready to spawn in, choose whichever start you like from the shrine of Mara and good luck! Also, don't forget to get some sleep.
	
## Adding mods to DNGG

I know you may want to add some extra mods on top of this. I also know I will not stop you from doing so; therefore, I have to say that I can only help you to the fullest of my ability if you _have not_ added any mods. ENBs and racemenu presets are an exception to this rule. 

Weapons, armors, spells, followers, etc... might not be as easy to add as you might think. Just throwing in a random weapon/armor will probably get you killed. Adding followers will almost definitely underperform.

As a suggestion: _DO NOT_ put any additional mods with plugins below the paper maps, but preferably they should go above DynDOLOD.esp.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

Q: Screenshake in 3rd person? 

A: Check the Precision MCM. If that doesn't cut it for you, enable the mod to disable screenshake in the optional section.

Q: Can you add (insert player's favorite mod) into the list? 

A: Maybe, but probably not. If it's a cool weapon/armor, I might do it cause I'm a sucker for those, but otherwise, probably not.

Q: I ran into someone and everyone attacked! 

A: You were sprinting, huh? Don't be rude. Sprinting full speed into someone would hurt in real life. If you must know, there is an option to turn that feature off in the Requiem MCM.

Q: Where are my Ebony Vampires?? I want to die more!!

A: So about the Ebony Vamps, Vampire Collection does reduce the amount of Ebony Vamps while making the Dawnguard bosses stronger. They aren't gone. If you wanna check somewhere specific, go to Forebears Holdout. I looked at the record. There is one there. 

Q: How do I fast travel? 

A: You can fast travel using a combination of [More Carriages](https://www.nexusmods.com/skyrimspecialedition/mods/71135), [Wait Carriage in Towns](https://www.nexusmods.com/skyrimspecialedition/mods/35418), or using the travel packs from [Horizon Zero Dawn Fast Travel](https://www.nexusmods.com/skyrimspecialedition/mods/35793). You can craft the travel packs at a cooking pot or purchase them from any inn keeper, except the two inns in Bruma. There are also teleportation spells from two seperate schools of magic.

### Tweaking the Game Settings


#### ENB

DNGG ships with an ENB setup that is configured to match the look of the list. If you wish to make some changes though, here are a few common tweaks. 

- PiCho ENB and Rudy ENB are likely to perform better than Amon ENB.
- Amethyst Reshade and Kreate preset with ENB Binaries disabled is likely to perform better than PiCho, Rudy, or Amon ENBs, but is also likely to perform worse than *just* using Community Shaders.
- Community Shaders by itself will give the best performance compared to anything mentioned above, but you might notice some loss in visual fidelity.

##### Removing the letterbox

1. Press [End] to open the ENB menu.
2. In the tab called Shader Parameters, select the `ENBPOSTPASS.FX` section. It will open once you click on it.
3. Scroll down until you see letterbox and untick it.
4. Press the save configuration button.
5. Press [End] to return to the game.

##### Turning off ENB settings for FPS

If you are struggling for frames but want the colour correction and realism, turn off the following items.

- DetailedShadows
- ComplexParticleLights – Disable Big Range
- Reflection
- Complex Grass Collision
- Complex Grass
- Complex Parallax (must be disabled out of game from the enbseries.ini inside the Game Root folder and then you must clear the enbcache in that same folder)

If your computer cannot handle the ENB, the Page Down button will toggle the ENB while in game. Note that this will make the list look worse and it's not intended to be played like that.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Animonculory Team for helping me learn so much about modding and being so kind.
- Zelie(Sovn) for helping me with a few things and giving helpful advice.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## Contact

I am available primarily on the [Requiem Wabbajack server](https://discord.gg/JycmyqzZz7). PLEASE, DO NOT DM ME ON DISCORD; it is more helpful for others if your problem gets a solution that others can see.

You are welcome to [contribute](https://github.com/Arkay-1248/Do-Not-Go-Gentle/issues/new/choose) to the list, however please check the [changelog](https://github.com/Arkay-1248/Do-Not-Go-Gentle/blob/main/Changelog.md) before you do. Lastly, if you love my list, feel free to contribute to my [Patreon](https://www.patreon.com/Abandoned_by_Arkay). I may even end up playing the build of your choice.
