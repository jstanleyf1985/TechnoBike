# TechnoBike
7 Days to Die Motorcycle Mod


A motorcycle vehicle mod. Craftable using the same materials as a vanilla motorcycle. It has roughly similar settings currently than the vanilla motorcycle and comes with the same amount of mod slots (4). The players on my private server asked to have a bike mod, I thought I'd share the mod with the community. I've tested this as of the latest version (Alpha 19.5) and also Darkness Falls (19.4B7) and appears to be working fine.

Speed: 15 - 25 (can be edited)
Gas Tank Size: 250 (can be edited)
Hit Points: 6000 (can be edited)
Seats: 1 player
Comes in the following colors
 Red (default)
 Black
 Blue
 Gold
 Green
 Orange
 Pink
 Purple
 Teal
 White

To Edit,  change the following numbers in the following file locations inside the mod folder and save it. 
(note *** your install location may be different)
(note *** you'll need to do this for each color if you want to change them as well)

Speed - C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods\TechnoBike\Config\vehicles.xml
---- Edit <property name="velocityMax" value="15, 25"/> , change the 1st and 2nd value to min and max speed.

Gas Tank Size - C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods\TechnoBike\Config\vehicles.xml
----- Edit <property name="capacity" value="300"/>, change the 300 higher to increase capacity or lower to decrease it

Hit Points - C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods\TechnoBike\Config\items.xml
---- Edit <passive_effect name="DegradationMax" operation="base_set" value="6000"/>, change value to set HP of vehicle

------------------------------
Installation instructions

1.) Unzip this folder
2.) Place this folder inside your mods folder
3.) Structure should look similar to the following
  \mods\TechnoBike\ ... multiple folders
4.) It should NOT look like the following
  \mods\mods\TechnoBike\ .. files
