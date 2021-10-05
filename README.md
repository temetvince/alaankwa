# temetvince's mods for X3AP - Litcube's Universe

To download, go to the latest release and click 'Source code (zip)': https://github.com/temetvince/x3ap-lu/releases/

## Links
* Discord: https://discord.gg/S587CRb
* X3LU Egosoft Forum: https://forum.egosoft.com/viewtopic.php?f=94&t=441825

## Important
* You MUST read the Installation section or your install probably won't work
* If you notice slowdowns, disable Improved Escort Behavior in 'x3 terran conflict/addon/t/9979-L044.xml'
* Some other settings can be changed in 'x3 terran conflict/addon/t/9979-L044.xml'

## Credits
* Special thanks to Joubarbe for making Mayhem. You can show your support by buying Joubarbe a coffee:
    * https://www.buymeacoffee.com/Joubarbe
* Also thanks to Sepa for graciously allowing me to redistribute his SWLU Mothership Mod

## !!! Installation !!!
1. Install 'X3: Albion Prelude' in Steam
1. Ensure the Bonus Pack is not installed in Steam by right clicking on 'X3: Albion Prelude -> Properties -> DLC'
1. Ensure Farnham's Legacy is not installed in Steam
1. Copy 'x3 terran conflict' out of your steam folder to somewhere else on your drive.
    * The steam folder is probably found at 'C:\Program Files (x86)\Steam\steamapps\common\x3 terran conflict'
    * The new, copied folder is now your 'game's x3 terran conflict' folder
1. Download the no-steam exe from Egosoft:
    * https://www.egosoft.com/download/x3ap/bonus_en.php
1. Copy the no-steam exe into your game's 'x3 terran conflict' folder
1. If you don't want to use Reshade and want to skip the Graphics Improvement mod functionality, skip to step 12
1. Download and install ReShade
    * https://reshade.me/
1. When asked for the game, browse and select X3AP.exe in your x3 install folder
1. The game uses Direct3D 9
1. When asked, install all the shaders. Everything. All of them
1. Download and install LU Base + Patch + Import/Export + Soundtrack:
    * http://litcube.xtimelines.net/wiki/index.php/Main_Page
1. Download the latest x3ap-lu release at:
    * https://github.com/temetvince/x3ap-lu/releases/
1. Copy (this) x3ap-lu's 'x3 terran conflict' folder into your game's 'x3 terran conflict' folder. When asked, overwrite everything
1. If you want to use the optional font, then go to your game's 'x3 terran conflict' folder. Rename the folder 'RenameMeTof' to 'f'. Notice the LicenseAndCopyright file for your information

## Graphics Improvement Mod
You can take before/after screenshots that save to your root install folder with the PrintScrn button on your keyboard. To access the options in game, press [SHIFT]+[~] (or [SHIFT]+[`])

## Features
* All ships orient themselves upright with respect to "up"
    * An optional setting in 'addon/9979-L044.xml' allows you to turn on the orientation feature for your player ship (off by default)
* Improved escort behavior
* Added a Map Gates command that tells a ship to map the gates in its current sector
* Joubarbe's Ship Destruct now included, found in any ship's Additional Commands Menu
* Joubarbe's Satellite Monitoring (v1.8 Included): Now considers player owned ships as satellites
    * https://forum.egosoft.com/viewtopic.php?t=380611
* LU Stock Exchange pageid fix (theoretically)
* Phanon investors step in to keep Phanon corps afloat if their balance goes negative
* Cheat: Enables Phanon Spy in the Player Console
* Cheat: Saving with the hotkey no longer requires Salvage Insurance, removes the confirmation prompt to save, and removes the awful sound when saving to Slot 10
* Cheat: A script called 'temetvince.Cheat.AddSats' that adds sats to all connected sectors which don't already have satellites
* Debug scripts. See Development Features below
* An optional Graphics Improvement mod utilizing ReShade is included
* An optional font change is included, disabled by default. It is Fantasque Sans Mono, you can find the original here:
    * https://github.com/belluzj/fantasque-sans

## Development Features
* Debug scripts for development. It can take in any text decodable object, say an array of tables, and output it in game to the user
* You can call this script like this: $debug.return = [NULL] -> call script 'temetvince.Debug': debug=$Unknown trackingAim=$ShipOrStation
* $debug is the message or object to debug. Can be simple like a ship name or complex like an array of tables
* $trackingAim is optional. If provided, then the debug script will only run if that entity is the player's tracking aim in game
