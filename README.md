# Alaankwa

## Downloads
* English: **Use the [Alaankwa Installer](https://github.com/temetvince/alaankwa-installer)**, otherwise click [HERE](https://github.com/temetvince/alaankwa/archive/refs/heads/main.zip "The equivalent of clicking the Code button then Download ZIP") to download this repository.
* Pусский / Russian: [Russian GitHub](https://github.com/alexalsp2/x3ap-lu-swlu-alaankwa-rus)

## Communities
* [Join the Discord](https://discord.gg/S587CRb)
* [Egosoft Forum thread](https://forum.egosoft.com/viewtopic.php?f=94&t=441824)

## Description
Alaankwa is an "all but the kitchen sink" mod for X3: Albion Prelude which enhances the game with new features, gamestarts, and bug fixes. It requires the Litcube's Universe (LU) or Star Wars Litcube's Universe (SWLU) mods, and it includes many quality of life improvements and new gameplay mechanics. It is also compatible with the Galaxy in Chaos (GiC) addon for SWLU. Alaankwa means 'star' in the Miami-Peoria language (Myaamia).

## Installation
1. Install [X3: Albion Prelude](https://store.steampowered.com/app/201310/X3_Albion_Prelude/) from Steam.
    - IMPORTANT: Check your X3:AP DLC and ensure the Bonus Pack is **NOT** installed!
2. Launch the game from the Steam at least once.
3. Copy the Steam *x3 terran conflict* folder to a new location.
    - This is known as your *root* folder.
    - Only use you new *root* folder you just created going forward; ignore the original Steam folder.
4. Copy the [No-Steam Exe](https://www.egosoft.com/download/x3ap/bonus_en.php) into your *root* folder.
5. *Optional:* Install [ReShade](https://reshade.me/)
   - When asked to select the game, browse and select the No-Steam Exe in your *root* folder.
   - The game uses DirectX 9.
   - When asked, select the temetvince.ini preset in your *root* folder and install the pre-selected shaders.
6. Install [Litcube's Universe](https://www.x3collective.com/lu-setup/lu-downloads/) or [Star Wars Litcube's Universe](https://www.moddb.com/mods/star-wars-lu-swlu/downloads) into your *root* folder.
    - LU GUI install options are illustrated in the [Litcube's Universe Manual](https://x3collective.com/lu-features/gui/).
7. Place the [Alaankwa Installer](https://github.com/temetvince/alaankwa-installer) inside your *root* folder and run it.
8. *Optional:* If using Star Wars Litcube's Universe, install the [Galaxy in Chaos](https://www.moddb.com/mods/star-wars-lu-swlu/addons) addon into your *root* folder.

## Configuration
Only for LU/SLWU, NOT for the optional Galaxy in Chaos addon
- Configuration is done via the *addon/t/9979-L044.xml* file.
- For playing against a perpetual version of the hardest Phanon Corporation:
  - Replace *addon/t/9979-L044.xml* with a renamed *addon/t/9979-L044 (Phanon Extreme).xml*.
- To have Auto-Rotate apply to the playership:
  - Replace *addon/t/9979-L044.xml* with a renamed *addon/t/9979-L044 (Overachiever).xml*.
- To restore the default settings:
  - Replace *addon/t/9979-L044.xml* with a renamed *addon/t/9979-L044 (Default).xml*.

## Features

### LU Specific
- **ROTATIONAL THRUSTERS**
    - Class rotation variables have been increased:
        - M1/M2/TL = 200%
        - M7 = 50%
        - M6 = 25%
        - M3 = 40%
        - M4 = 25%
        - TM/TP/TS = 10%

### General
- **IMPROVED PILOTING**
    - Ships automatically orient "upright" in the game like they do in the movies.
    - Overachiever: Improved Piloting applies to the playership.
- **STANDARDIZED FLEET OPERATIONS**
    - Escorts will attempt to follow at reasonable speeds instead of flying all over the place.
- **SHIP COMPUTER UPGRADES**
    - New commands for the Ship Command Menu:
        - Map Gates: This command maps the gates in its current sector.
        - Self Destruct: This command tells the ship to self destruct.
- **FRESH HOTKEYS, GET YOUR HOTKEYS**
    - Decide which hotkeys are configurable in the Hotkeys Menu.
        - All of Space: CHEAT: This hotkey adds satellites to all sectors with jumpgates which don't already have one.
- **SHIP COMPUTER UPGRADES**
    - New commands for the Ship Command Menu:
        - Manage Mothership: Allows you to manage a Mothership. (Feature: Sepa's Mothership)
        - Manage Wares: Allows you to manage the wares of a Mothership.
- **FRESH HOTKEYS, GET YOUR HOTKEYS**
    - Decide which hotkeys are configurable in the Hotkeys Menu:
        - Blueprint Data Scanner: Activates the Blueprint Data Scanner.
        - Phanon Industrial Espionage: Activates the Phanon Debug Menu.
        - Satellite Monitoring Plus: Activates the Satellite Monitoring+ Menu.
        - Ship Compendium Plus: Activates the Ship Compendium+ Menu.
        - All of Time: CHEAT: Saves your point in time to the next slot even if you don't have Salvage Insurance.
        - Joubarbe's Player Journal: Activates the Player Journal.
        - Show/Hide Miners: Toggles showing or hiding miners from the player property list.
- **TOP NOTCH RECRUITERS**
    - All recruited Trade Mrk III Pilots are level 8 (enough to start Galaxy trading).
- **TRADE EMBARGO**
    - Removes all NPC ships docked at player stations which are not open to race traders.
- **RAPID DEPLOYMENT**
    - Ships following another ship will no longer check if their followers can jump prior to jumping themselves.
- **SEPA'S MOTHERSHIP**
    - Motherships are TL class mobile factories:
        - Alaankwa Corsairs: A unique gamestart focused on unlocking blueprints by scanning ships.
        - Alaankwa Corporation: An advanced gamestart with a small functioning empire. Phanon is extremely difficult.
        - Assembly Lines: Ship Building Speed is a function of the population.
        - Just in Time (JIT) Manufacturing: Allows full production speed even when producing more than one type of ware.
        - Research and Development Budget: The number of data scans required to get the cheapest blueprint.
        - Shield Expertise: Maximum shield percentage of the target while using the data scanner.
- **UNDER NEW MANAGEMENT (PHANON)**
    - Enables various changes to help Phanon corporations be more competitive:
        - Corporate Bailouts: Keeps Phanon corps afloat if their balance sheet goes negative.
        - Backroom Deals: Lowers ship manufacturing costs.
        - Seedy Investors: Finances cash from less reputable sources.
        - Well Connected Leadership: Commands a premium in salaries.

### AND MORE
- The OCV should operate a bit smarter and expand a bit better.
- Longer range combat with cool looking stagger fire.
- An optional graphics improvement utilizing ReShade is included.
- The map is prettier and less dark overall.
- Debugging scripts for development.
- Updated LU Export/Import to support Alaankwa.
- Quickshuttles notify the player when they have completed their task and have returned home.
- Universe Traders proactively sell off unneeded wares in their cargo bay.
- Universe Traders move to a random core sector within their jump range if no trades are found.
- Player Space Suit has SETA, trading capabilities, video enhancement goggles, and a bioware scanner (LU only).
- Miners no longer run into asteroids when the player is in sector.
- The Player Headquarters, Equipment Docks, and Trading Stations are now available as Sources in the Dockware Manager.
- MLCC ships set to Assist Escort will no longer attempt to escort themselves.
- Ships will remember their homebase when the player transfers into the ship.
- Ships with a Quantum Jumpgate Extension can now jump to a TL whose cargo contains a jump beacon.
- Removed ATF Mapping Service Mammoths from the game (a mission bug).
- Fixed export/import OCV Mammoth bug.
- Added an infinite script debug tool (for developers).

## Credits
* Special thanks to Joubarbe for making Mayhem and allowing me to do whatever with his code.
    * You can show your support by buying Joubarbe a coffee: [Buy Joubarbe a coffee](https://www.buymeacoffee.com/Joubarbe)
* Thanks to Ashakar for bullet staggering and long range weapon targeting.
* Thanks to Sepa for graciously allowing me to redistribute the Mothership mod!
* Thanks to Rocket Man for the code to allow jumping to a TL containing a jump beacon.
* Thanks to Hector for the infinite script debug tool.
* Thanks to Fallout(EG) for the Russian translation.
