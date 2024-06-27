# Alaankwa
* **Click [HERE](https://github.com/temetvince/alaankwa/archive/refs/heads/main.zip "The equivalent of clicking the Code button then Download ZIP") to download this repository.**
* *'Alaankwa' means 'star' in the Miami-Peoria language (Myaamia)*

## Table of Contents
1. [Communities](#communities)
2. [Installation](#installation)
    - [Pre-Install](#pre-install)
    - [Install](#install)
    - [Post-Install](#post-install)
3. [Features](#features)
    - [LU + Mods Specific](#lu--mods-specific)
    - [General](#general)
    - [And More](#and-more)
4. [Downloads](#downloads)
5. [Credits](#credits)

## Communities
* [Join the Discord](https://discord.gg/S587CRb)
* [Egosoft Forum thread](https://forum.egosoft.com/viewtopic.php?f=94&t=441824)

## Installation

### Pre-Install
1. Ensure the Bonus Pack is **NOT** installed!
2. Optionally download and install ReShade:
   - [ReShade](https://reshade.me/)
   - When asked for the game, browse and select X3AP.exe in your X3 install folder.
   - The game uses Direct3D 9.
   - When asked, select the temetvince.ini preset and install the pre-selected shaders.

### Install
1. Install Litcube's Universe or Star Wars Litcube's Universe.
2. RECOMMENDED: [Use the Alaankwa installer](https://github.com/temetvince/alaankwa-installer)

OR

2. Copy the contents of the Alaankwa `x3 terran conflict` folder into your LU's `x3 terran conflict` folder.

### Post-Install
- If you don't like the new font, delete the `f` folder in your `x3 terran conflict` root install directory.
- To enable Phanon Extreme for a challenge, modify `Phanon Extreme` entry `150` in `addon/t/9979-L044.xml` and set it to `1` instead of `0`.
- To enable AutoRotation of your player ship, modify `Overachiever` entry `101` in `addon/t/9979-L044.xml` and set it to `1` instead of `0`.
- Alternatively, replace `addon/t/9979-L044.xml` with a renamed `addon/t/9979-L044 (Phanon Extreme).xml`, `addon/t/9979-L044 (Overachiever).xml`, or `addon/t/9979-L044 (Overachiever + Phanon Extreme).xml`.
> **Note**: The default settings are duplicated in `addon/t/9979-L044 (Default).xml`.

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
- An optional graphics improvement utilizing ReShade is included.
- The map is prettier and less dark overall.
- A new game font, [Fantasque Sans Mono](https://github.com/belluzj/fantasque-sans).
- Longer range combat with cool looking stagger fire.
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
- Removed ATF Mapping Service mammoths from the game (a mission bug).
- Fixed export/import OCV Mammoth bug.

## Downloads
* [No-Steam Exe](https://www.egosoft.com/download/x3ap/bonus_en.php)
* [ReShade](https://reshade.me/)
* [LU](https://www.x3collective.com/lu-setup/lu-downloads/)
* [SWLU](https://www.moddb.com/mods/star-wars-lu-swlu/downloads)

## Credits
* Special thanks to Joubarbe for making Mayhem and allowing me to do whatever with his code.
    * You can show your support by buying Joubarbe a coffee: [Buy Joubarbe a coffee](https://www.buymeacoffee.com/Joubarbe)
* Thanks to Ashakar for bullet staggering and long range weapon targeting.
* Thanks to Sepa for graciously allowing me to redistribute the Mothership mod!
