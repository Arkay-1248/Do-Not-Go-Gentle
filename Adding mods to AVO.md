# Adding mods to AVO

## Disclaimer

No modifications are supported as we cannot track down what everyone has done. If you have modified your list, you void your support and bug reporting.

## Things to Know Before Modifying

AVO uses **Skyrim version 1.6.xx**. This means that **you need to use plugins that are made for Skyrim version 1.6.xx**. If your desired plugin does not exist for 1.6.xx (commonly referred to as AE) then you cannot use it.

AVO is method patched which means that you can, within reason, remove or change near enough anything. The only things that are not method patches are the generated outputs. These **will need to be regenerated** depending on what you change. More details are given in the relavant sections.

## Before You Begin

You may have seen us say "the left should match the right" when it comes to modlists, but what does this actually mean?

What it essentially means is that your mod order on the left hand side of MO2 matches the plugin order on the right. For example, USMP is designed to load after USSEP and on the right hand plugin view side will load like that. Therefore, we should place the USMP mod on the left hand below USSEP in priority. Whatever loads lower in priority (higher number) will be what is loaded in the game.

### Bash & Smash

**NEVER** attempt to create a Bash or Smashed patch on AVO. You should **ONLY** use Wrye Bash to swap masters on a plugin or use the mod-checker and **NEVER** attempt to use Smash oon this list. Bash and smash patches are, for Skyrim Special/Anniversary Edition, broken and **SHOULD NOT** be used. You can do almost everything they do via a custom patch in xEdit.

Neither tool is included with the list as they are not required. If you do wish to add Bash, **you will need to reroute the managed game to your vanilla install**. If you do not, you will break the load order.

### LOOT

As of version 2 of AVO, LOOT is included with the list alongside a custom `userdata.yaml` file. The aforementioned file applies custom groups to the plugins in AVO to ensure that the existing load order is preserved. In order to copy the file across, please follow [this guide](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Make%20AVO%20work%20with%20LOOT.md) which covers getting the `.yaml` file installed in the correct place.

### Synthesis

If you add any mod with a plugin, it's recommended to re-run Synthesis. The patchers are split into 2 groups and are as follows:

__Synthesis__
- enblightpatcher
- SynFloraFix
- khajiitearsshow
- nodragonlods

__ELE-SynthMasterPatch__
- ELE_Patcher

No custom data is used in these patches so you can just simply run them.

**WARNING!**

The lighting mods used in both AVO & AVO-AE have a master patch which is required for lighting to be consistant in all areas. If you are not changing the lighting mod or any areas that modify cells, **DO NOT** re-run the ELE patcher. If you have to re-run the patcher, make a backup of the original patch and then compare your new one to the one that came with the list in xEdit. You will **very likely** need to repatch Water4ENB records as the Synthesis patcher **DOES NOT** correctly forward them.

## Adding Mods

Move every addition you make **above** the Synthesis and DynDOLOD esps.

Mods such as armors and weapons will not cause any issues. **However** make sure that any armors you use have bodyslide files for CBBE. You will need to rebuild the bodyslide data if you wish to have consistency between your newly added armors and the existing armors. The preset used is the Amazonia preset, **however** you can change that to whichever one you wish to use.

For mods that include SKSE Plugins, **you need to use plugins that are made for Skyrim version 1.6.xx**. This is mandatory and if your desired plugin does not exist for 1.6.xx (commonly refered as AE), then you can't use it.

### Mesh/Texture Replacers

This is where things can get a bit complicated. What action you'll need to take depends on what your mesh/texture does. Mesh/texture replacer mods tend to fall into three categories: worldspace, non worldspace and NPC replacers. 

#### Non Worldspace Meshes/Textures

These are mods that change things relating to: 
- Armors
- Weapons
- Interiors
- Food

Simply position these in the correct section as indicated on the left hand side. If there are any esp's present, move them to the correct position and resolve any conflicts that arise in xEdit. Any new armors you add will require bodyslide files for CBBE.

**Note**: Make sure that the normal maps match for the texture/mesh you are using. If they do not, you will see some weird looking things.

#### Worldspace Mesh/Texture Replacers

These are mods that change things relating to
- Landscape
- Trees
- Architecture incl: Cities, towns and villages
- Mountains

These are more involved as you will need to regenerate the LOD files to ensure there is consistency across the worldspace. After positioning these in the correct section, please follow [this guide](https://github.com/The-Animonculory/Modding-Resources/blob/main/DynDOLOD.md) for regenerating the LOD files.

**NOTE**: Both AVO & AVO-AE use custom tree rules which can be found on the [Morekvior DynDOLOD Add-ON](https://www.nexusmods.com/skyrimspecialedition/mods/54141) page. It uses the `Optimal` settings with the Lod32 settings from ACMOS.

#### NPC Replacers

These are mods that change things relating to:
- NPC's
- Facedata

As of AVO 2.0, you no longer need to regenerate all of the facegen for newly added quest mods or have to contend with it. By default, AVO uses HMB II which has the option of assets to create new facegen. If you wish to do this, please follow [this guide](https://github.com/The-Animonculory/Modding-Resources/blob/main/Regenerating%20Faces%20in%20the%20Creation%20Kit.md) which details the process of doing so.
