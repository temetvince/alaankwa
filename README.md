# Alaankwa
* To download, go to the latest release and click 'Source code (zip)': https://github.com/temetvince/x3ap-lu/releases/
* 'Alaankwa' means 'star' in the Miami-Peoria language (Myaamia)

## Discord
* https://discord.gg/S587CRb

## Credits
* Special thanks to Joubarbe for making Mayhem. You can show your support by buying Joubarbe a coffee:
    * https://www.buymeacoffee.com/Joubarbe
* Also thanks to Sepa for graciously allowing me to redistribute his SWLU Mothership Mod

## Installation
### Downloads
* No-Steam Exe: https://www.egosoft.com/download/x3ap/bonus_en.php
* ReShade: https://reshade.me/
* Alaankwa: https://github.com/temetvince/x3ap-lu/releases
* LU: http://litcube.xtimelines.net/wiki/index.php/Download
* SWLU: https://www.moddb.com/mods/star-wars-lu-swlu/downloads
* GiC: https://www.moddb.com/mods/star-wars-lu-swlu/addons
* M3: https://www.moddb.com/mods/mayhem/downloads
* SWM3: https://www.moddb.com/games/star-wars-mayhem-3/downloads

### Instructions
1. Install Litcube's Universe
2. Optionally Install SWLU or M3
    * (SWLU) Star Wars Litcube's Universe
    * (M3) Mayhem 3
3. Optionally install GiC or SWM3
    * (GiC) Galaxy in Chaos - Requires SWLU
    * (SWM3) Star Wars Mayhem 3 - Requires M3
4. Install all other desired mods besides Alaankwa
5. Optionally install ReShade
6. Install Alaankwa
7. Install Alaankwa Patch if playing SWLU, GIC, M3, or SWM3
8. If you don't like the new font, delete the 'f' folder in your 'x3 terran conflict' root install directory

## Features
### General
* SHIP COMPUTER UPGRADES
    * New commands for the Ship Command Menu.
        * Manage Mothership
            * This command allows you to manage a Mothership. (Feature: Sepa's Mothership)
        * Manage Wares
            * This command allows you to manage the wares of a Mothership.
        * Map Gates
            * This command maps the gates in its current sector.
        * Self Destruct
            * This command tells the ship to self destruct.
* FRESH HOTKEYS, GET YOUR HOTKEYS
    * Decide which hotkeys are configurable in the Hotkeys Menu.
        * Blueprint Data Scanner 
            * This hotkey activates the Blueprint Data Scanner.
        * Joubarbe's Satellite Monitoring
            * This hotkey activates the Satellite Monitoring Menu respecting all player property, not just satellites.
        * All of Time
            * CHEAT: This hotkey saves your point in time to the next slot even if you don't have Salvage Insurance.
        * All of Space
            * CHEAT: This hotkey adds satellites to all sectors with jumpgates which don't already have one.
        * Phanon Industrial Espionage
            * This hotkey activates the Phanon Debug Menu, which shows detailed Phanon corp information.
* IMPROVED PILOTING
    * Ships automatically orient "upright" in the game like they do in the movies.
        * Overachiever
            * Improved Piloting applies to the playership
* STANDARDIZED FLEET OPERATIONS
    * Escorts will attempt to follow at reasonable speeds instead of flying all over the place.
* SEPA'S MOTHERSHIP
    * Motherships are mobile factories which can produce lasers, missiles, shields, and ships (must be able to dock on the Mothership).
        * Alaankwa Corsairs
            * A unique gamestart which focuses on unlocking blueprints by scanning ships in order to build them instead of buying/selling them.
        * Assembly Lines
            * The Ship Building Speed is a function of the population where the population is the max marines a ship can hold multiplied by the Assembly Lines.
        * Research and Development Budget
            * The number of data scans per type required to get the cheapest blueprint for production.
        * Shield Expertise
            * The maximum shield percentage of the target while using the data scanner.
* SATELLITE MONITORING PLUS
    * Satellite Monitoring respects all player property, not just satellites.
* UNDER NEW MANAGEMENT (PHANON)
    * Enables various changes which should help Phanon corporations be more competitive.
        * Corporate Bailouts
            * Corporate Bailouts keep Phanon corps afloat if their balance sheet goes negative.
        * Backroom Deals
            * Management cuts backroom deals to lower ship manufacturing costs.
        * Seedy Investors
            * Management isn't afraid to finance cash from less... reputable sources.
        * Well Connected Leadership
            * Well Connected Leadership commands a premium in salaries.
* AND MORE
    * An optional Graphics Improvement mod utilizing ReShade is included
        * You can take before/after screenshots that save to your root install folder with the PrintScrn button on your keyboard. To access the options in game, press [SHIFT]+[~] (or [SHIFT]+[`])
    * A new game font, Fantasque Sans Mono
        * https://github.com/belluzj/fantasque-sans
    * Debugging scripts for development
        * Can take in any text decodable object, say an array of tables, and output it in game to the user
        * Call the script like this: $debug.return = [NULL] -> call script 'tv.debug': param.debug=$Unknown param.trackingaim=$ShipOrStation
            * $param.debug is the message or object to debug. Can be simple like a ship name or complex like an array of tables
            * $param.trackingaim is optional. If provided, then the debug script will only run if that entity is the player's tracking aim in game

### M3/SWM3 specific
* NAVIGATION COMPUTER MK II (Disabled by Default)
    * Allows Workers to use jump beacons during their job search
    * Significant performance impact to Worker job calculation speed
        * Don't use with more than 10-20 jump beacons
* Outposts show themselves as a candidate for export or import jobs
    * This is helpful for making generic templates that include the sanctuary where you are creating the template
* Fixed the Outpost Client Threshold not being saved when making a Jobs Preset
* Fixed the homebase being cleared in your ship when using the Personal Teleportation Device
* An optional settings t-file for new players is included, disabled by default
    * These settings are the ones recommended by Darth Fiscus here: https://www.youtube.com/watch?v=kV-aS0swpfY&t=13s

## Links
* temetvince Youtube Playlists (X3 Mod Install Videos):
	* https://www.youtube.com/channel/UCw7tARIJee8gd1OpeSjAEMw/playlists
* temetvince Egosoft Forums:
    * Alaankwa: https://forum.egosoft.com/viewtopic.php?f=94&t=441825
* Star Wars Mayhem 2 ModDB:
    * https://www.moddb.com/mods/star-wars-mayhem-2
* Star Wars Mayhem 3 ModDB:
    * https://www.moddb.com/games/star-wars-mayhem-3
* X3 Mod Github Repositories:
    * Alaankwa: https://github.com/temetvince/x3ap-lu
    * Star Wars Mayhem 2: https://github.com/temetvince/x3ap-swm2
    * Star Wars Mayhem 3: https://github.com/temetvince/x3ap-swm3

