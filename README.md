﻿# Valheim-TimedTorches
Original Mod by Gurrling and found here [TimedTorches Original](https://www.nexusmods.com/valheim/mods/962)

## Fixed for Valheim Frost Cave Update
Original Mod by Gurrlin all credit goes back to them for creating the mod

This has been fixed for the Valheim Frost Cave Update  
### This is not my mod and all credit goes back to the original author Gurrlin
I will do my best to answer questions and fix issues.

### About the Mod
Tired of having to add resin to the tens or hundreds of torches lighting up your viking village? 
This mod takes care of that by allowing you to set a time-span during which they are always on, 
even if they burned all their fuel. Never let your base go dark again!

### Background
I created this mod because I got tired of having to re-light all the torches in my base from time to time when all I wanted was for it to look pretty in the dark.
Timed Torches allows you to have a global timer for any light source/fireplace that uses fuel.
This means that you can finally have a village full of torches and have it light up every night when the sun sets
and then turn off when it rises in the morning without constantly having to refill them with resin or other fuel sources

### Configuration

- OnTime - Time of day when torches should turn ON. (The default is set to 4.30pm in-game time)
- OffTime - Time of day when torches should turn OFF. (The default is set to 6.30am in-game time)
- AlwaysOnInDarkBiomes - If true, objects listed in AffectedFireplaceSources will always burn in areas that Valheim considers 'always dark'. E.g Mistlands or any biome during a storm.
- AffectedFireplaceSources - List of objects to be affected by the mod (see below for list of supported objects). By default only torches are added.
- AllowAddingFuel - If true, enable adding fuel to torches which will make them burn during daytime as well.
- FuelDurationMultiplier - Multiplies the duration of each fuel added to objects listed in the FuelDurationSources.
- FuelDurationSources - See FuelDurationMultiplier.

Note: If OnTime and OffTime is set to the same value, for example 0 and 0 the fireplaces listed in AffectedFireplaceSources will burn 24/7.

The config file is located in "<GameDirectory>\Bepinex\config" (You need to start the game with the mod installed for the config file to be created).

### List of supported objects:
  
piece_groundtorch  
piece_groundtorch_wood  
piece_groundtorch_green  
piece_brazierceiling01  
piece_walltorch  
hearth  
bonfire  
fire_pit  
piece_jackoturnip


### Installation (manual)  
Extract DLL from zip file into "<GameDirectory>\Bepinex\plugins"  
Start the game.

### Version Information

0.6.0 - By TastyChickenLegs

- Removed reference to Water Volume
- Updated version with credits back to Gurrlin

0.5.1  -By Gurrlin

- Original version by Gurrlin
