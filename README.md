# samplecode
Sample code from - How to kill Monsters: The Cabin

//This is a selection of codes from my current project, “How to Kill Monster: The Cabin” a short repeatable game that is a prequel to a Dark Rift Horror film https://darkrifthorror.com/ that is to be released by the end of 2022. 
It is a top-down shooter in procedurally generated rooms. Where each boss has a different gaming mechanic (2d Platformer chase, turn-based battle system) at the end of a set of rooms. 
Please see a trailer for the demo: https://www.youtube.com/watch?v=EIU4vpsrK6s

The samples of codes I’ve included are:

Enemy Code -
The enemy code and combat features for 5 types of enemies 
EnemyBaseCode, the base code for all the enemies.
zombieEnemyMovement for the basic combat enemies.
ZombieReproduce which is zombie enemies that spawn smaller enemies on death.
EnemyShoot which is the shooting enemies.
EnemyBullet, which controls the shooting enemies bullet
EnemyBurry which is an enemy that digs underground, moves to a different location, pops up and then shoots in 8 directions. Then repeats.

Event System and Dialog –
This is a set of codes that control UI, the event system and Dialog
DialogProceduralLevel, dialog manager for the procedurally generated levels.  
EventSystemController, managing all UI button systems
FullUIReset, Health and Inventory reset
TitleLevelSelect, Lets players enter a code that they receive when they die to start back at a level again
inventoryUI, controls the test for the coin, key bomb UI text.
