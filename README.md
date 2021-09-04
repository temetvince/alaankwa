# temetvince's Litcube's Universe mods
To download, go to the latest release and click 'Source code (zip)': https://github.com/temetvince/lu-mods/releases/

## Features:
* All ships orient themselves upright with respect to "up"
* Improved escort behavior
* Added a Map Gates command that tells a ship to map the gates in its current sector
* Debug scripts. See Development Features below
* An optional Graphics Improvement mod utilizing ReShade is included
* An optional font change is included, disabled by default. It is Fantasque Sans Mono, you can find the original here: https://github.com/belluzj/fantasque-sans 

## Installation:
If you don't want to use Reshade and want to skip the Graphics Improvement mod functionality, skip to step 5.
1. Download and install ReShade: https://reshade.me/
2. When asked for the game, browse and select X3AP.exe in your x3 install folder
3. The game uses Direct3D 9
4. When asked, install all the shaders. Everything. All of them
5. Copy this mods 'x3 terran conflict' folder into your game's 'x3 terran conflict' folder. When asked, overwrite everything
6. If you want to use the optional font, then go to your game's 'x3 terran conflict' folder. Rename the folder 'RenameMeTof' to 'f'. Notice the LicenseAndCopyright file for your information

## Graphics Improvement Mod
You can take before/after screenshots that save to your root install folder with the PrintScrn button on your keyboard. To access the options in game, press [SHIFT]+[~] (or [SHIFT]+[`])

## Settings
Some settings can be changed in the '9979-L044.xml' file located in the 'x3 terran conflict/addon/t/' directory

## Development Features
* Debug scripts for development. It can take in any text decodable object, say an array of tables, and output it in game to the user
* You can call this script like this: $debug.return = [NULL] -> call script 'temetvince.Debug': debug=$Unknown trackingAim=$ShipOrStation
* $debug is the message or object to debug. Can be simple like a ship name or complex like an array of tables
* $trackingAim is optional. If provided, then the debug script will only run if that entity is the player's tracking aim in game
