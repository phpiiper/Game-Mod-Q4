# PLPARENA

(A Quake 4 Mod)

## Quick Blurb

A PvE open arena game mode with a twist. The blaster can be modded to use special runes to change the way how a blaster interacts with enemies. Cause burns and damage over time, freeze enemies in place, have enemies fly into the air, or affect the damage the blaster can deal.

## How to Play
After launching Quake 4 with this mod loaded, in any location when spawn, open up the in-game command terminal and type in the command: `plpAM start`

## Command Line Notes

### `plpAM <params>`

[No Parameters]

Brings up the list of commands that can be run.

[Parameters]
- `start` : start the Arena from Round 1
- `end` : forcibly end the Arena and procede to the next round (for debugging / cheat purposes)
- `setRound` : forcibly change the Arena's Round to this value (default: 0).
- `display <param>`
    - `round` : Returns which round the player is in
    - `inRound` : Returns text confirming whether or not, player is in a round of the Arena (monsters are still alive)
    - `enemies_left` : Returns how many enemies are left in this Round. Returns -1 when complete.
- `actions <param>`
    - `setup` : Cheat setup, gives all runes and add it and `god` mode, then start round
    - `spawnrandom` : Summon random enemy using random enemy function (for debugging / chear purposes)