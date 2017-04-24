# ExileZ Mod by [FPS]kuplion - Based on ExileZ 2.0 by Patrix87

This is an update/modification of ExileZ 2.0 by Patrix87. The file scructure has been cleaned up, along with a number of edits to fix or update functionality. The intention of this modification is to build upon the work done with ExileZ 2.0 and to add functionality with ease of configuration in mind.

## Features

Dynamic Zombie spawning

Location based Zombie spawning

Harassing Zombies

Hordes

Built in Zombie mission (for specific maps)

Working safezone and territory detection

Supports ANY map (and includes a number of map specific configs)

Highly configurable Zombie options

Supports Infections (See here for required additional files: http://steamcommunity.com/sharedfiles/filedetails/?id=614815221)

## Requirements

Zombies and Demons (http://steamcommunity.com/sharedfiles/filedetails/?id=501966277)

ExileMod (http://www.exilemod.com/downloads/)

## Download

https://github.com/kuplion/ExileZ-Mod

## Installation

1: Edit main settings in 'exilez_mod\config.sqf'.

2: Edit triggers and settings (if required) in 'exilez_mod\triggers\'.

3: Edit zombie classes and loot in 'exilez_mod\zombies\'.

4: Edit the Zombie mission loot in 'exilez_mod\mission\zMissionLootCrate.sqf'.

5: Pack exilez_mod.pbo with either PBO Manager 1.4b x64 (http://www.armaholic.com/page.php?id=16369) or Eliteness/MikeRo tools if you have them.

6: Place exilez_mod.pbo in your '@ExileServer\addons\' folder.

7: Add "ryanzombies" & "ryanzombiesfunctions" to the "addons" section of your mission.sqm (don't forget to adjust your commas accordingly!!)

addOns[]=
{
	"exile_client",
	"a3_map_altis",
	"Ryanzombies",
	"ryanzombiesfunctions" // Make sure the last entry does not have a comma after it!!
};

## Configuration

The script is configured to run with Altis, Tanoa, Namalsk, Chernarus (Normal, Winter, Summer, and Isles), Napf, Bornholm, Esseker, Al Rayak, and Taviana, with all the features enabled by default but will still run on ANY map if an unsupported map is detected.

Almost all of the information related to the configuration is in 'exilez_mod\config.sqf'.

## How to export Triggers positions

1: Open arma with NO MODS other than the map you are using.

2: Open Eden Editor and DO NOT load a mission file.

3: Place an Elliptic Marker *(not a trigger) on every region you want a spawner and set its radius.

4: Copy Paste the code from GetMarkerCmd.txt inside the debug console.

5: Execute the code.

6: Open Notepad, CTRL+V / (Paste).

7: ???

8: Profit!

## Donations

If you feel so inclined, donations can be sent to myself via PayPal donate@FriendlyPlayerShooting.com or to Patrix87 via PayPal patrix87@gmail.com

## License
Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)
