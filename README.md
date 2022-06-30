# Alaankwa
* To download, go to the latest release and click 'Source code (zip)': https://github.com/temetvince/x3ap-lu/releases/
* 'Alaankwa' means 'star' in the Miami-Peoria language (Myaamia)

## Discord
* https://discord.gg/S587CRb

## Credits
* Special thanks to Joubarbe for making Mayhem. You can show your support by buying Joubarbe a coffee:
    * https://www.buymeacoffee.com/Joubarbe
* Also thanks to Sepa for graciously allowing me to redistribute his Mothership mod

## Installation
### Downloads
* No-Steam Exe: https://www.egosoft.com/download/x3ap/bonus_en.php
* ReShade: https://reshade.me/
* Alaankwa: https://github.com/temetvince/x3ap-lu/releases
* LU: http://litcube.xtimelines.net/wiki/index.php/Download
* SWLU: https://www.moddb.com/mods/star-wars-lu-swlu/downloads
* GiC: https://www.moddb.com/mods/star-wars-lu-swlu/addons
* M3: https://www.moddb.com/mods/mayhem/downloads

### Instructions
1. Install Litcube's Universe
2. Optionally Install SWLU or M3
    * (SWLU) Star Wars Litcube's Universe
    * (M3) Mayhem 3
3. Optionally install GiC
    * (GiC) Galaxy in Chaos - Requires SWLU
4. Install all other desired mods besides Alaankwa
5. Optionally install ReShade
6. Install Alaankwa
7. Install Alaankwa Patch if playing SWLU, GIC, or M3
8. If you don't like the new font, delete the 'f' folder in your 'x3 terran conflict' root install directory

## Features
### General
* ROTATIONAL THRUSTERS
    * Class rotation variables have been increased by these amounts:
        * M1/M2/TL = 200%
        * M7 = 50%
        * M6 = 25%
        * M3 = 40%
        * M4 = 25%
        * TM/TP/TS = 10%
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
        * Satellite Monitoring Plus
            * This hotkey activates the Satellite Monitoring+ Menu respecting all player property, not just satellites.
        * Ship Compendium Plus
            * This hotkey activates the Ship Compendium+ Menu where ships are shown even if not yet discovered.
        * All of Time
            * CHEAT: This hotkey saves your point in time to the next slot even if you don't have Salvage Insurance.
        * All of Space
            * CHEAT: This hotkey adds satellites to all sectors with jumpgates which don't already have one.
        * Phanon Industrial Espionage
            * This hotkey activates the Phanon Debug Menu, which shows detailed Phanon corp information.
        * Joubarbe's Player Journal
            * This hotkey activates the Player Journal.
* IMPROVED PILOTING
    * Ships automatically orient "upright" in the game like they do in the movies.
        * Overachiever
            * Improved Piloting applies to the playership
* STANDARDIZED FLEET OPERATIONS
    * Escorts will attempt to follow at reasonable speeds instead of flying all over the place.
* TOP NOTCH RECRUITERS
    * All recruited Trade Mrk III Pilots are level 8 (enough to start Galaxy trading).
* TRADE EMBARGO
    * Removes all NPC ships docked at player stations which are not open to race traders.
* SEPA'S MOTHERSHIP
    * Motherships are mobile factories which can produce lasers, missiles, shields, and ships (must be able to dock on the Mothership).
        * Alaankwa Corsairs
            * A unique gamestart which focuses on unlocking blueprints by scanning ships in order to build them instead of buying/selling them.
        * Assembly Lines
            * The Ship Building Speed is a function of the population where the population is the max marines a ship can hold multiplied by the Assembly Lines.
        * Just in Time (JIT) Manufacturing
            * Allows full production speed even when producing more than one type of ware.
        * Research and Development Budget
            * The number of data scans per type required to get the cheapest blueprint for production.
        * Shield Expertise
            * The maximum shield percentage of the target while using the data scanner.
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
    * Updated LU Export/Import to support Alaankwa
    * An optional Graphics Improvement mod utilizing ReShade is included
        * You can take before/after screenshots that save to your root install folder with the PrintScrn button on your keyboard. To access the options in game, press [SHIFT]+[~] (or [SHIFT]+[`])
    * A new game font, Fantasque Sans Mono
        * https://github.com/belluzj/fantasque-sans
    * Quickshuttles notify the player when they have completed their task and have returned home.
    * Universe Traders proactively sell off unneeded wares in their cargo bay.
    * Player Space Suit has SETA, trading capabilies, video enchancement goggles, and a bioware scanner. (LU only)
    * The Player Headquarters, Equipment Docks, and Trading Stations are now available as Sources in the Dockware Manager.
    * Debugging scripts for development
        * Can take in any text decodable object, say an array of tables, and output it in game to the user
        * Call the script like this: $debug.return = [NULL] -> call script 'tv.debug': param.debug=$Unknown param.trackingaim=$ShipOrStation
            * $param.debug is the message or object to debug. Can be simple like a ship name or complex like an array of tables
            * $param.trackingaim is optional. If provided, then the debug script will only run if that entity is the player's tracking aim in game


### M3 specific
* NAVIGATION COMPUTER MK II
    * Allows Workers to use jump beacons during their job search
    * Significant performance impact to Worker job calculation speed
        * Don't use with more than 10-20 jump beacons
* SMUGGLING RUNS
    * Allows workers to use Pirate bases during their job search
    * Disabled by default
        * Enable for normal M3 behavior
* MINING DRONES
    * Player owned outposts build mining drones which collect minerals from miners in sector
* Outposts show themselves as a candidate for export or import jobs
    * This is helpful for making generic templates that include the outpost where you are creating the template
* Fixed multiple Supply Drone bugs
* Economy flowcharts for Mayhem 3

## Links
* temetvince Youtube Playlists (X3 Mod Install Videos):
	* https://www.youtube.com/channel/UCw7tARIJee8gd1OpeSjAEMw/playlists
* temetvince Egosoft Forums:
    * Alaankwa: https://forum.egosoft.com/viewtopic.php?f=94&t=441824
* Star Wars Mayhem 2 ModDB:
    * https://www.moddb.com/mods/star-wars-mayhem-2
* X3 Mod Github Repositories:
    * Alaankwa: https://github.com/temetvince/x3ap-lu
    * Star Wars Mayhem 2: https://github.com/temetvince/x3ap-swm2

