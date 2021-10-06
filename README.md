# temetvince's mods for X3AP - Litcube's Universe

To download, go to the latest release and click 'Source code (zip)': https://github.com/temetvince/x3ap-lu/releases/

## Discord
* https://discord.gg/S587CRb

## Credits
* Special thanks to Joubarbe for making Mayhem. You can show your support by buying Joubarbe a coffee:
    * https://www.buymeacoffee.com/Joubarbe
* Also thanks to Sepa for graciously allowing me to redistribute his SWLU Mothership Mod

## Installation
### Instructions
* https://www.youtube.com/playlist?list=PLl4mHpHKbi1nu40jru_6Hf8jumxxtS-VO
### Downloads
* No-Steam Exe: https://www.egosoft.com/download/x3ap/bonus_en.php
* ReShade: https://reshade.me/
* Litcube's Universe: http://litcube.xtimelines.net/wiki/index.php/Main_Page
* temetvince's LU mods: https://github.com/temetvince/x3ap-lu/releases/

## Graphics Improvement Mod
You can take before/after screenshots that save to your root install folder with the PrintScrn button on your keyboard. To access the options in game, press [SHIFT]+[~] (or [SHIFT]+[`])

## Features
### General LU
* All ships orient themselves upright with respect to "up"
    * An optional setting in 'addon/9979-L044.xml' allows you to turn on the orientation feature for your player ship (off by default)
* Improved escort behavior
* Added a Map Gates command that tells a ship to map the gates in its current sector
* Joubarbe's Ship Destruct is included, found in any ship's Additional Commands Menu
* Joubarbe's Satellite Monitoring (v1.8 Included): Now considers player owned ships as satellites
    * https://forum.egosoft.com/viewtopic.php?t=380611
* LU Stock Exchange pageid fix (theoretically)
* Phanon:
    * Investors step in to keep Phanon corps afloat if their balance goes negative
    * Phanon gets cheaper ships and more money
    * Phanon starting cash, bonus salary, and ship cost divisor modifiable in 'addon/8384-L044.xml'
* Cheat: Enables Phanon Spy in the Player Console
* Cheat: Saving with the hotkey no longer requires Salvage Insurance, removes the confirmation prompt to save, and removes the awful sound when saving to Slot 10
* Cheat: A script called 'temetvince.Cheat.AddSats' that adds sats to all connected sectors which don't already have satellites
* Debug scripts. See Development Features below
* An optional Graphics Improvement mod utilizing ReShade is included
* An optional font change is included, disabled by default. It is Fantasque Sans Mono, you can find the original here:
    * https://github.com/belluzj/fantasque-sans

### SWLU/GiC specific (Requires temetvince's SWLU or GiC modpacks)
* Phanon is even more powerful due to decreased ship costs
* A new UNFINISHED (Will break!) start!
    * 'Alaankwa' which means 'star' in the Miami-Peoria language (Myaamia)
    * You:
        * Cannot buy new ships (used ships are still available)
        * Cannot sell ships
        * Start in a TL with a miner, trade ships, and explorer ships and blueprints
        * Produce ships by using Sepa's Mothership Mod (included)
            * Found under the Special Commands menu
            * Works on any Carrier with the Carrier Command Software
        * Set the Data Scanner hotkey so you can scan ships with low shields to unlock their blueprints
        * Can still claim bailed ships
        * Use Piracy as an alternative to claiming ships
* Sepa's Mothership Mod:
    * It allows you to have the following on any Carrier class ship that has Carrier Command Software:
	    * Hangar with upgrade and repair functionality
	    * Recycle functionality
	    * Production functionality (missiles, shields, lasers, fighter ships)
    * You can only produce ships that you have previously recycled or data scanned
    * You can access the Mothership menu in ship console, under 'Special commands'
    * Applies to all carriers now, not just M7+
    * Population multiplier (ship building speed) increased by 4 from version 2
    * Population multiplier can be set in 'x3 terran conflict/addon/t/9979-L044.xml'
    * Carriers can build any type of ship they can dock now, not just fighters
    * Ships can be built at any Mothership given they can dock in the carrier, and they have been either:
        * Scanned with the Data Scanner
        * Recycled in any Mothership

## Development Features
* Debug scripts for development. It can take in any text decodable object, say an array of tables, and output it in game to the user
* You can call this script like this: $debug.return = [NULL] -> call script 'temetvince.Debug': debug=$Unknown trackingAim=$ShipOrStation
* $debug is the message or object to debug. Can be simple like a ship name or complex like an array of tables
* $trackingAim is optional. If provided, then the debug script will only run if that entity is the player's tracking aim in game

## Links
* temetvince Youtube Playlists (X3 Mod Install Videos):
	* https://www.youtube.com/channel/UCw7tARIJee8gd1OpeSjAEMw/playlists
* temetvince X3 Mod Github Repositories:
    * Litcube's Universe: https://github.com/temetvince/x3ap-lu
    * Star Wars LU: https://github.com/temetvince/x3ap-swlu
    * SWLU Galaxy in Chaos: https://github.com/temetvince/x3ap-gic
    * Mayhem 3: https://github.com/temetvince/x3ap-m3
    * Star Wars Mayhem 2: https://github.com/temetvince/x3ap-swm2
    * Star Wars Mayhem 3: https://github.com/temetvince/x3ap-swm3
* temetvince Egosoft Forums:
    * Litcube's Universe: https://forum.egosoft.com/viewtopic.php?f=94&t=441825
    * Mayhem 3: https://forum.egosoft.com/viewtopic.php?f=94&t=441824
* Star Wars Mayhem 2 ModDB:
    * https://www.moddb.com/mods/star-wars-mayhem-2
* Star Wars Mayhem 3 ModDB:
    * https://www.moddb.com/games/star-wars-mayhem-3
