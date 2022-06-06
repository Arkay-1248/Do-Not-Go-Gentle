# Adding mods to AVO

## Disclaimer

No modifications are supported as we cannot track down what everyone has done. If you have modified your list, you void your support and bug reporting.

## Things to know before modifying

AVO uses **Skyrim version 1.6.xx**. This means that **you need to use plugins that are made for Skyrim version 1.6.xx**. If your desired plugin does not exist for 1.6.xx (commonly referred to as AE) then you cannot use it.

AVO is method patched which means that you can, within reason, remove or change near enough anything. The only things that are not method patches are the generated outputs. These **will need to be regenerated** depending on what you change. More details are given in the relavant sections.

## Making Modifications

You may have seen us say "the left should match the right" when it comes to modlists, but what does this actually mean?

What it essentially means is that your mod order on the left hand side of MO2 matches the plugin order on the right. For example, USMP is designed to load after USSEP and on the right hand plugin view side will load like that. Therefore, we should place the USMP mod on the left hand below USSEP in priority. Whatever loads lower in priority (higher number) will be what is loaded in the game.

### General modifications

Move every addition you make **above** the Synthesis and DynDOLOD esps.

Mods such as armors and weapons will not cause any issues, however make sure that any armors you use have bodyslide files for CBBE. You will need to rebuild the bodyslide data if you wish to have consistency between your newly added and the existing armors. The preset used is the Amazonia preset, however you can change that to whichever one you wish to use.

For mods that include SKSE Plugins, **You need to use plugins that are made for Skyrim version 1.6.xx**. This is mandatory and if your desired plugin does not exist for 1.6.xx (commonly refered as AE), then you can't use it.

### Mesh/Texture replacers

This is where things can get a bit complicated. Depending on what your mesh/texture does, depends on what action you will need to take. Mesh/texture replacer mods tend to fall into three categories: worldspace, non worldspace and NPC replacers. 

#### Non Worldspace meshes/textures

These are mods that change things relating to: 
- Armors
- Weapons
- Interiors
- Food

Simply position these in the correct section as indicated on the left hand side. If there are any esp's present, move them to the correct position and resolve any conflicts that arise in xEdit. Any new armors you add will require bodyslide files for CBBE. You will need to rebuild the bodyslide data if you wish to have consistency between your newly added and the existing armors. The preset used is the Amazonia preset, however you can change that to whichever one you wish to use.

**Note**: Make sure that the normal maps match for the texture/mesh you are using. If they do not, you will see some weird looking things.

#### Worldspace mesh/texture replacers

These are mods that change things relating to
- Landscape
- Trees
- Architecture incl: Cities, towns and villages
- Mountains

These are more involved as you will need to regenerate the LOD files to ensure there is consistency across the worldspace. After positioning these in the correct section, please follow [this guide](https://github.com/The-Animonculory/Modding-Resources/blob/main/DynDOLOD.md) for regenerating the LOD files.

#### NPC replacers

These are mods that change things relating to:
- NPC's
- Facedata

As with worldspace mesh/texture replacers, these are a bit more involved and you will need to either regenerate all of the facegen or re-install certain mods to bring back the original facegen. Please follow [this guide](https://github.com/The-Animonculory/Modding-Resources/blob/main/Regenerating%20Faces%20in%20the%20Creation%20Kit.md) on how to regenerate facegen.
