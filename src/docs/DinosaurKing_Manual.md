# Dinosaur King Manual Archipelago

## Goal
Defeat DR. Z and reach the credits.

## What Checks are available?

### Always
* Chests
* Stone Fragment from defeating Alpha Gang members
* Forest Flute and Forest Tree Charm

### Optional
* Dig up a fossil in each area (**dig_fossil**)
* Dig at each depth in each area (**dig_all_depths**)
* Items given by NPCs for beating a robot (**enable_fight_rewards**)

## Progression Items

### Always
* Progressive Drill
    * The base drill for White digs is always available
    * Progressive Drill 1 gives access to yellow digs
    * Progressive Drill 2 gives access to orange digs
* Stone Fragment
    * 6 Stone Fragments to access final boss in Command Center

### Optional
* Dungeon Key (**require_dungeon_keys**)
    * Item to restrict access to dungeons
    * Not required for first dungeon (North Mine)
* Upgrade Moves (**block_upgrade_moves**)
    * Allow to modify each move slot
    * Fourth move slot is not usable without the upgrade (because its default state is no move)


## Recieving Inventory Items
Items recieved from checks like healing items and stop drops can be added to your inventory if you modify certain memory while the game is running. These items are not required to play the game if you don't want to or are unable to access the memory directly. The number of items in your inventory is in hex format. The ID of the item is in the memory address before the item count, if that is helpful to find the correct position.

### Items given by this AP
This table is only valid on the NA version of the game.

| Item | ID | Memory Address to Change |
| --- | --- | --- |
| Leaf | 01 | 0x02292315 |
| Sprout | 02 | 0x02292317 |
| Trefoil | 03 | 0x02292319 |
| Alpha Stop Drop + | 09 | 0x02292325 |
| Workbook | 0C | 0x0229232B |
| Manual | 0E | 0x0229232F |
| Book of Mastery | 10 | 0x02292333 |
