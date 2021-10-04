# temetvince's Star Wars Litcube's Universe mods
To download, go to the latest release and click 'Source code (zip)': https://github.com/temetvince/lu-mods/releases/

## Links
* Egosoft Forum: https://forum.egosoft.com/viewtopic.php?f=94&t=441825
* Discord: https://discord.gg/S587CRb

## Important
* If you notice slowdowns, disable Improved Escort Behavior in 'x3 terran conflict/addon/t/9979-L044.xml'
* You MUST read the Installation section or your install probably won't work. I've kept it brief, you can ignore literally every thing else in this document if you desire.

## !!! Installation !!!
If you don't want to use Reshade and want to skip the Graphics Improvement mod functionality, skip to step 5.
1. Download and install ReShade
    * https://reshade.me/
2. When asked for the game, browse and select X3AP.exe in your x3 install folder
3. The game uses Direct3D 9
4. When asked, install all the shaders. Everything. All of them
5. Copy this mods 'x3 terran conflict' folder into your game's 'x3 terran conflict' folder. When asked, overwrite everything
6. If you're playing Star Wars LU, copy '!!!SWLU!!!/addon' to your game's 'x3 terran conflict' folder
7. If you're playing Galaxy in Chaos, copy '!!!GiC!!!/addon' to your game's 'x3 terran conflict' folder
8. If you want to use the optional font, then go to your game's 'x3 terran conflict' folder. Rename the folder 'RenameMeTof' to 'f'. Notice the LicenseAndCopyright file for your information 

## Features
* All ships orient themselves upright with respect to "up"
* Improved escort behavior
* A new UNFINISHED (Will break!) start for SWLU/GiC! 'Alaankwa' which means 'star' in the Miami-Peoria language, Myaamia.
You:
    * Cannot buy new ships (used ships are still available)
    * Cannot sell ships
    * Start in a TL with a miner, trade ships, and explorer ships and blueprints
    * Produce ships by using Sepa's Mothership Mod (included)
        * Found under the Special Commands menu
        * Works on any Carrier with the Carrier Command Software
    * Set the Data Scanner hotkey so you can scan ships with low shields to unlock their blueprints
    * Can still claim bailed ships
    * Use Piracy as an alternative to claiming ships
* Added a Map Gates command that tells a ship to map the gates in its current sector
* Joubarbe's Satellite Monitoring (v1.8 Included): Now considers player owned ships as satellites
    * https://forum.egosoft.com/viewtopic.php?t=380611
* Phanon investors step in to keep Phanon corps afloat if their balance goes negative
* Sepa's Mothership Mod (V2 Included):
    * Please see 'READEME_SEPAS_MOTHERSHIP_MOD.md'
    * Special thanks to Joubarbe and Sepa. You can buy Joubarbe a coffee to show support here:
        * (https://www.buymeacoffee.com/Joubarbe)
    * Applies to all carriers now, not just M7+
    * Population multiplier (ship building speed) increased by 4
    * Population multiplier can be set in 'x3 terran conflict/addon/t/9979-L044.xml'
    * Carriers can build any type of ship they can dock now, not just fighters
    * Ships can be built at any Mothership given they can dock in the carrier, and they have been either:
        * Scanned with the Data Scanner
        * Recycled in any Mothership
* Cheat: Saving with the hotkey no longer requires Salvage Insurance, removes the confirmation prompt to save, and removes the awful sound when saving to Slot 10
* Cheat: Enables Phanon Spy in the Player Console
* Cheat: A script called 'temetvince.Cheat.AddSats' that adds sats to all connected sectors which don't already have satellites
* Debug scripts. See Development Features below
* LU Stock Exchange pageid fix (theoretically)
* An optional Graphics Improvement mod utilizing ReShade is included
* An optional font change is included, disabled by default. It is Fantasque Sans Mono, you can find the original here:
    * https://github.com/belluzj/fantasque-sans 

## Graphics Improvement Mod
You can take before/after screenshots that save to your root install folder with the PrintScrn button on your keyboard. To access the options in game, press [SHIFT]+[~] (or [SHIFT]+[`])

## Settings
Some settings can be changed in the '9979-L044.xml' file located in the 'x3 terran conflict/addon/t/' directory

## Development Features
* Debug scripts for development. It can take in any text decodable object, say an array of tables, and output it in game to the user
* You can call this script like this: $debug.return = [NULL] -> call script 'temetvince.Debug': debug=$Unknown trackingAim=$ShipOrStation
* $debug is the message or object to debug. Can be simple like a ship name or complex like an array of tables
* $trackingAim is optional. If provided, then the debug script will only run if that entity is the player's tracking aim in game
