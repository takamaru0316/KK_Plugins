# KK_Plugins
Plugins for Koikatsu

## Installation
1. Install [BepInEx](https://github.com/BepInEx/BepInEx/releases) and [BepisPlugins](https://github.com/bbepis/BepisPlugins/releases)
2. Extract the plugin .zip file to your Koikatu folder

#### KK_CharaMakerLoadedSound - [Download](https://github.com/DeathWeasel1337/KK_Plugins/releases/download/v1/KK_CharaMakerLoadedSound.v1.0.zip)
Plays a sound when the Chara Maker finishes loading. Useful if you spend the load time alt-tabbed.

#### KK_StudioSceneLoadedSound - [Download](https://github.com/DeathWeasel1337/KK_Plugins/releases/download/v1/KK_StudioSceneLoadedSound.v1.0.zip)
Plays a sound when a Studio scene finishes loading or importing. Useful if you spend the load time for large scenes alt-tabbed.

#### KK_ForceHighPoly - ~[Download](https://github.com/DeathWeasel1337/KK_Plugins/releases/download/v1/KK_ForceHighPoly.v1.0.zip)~
Forces all characters to load in high poly mode, even in the school exploration mode.

Warning: May cause the game to lock up after special H scenes, use at your own risk.

#### KK_GUIDMigration v1.0.2 - [Download](https://github.com/DeathWeasel1337/KK_Plugins/releases/download/v5/KK_GUIDMigration.v1.0.2.zip)
Migrates your character cards in cases where a mod's GUID or IDs changed so you don't have to manually reselect everything. Will not attempt migration if you have the old mod but not the new.

Also attempts to fix cards saved with a blank GUID (Missing Mod []) by stripping the GUID and forcing sideloader to treat it as a hard mod. May not work 100%, so check your cards.

<details><summary>Configuration</summary>
  
Comes preconfigured with a whole bunch of migration info. Unless I stopped maintaining it you shouldn't need to mess with this stuff.  
KK_GUIDMigration.csv is a comma separated file in the form Category,Old GUID,Old ID,New GUID,New ID.  
Category is the internal one used by sideloader, not the numeric category.  
When the category is * only GUID migration will be attempted and whatever you put for Old/New ID will be ignored. Use only in cases where a GUID changed and the IDs stay the same.
</details>

#### KK_CutsceneLockupFix - [Download](https://github.com/DeathWeasel1337/KK_Plugins/releases/download/v2/KK_CutsceneLockupFix.v1.0.zip)
Adds some extra error handling to the game so certain hair mods wont lock up the whole game when they appear in a cutscene.

#### KK_ReloadCharaListOnChange v1.1 - [Download](https://github.com/DeathWeasel1337/KK_Plugins/releases/download/v4/KK_ReloadCharaListOnChange.v1.1.zip)
Reloads the list of characters and coordinates in the character maker when any card is added or removed from the folders. Supports adding and removing large numbers of cards at once.


<details><summary>Change Log</summary>
  
v1.1 Fix for new coordinates saved from within the game not handled correctly.
</details>

#### KK_InvisibleBody v1.0 - [Download](https://github.com/DeathWeasel1337/KK_Plugins/releases/download/v6/KK_InvisibleBody.v1.0.zip)
Select characters in the Studio workspace and press numpad+ (configurable) to toggle them between invisible and visible. Any worn clothes or accessories and any attached studio items will remain visible. Invisible state saves and loads with the scene. Can also be used to make girls invisible in H scenes but cannot be disabled except by exiting the scene.