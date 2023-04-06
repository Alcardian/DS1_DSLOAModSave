# DSLOAModSave
A mod for Dungeon Siege 1. Find the mod on Nexusmods at https://www.nexusmods.com/dungeonsiege1/mods/156
## Short Description
Enable importing characters to your singleplayer save.

## Description
Mod based on "DSLOA Map Transfer Mod" found at https://www.siegetheday.org/?q=node/934  
This mod just makes it possible to import characters using DSLOAMod (the dev client with console access) & doesn't rebalance singleplayer into veteran or elite modes as "DSLOA Map Transfer Mod" does.

Importing a character or party in DSMOD or DSLOAMOD to a singleplayer game & saving can result in the game crashing every time you try to load it in the normal game client afterwards.  
Fixes the issue of saving in singleplayer while using DSLOAMod (DSMOD might work as well) & later trying to load that same save in the normal game client.  
This enables one to do things like importing a character from a multiplayer save or a party from another singleplayer save.

### Instructions assumptions:
* DSLOAMod is installed already & you can run it. See Siege Editor Tool Kit https://www.nexusmods.com/dungeonsiege1/mods/49
* You have a savefile or more that you want to import

### Instructions:
* Place the mod in your "Dungeon Siege 1\Resources" folder
* Startup DSLOAMod & load the singleplayer save
* Press '**~**' (left of '1' Key)
* Point cursor on an empty space that is flat. Imported party members appear on cursor
* Do your imports. Example "**PARTY ADD Alcardian.dsparty**" (see your save folder for what your saves are named).
* Press '**~**' to close console once done
* Save the game. I like to add "TEST" at the end of the save name to keep track of that save potentially having issues.
* Close down DSLOAMod & startup the normal game client. Load the save to make sure that you can load it correctly
* Save again in the normal client
* You can uninstall DSLOAModSave if you don't plan on importing anything else by removing it from the resources folder. Or you can leave it.

### DSLOAMod Console commands
**PARTY LOAD CHARACTERNAME.dsparty**
* Load replaces entire party
* Can load from singleplayer as well, .dssave instead of .dsparty

**PARTY ADD CHARACTERNAME.dsparty**
* Add adds onto your current party instead of overwriting it
