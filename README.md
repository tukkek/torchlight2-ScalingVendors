# Scaling Vendors mod for Torchlight II

Blacksmith's items now scale with player level, from Act 1 to Act 4 and Mapworks. This change does not affect General Merchants but, to make up for it potions and scrolls have been added to the Blacksmiths as well.

This is intended to be used with mods like [The Endless Dungeon](https://steamcommunity.com/sharedfiles/filedetails/?id=160404095) or [The Toy Collector](https://steamcommunity.com/sharedfiles/filedetails/?id=138078507) and similar (or merge-mods that contain those) that either unlock infinitely-scaling play from Act 1 or that unlock Mapworks early.

## How to install

**Steam workshop version:** if you own the game on Steam, simply open the [Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=2500774315) and hit the "subscribe" button. Next time you launch the game, enable the mod as normal through the official Mod Launcher.

**Manual install:** Download the latest version of the mod file from [the GitHub release page](https://github.com/tukkek/torchlight2-ScalingVendors/releases) and place it on your Torchlight 2 mod folder. If you're unsure the exact folder location, use the "Open mods folder" button on the official Mod Launcher tool. If needed, check [this video](https://www.youtube.com/watch?v=e5KeocjLUiA) for step-by-step instructions.

## What was changed

Blacksmiths from acts 1, 2, 3, 4 and Mapworks were altered:

1. Their minimum inventory levels were removed (Monster data, Behavior tab)
2. A single roll of the MERCHANT_GENERAL_INVENTORY treasure table was added (respective Spawn Classes)
3. A MERCHANT_BAG was added as Inventory to each blacksmith (Monster data)

Note that #2 and #3 were unnecessary for the Mapworks vendor as he already offers consumables by default.

The Dungeon data for the five hubs were also modified:

1. Set area level range from 1 to 100.
