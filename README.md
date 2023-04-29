# Alaankwa
* To download, go to the latest release and click 'Source code (zip)': https://github.com/temetvince/alaankwa/releases/
* 'Alaankwa' means 'star' in the Miami-Peoria language (Myaamia)

## Discord
* https://discord.gg/S587CRb

## Installation
### Pre-Install
* Optionally download and install ReShade
  * https://reshade.me/
  * When asked for the game, browse and select X3AP.exe in your x3 install folder
  * The game uses Direct3D 9
  * When asked, select the temetvince.ini preset and install the pre-selected shaders.

### Install
* If playing LU, download and run the installer at https://www.alaankwa.com.
* If playing vanilla, copy the contents of the 'Manual Install - Vanilla' folder into your 'x3 terran conflict' folder.
* If playing GiC, copy the contents of the 'Manual Install - GiC' folder into your 'x3 terran conflict' folder.

### Post-Install
* If you don't like the new font, delete the 'f' folder in your 'x3 terran conflict' root install directory

## Features
### General
* IMPROVED PILOTING
    * Ships automatically orient "upright" in the game like they do in the movies.
        * Overachiever
            * Improved Piloting applies to the playership
* STANDARDIZED FLEET OPERATIONS
    * Escorts will attempt to follow at reasonable speeds instead of flying all over the place.
* SHIP COMPUTER UPGRADES
    * New commands for the Ship Command Menu.
        * Map Gates
            * This command maps the gates in its current sector.
        * Self Destruct
            * This command tells the ship to self destruct.
* FRESH HOTKEYS, GET YOUR HOTKEYS
    * Decide which hotkeys are configurable in the Hotkeys Menu.
        * All of Space
            * CHEAT: This hotkey adds satellites to all sectors with jumpgates which don't already have one.
* LITCUBE'S BOUNCE
    * Ships avoid collisions.

### LU + Mods specific
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
* FRESH HOTKEYS, GET YOUR HOTKEYS
    * Decide which hotkeys are configurable in the Hotkeys Menu.
        * Blueprint Data Scanner 
            * This hotkey activates the Blueprint Data Scanner.
        * Phanon Industrial Espionage
            * This hotkey activates the Phanon Debug Menu, which shows detailed Phanon corp information.
        * Satellite Monitoring Plus
            * This hotkey activates the Satellite Monitoring+ Menu respecting all player property, not just satellites. It also shows average salvage value per sector in millions.
        * Ship Compendium Plus
            * This hotkey activates the Ship Compendium+ Menu where ships are shown even if not yet discovered.
        * All of Time
            * CHEAT: This hotkey saves your point in time to the next slot even if you don't have Salvage Insurance.
        * Joubarbe's Player Journal
            * This hotkey activates the Player Journal.
        * Show/Hide Miners
	        * This hotkey toggles showing or hiding miners from the player property list.
* TOP NOTCH RECRUITERS
    * All recruited Trade Mrk III Pilots are level 8 (enough to start Galaxy trading).
* TRADE EMBARGO
    * Removes all NPC ships docked at player stations which are not open to race traders.
* RAPID DEPLOYMENT
    * Ships following another ship will no longer check if their followers can jump prior to jumping themselves.
* SEPA'S MOTHERSHIP
    * Motherships are TL class mobile factories which can produce lasers, missiles, shields, and ships (must be able to dock on the Mothership).
        * Alaankwa Corsairs
            * A unique gamestart which focuses on unlocking blueprints by scanning ships in order to build them instead of buying/selling them.
        * Alaankwa Corporation
            * An advanced gamestart where you are given a small functioning empire. Phanon is extremely difficult.
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
### AND MORE
* An optional graphics improvement utilizing ReShade is included
    * You can take before/after screenshots that save to your root install folder with the PrintScrn button on your keyboard. To access the options in game, press [SHIFT]+[~] (or [SHIFT]+[`])
* A new game font, Fantasque Sans Mono
    * https://github.com/belluzj/fantasque-sans
* Debugging scripts for development
    * Can take in any text decodable object, say an array of tables, and output it in game to the user
    * Call the script like this: $debug.return = [NULL] -> call script 'tv.debug': param.debug=$Unknown param.trackingaim=$ShipOrStation
        * $param.debug is the message or object to debug. Can be simple like a ship name or complex like an array of tables
        * $param.trackingaim is optional. If provided, then the debug script will only run if that entity is the player's tracking aim in game
* Updated LU Export/Import to support Alaankwa
* Quickshuttles notify the player when they have completed their task and have returned home.
* Universe Traders proactively sell off unneeded wares in their cargo bay.
* Universe Traders move to a random core sector within their jump range if no trades are found.
* Player Space Suit has SETA, trading capabilies, video enchancement goggles, and a bioware scanner. (LU only)
* Miners no longer run into asteriods when the player is in sector.
* The Player Headquarters, Equipment Docks, and Trading Stations are now available as Sources in the Dockware Manager.
* MLCC ships set to Assist Escort will no longer attempt to escort themselves.
* Ships will remember their homebase when the player transfers into the ship.

## Downloads
* No-Steam Exe: https://www.egosoft.com/download/x3ap/bonus_en.php
* ReShade: https://reshade.me/
* LU: http://litcube.xtimelines.net/wiki/index.php/Download
* STLU: https://www.moddb.com/mods/star-trek-litcubes-universe/downloads
* SWLU: https://www.moddb.com/mods/star-wars-lu-swlu/downloads
* GiC: https://www.moddb.com/mods/star-wars-lu-swlu/addons

## Credits
* Special thanks to Joubarbe for making Mayhem and allowing me to do whatever with his code.
    * You can show your support by buying Joubarbe a coffee:
        * https://www.buymeacoffee.com/Joubarbe
* Also thanks to Sepa for graciously allowing me to redistribute his Mothership mod!
