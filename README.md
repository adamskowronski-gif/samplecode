//This is a selection of codes from my current project, “How to Kill Monster: The Cabin” a short repeatable game that is a prequel to a Dark Rift Horror film https://darkrifthorror.com/ that is to be released by the end of 2022. 
It is a top-down shooter in procedurally generated rooms. Where each boss has a different gaming mechanic (2d Platformer chase, turn-based battle system) at the end of a set of rooms. 
Please see a trailer for the demo: https://www.youtube.com/watch?v=EIU4vpsrK6s
<br>
<br>
The samples of codes I’ve included are:
<br>
<br>
Enemy Code -
<br>
The enemy code and combat features for 5 types of enemies

EnemyBaseCode, the base code for all the enemies.

zombieEnemyMovement for the basic combat enemies.

ZombieReproduce is zombie enemies that spawn smaller enemies on death.

EnemyShoot which is the shooting enemies.

EnemyBullet, which controls the shooting enemies bullets

EnemyBurry which is an enemy that digs underground, moves to a different location, pops up and then shoots in 8 directions. Then repeats.
<br>
<br>
<br>
Event System and Dialog –
<br>
This is a set of codes that control UI, the event system and Dialog

DialogProceduralLevel, dialog manager for the procedurally generated levels.

EventSystemController, managing all UI button systems.

FullUIReset, Health and Inventory reset.

TitleLevelSelect, lets players enter a code that they receive when they die to start back at a level again

inventoryUI, controls the test for the coin, key bomb UI text.
<br>
<br>
<br>
Loot –
<br>
BombPickUp, lets players pick up bomb items to be used to drop and blow up objects

HeartPickUp, lets the player pick up a heart health item.

KeyPickUp, lets the player pick up a key to unlock the level door.

Loottable, controls the enemy loot drop system.

powerupSignal, signal for loot items.
<br>
<br>
<br>
Player Code/ Inventory / Inventory Items -
<br>
Inventory, the inventory manager.

ItemPlayer, item information scriptable object.
<br>
<br>
<br>
Player Code/ Inventory / Player Weapon Inventory –
<br>
GunPickUp, code for picking up a new gun.

MeleePickUp, Code for picking up a new melee weapon.

PlayerWeaponGunItem weapon item information scriptable object. 

PlayerWeaponInventory weapon inventory manager.
<br>
<br>
<br>
Player Code/ Player Movement codes – 
<br>
Bomb, bomb explosion mechanics when bomb has been dropped

KnockBack, universal script used for all damage done in the game, for player it will also knock them back when hit.

Player2dPlatMovement, 2d platformer character controller.

PlayerBulletSpawn, the location that the player’s bullets will spawn when PlayerShooting is called.

PlayerMovement, top-down 2d player movement, combat and health.

PlayerShooting, script for the player shooting mechanic.
<br>
<br>
<br>
Player Code/ Player Spawner -  
<br>
PlayerPrefabChange, mangers the spawn of the player prefab at the start of the level or if a weapon item is picked up.  
<br>
<br>
<br>
Player Code/ PlayerHealth –
<br>
ArmourManger, manages the players armour system and UI

HeartManger, Manages the players health system and UI

FloatValue, scriptable serialization to manage armour and health system  
<br>
<br>
<br>
Procedurally generated room code -
<br>
Door, controls the locking and opening of the doors when a player enters a room

Door Collider, manages the door colliders so that players can not walk through unspawned doors in the procedurally generated level 

DungeonCralwer, set position of room spawn

DungeonCrawlerController – direction in which the room will spawn

DungeonGenerator – spawns dungeon scenes into master scene

DungeonGeneratorData – scriptable object, set amount of random rooms spawn

RoomController controls which rooms spawn and how many room type

Room, room info, controls door spawning, and triggers enemy spawning
