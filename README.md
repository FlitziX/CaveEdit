# CaveEdit
A mod to provide easy ways to place large amounts of tiles very quickly (It's Minecraft's WorldEdit mod but in C:U)

I was looking for something like this but didn't find anything, so I guess I'm just gonna make it myself (probably badly).

# Please note
This is my first ever C:U mod as well as my first ever time using C#, so expect jank and probably coding sins beyond mortal mind's comprehension.

# Features
## Current:
-Building wand item that lets you free-hand place rectangles of a chosen tile

-wandsettile command to set the tile used by the held wand (e.g. wandsettile 12)

-wandpicktile command to select the currently hovered over tile as the tile used by the wand (hover over any tile and execute wandpicktile)

|For these two you will need to hold a wand, wands store their settings

-wandspawnalltiles command to place every tile currently in the game (for use with wandpicktile, it will spawn the tiles at  the position the cursor was located when the console was opened)


## Planned:
-Make it compatible with modded tiles (I'm sure that won't be a pain in the ass to figure out)

-Shape placers for Circles/Lines/Squares/etc.

-Entity placer for easily putting down entities (maybe)

-Copy-Paste tool for Copying/Pasting/Stacking/moving selections (mc WorldEdit style)

-Masks

-Undo feature (if i manage that)

# How to use
-1: Download the .zip file

-2: Unzip it in the BepInEx/plugins folder

This mod requires CUCoreLib and BepInEx (obviously)
