# BigBradley-Super-Castlevania-IV-Manual-APworld
Requirements: A North American copy of Super Castlevania IV, and the attached password sheet. If for whatever reason you can not use my password sheet, you will need to play through the entire game yourself and write down passwords for each level and fighting Dracula.

Goal: Collect 5 Dracula's Chamber Keys and defeat Dracula. Upon collecting all 5 keys, you can go straight to the fight using the password system.

Shuffled Items:

Whip-Related Upgrades:
- Whip Upgrade (3): collecting 1 allows you to use your whip, collecting 2 allows you to upgrade it once, and collecting 3 allows you to fully upgrade it. If you obtain too many whip upgrades in-game before you are supposed to, you must deplete your own HP at the earliest convenience. By default you start with 1, DO NOT remove this upgrade from your starting inventory in the game.json on Cursed difficulty unless you want to have a bad time.
- Upwards Whip: collecting this allows you to whip upwards. If you are playing on an emulator, I suggest mapping UP to a button you do not use in-game until you obtain this item.
- Downwards Whip and Crouch: collecting this allows you to whip downwards and crouch. If you are playing on an emulator, I suggest mapping DOWN to a button you do not use in-game until you obtain this item.
- Grapple: collecting this allows you to grapple onto grapple points.
  
The following items allow you to use their corresponding sub-weapon:
- Axe
- Progressive Horizontal Weapon (2): collecting 1 allows you to use the Dagger, collecting 2 allows you to use the Cross.
- Holy Water
- Watch

Sub-Weapon Adjacent Upgrades:
- Progressive Shot (2): collecting 1 allows you to use the Double Shot, collecting 2 allows you to use the Triple Shot.
- Big Heart (3): Increases your max heart count by 5, unaffected by Corrupted Hearts.
- Heart (filler): Increases your max heart count by 1.
- Corrupted Heart (trap): Decreases your max heart count by 1.
- 
Heart System:
The amount of total hearts you can hold at once is limited to 5, but by collecting Big Hearts and Heart items, you can increase the max amount you can hold. Corrupted Hearts reduce your max heart count from normal hearts by 1.
Your max heart count is calculated as follows: 5 + (collected Big Hearts[5]) + (collected Hearts[1] - collected Corrupted Hearts[1])

Level Keys:
Each level in the game can only be accessed by collecting its corresponding key. By default, you start with 1 random Level Key. You can not play Level 1 unless you have its key. You can not continue to the next vanilla level after completing a level unless you have its corresponding key. In order to access each level, you must use the password system and the attached password sheet to access each level from the main menu.

Checks:

Block Completion/Boss/Level Completion: Complete specific Blocks in a Level, defeat a boss, and/or complete a Level to obtain a check.
- Weapon Candles: Collect a weapon from a candle to obtain a check.
- Pork Candles: Collect pork from a candle to obtain a check.
- Miscellaneous Candles: Collect a Rosario, Invisibility Potion, or 1-UP from a candle to obtain a check.
- Destructible Blocks: Destroy some destructible blocks and find the item hidden behind them to obtain a check.
- Secret Room Discovery: Discover a Secret Room to obtain a check. Note that you only get 1 check from Secret Rooms, the additional items found inside them DO NOT count as checks.

Difficulty Options:

For each difficulty option there is a separate APworld and yaml.
- Normal: Does not expect any high level tricks. Level 6 and onwards expect you to have your full gear or close to it by the end of each Level. 5 Corrupted Hearts shuffled in the item pool.
- Hard: Expects some high level tricks. Logically speaking, you should not need your full gear to complete any of the Levels in the game. 10 Corrupted Hearts shuffled in the item pool.
- Cursed: Expects you to be able to complete most of the game with only your base whip plus whatever else is required to get past specific obstacles. Only recommended for Castlevania pros. 20 Corrupted Hearts shuffled in the item pool
