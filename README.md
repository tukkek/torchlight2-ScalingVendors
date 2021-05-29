# Scaling Vendors mod for Torchlight II

Blacksmith's items now scale with player level, from Act 1 to Act 4 and Mapworks. This change does not affect General Merchants but, to make up for it potions and scrolls have been added to the Blacksmiths as well.

This is intended to be used with mods like [The Endless Dungeon](https://steamcommunity.com/sharedfiles/filedetails/?id=160404095) or [The Toy Collector](https://steamcommunity.com/sharedfiles/filedetails/?id=138078507) and similar (or merge-mods that contain those) that either unlock infinitely-scaling play from Act 1 or that unlock Mapworks early.

## What was changed

Blacksmiths from acts 1, 2, 3, 4 and Mapworks have had their Monster data altered:

1. Their minimum inventory levels were removed (Behavior tab)
2. A single roll of the MERCHANT_GENERAL_INVENTORY treasure table was added (Treasure tab)

Note that #2 was unnecessary for the Mapworks vendor as he already offers consumables natively.
