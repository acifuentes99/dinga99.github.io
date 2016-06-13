---
layout: post
title:  "Weapons and Stats"
date:   2016-06-12 21:00:20 -0300
---

[Link of the game](http://gamejolt.com/games/element-rampage/138566)


 In this weekend (my time of progressing with the game), the Gameplay it's almost complete. Now, the main focus of this weekend it's all about the stats, and upgrade of them while playing. The main factors covered where the following:

 * Weapons: Having some variety of them, changing them, give the player feedback of the ammo stats
 * Stats: A stats screen in the pause menu. When the player pauses the game, there's 4 stats displayed, and also how much they are upgraded.


### Weapons

* In this session of developing the game, I advanced in the factor of having a hud for the player, seeing what weapon it's using at the time, and also the ability to change them during the game.
* Also, the three weapons have their own rate of fire, and damage.
* The idea of having Three different weapons, and two of them have limited ammo (but upgradeable), it's that, the weapons give the player more power to survive in the game.
* In future developing, every weapon will have their own sprite for the shoots, and also their respective SFX.


### Stats

* This it's a very important part of developing a compulsion loop, and make the player be more attached to the game. Now, killing enemies will give the player a new resource on the game, called "experience" (exp). It can be spent in upgrade stats of the player, that are Armor, Max Ammo, Damage and Speed.
* Armor gives the player, the opportunity of reducing the damage that comes to him, when dealing with shoots. Max ammo, increases the total amount of ammo, that the player can carry for the Shotgun, and the Uzi. Damage, as the name says, increase the damage that the player toes to the enemies with weapons. Finally, speed, increases player speed on the game, giving him more ability to evade shoots of the enemies.
* Now. I think that with this stats, the game looks more easier to learn the stats mechanics, than if I add more features. So, for an initial release, it's okay with this stats.


### A note about implementing these factors

* With the Weapons fully developed, and the stats, now the game has a more dynamic gameplay. The player will be motivated, to kill the enemies in the most intelligent way (using the elements) to manage the ammo. Or also, a great strategy, it's to carry a lot of ammo before the boss, so, a more much quantity of damage can be done, than if the player comes with no upgrades at all in max ammo.



### Experience as a developer

* A great technique and tool that I used to bring the pause menu, it's using tiled to draw the menu. Recently, I was using tiled to create the maps, and to understand JSON files on Phaser. Now, I used the program to create the menu. So, it's for drawing elements on the screen. This allowed me to reduce the amount of work to make the UI (in the first tutorial, I spent a lot of time placing the elements of the screen only with code).
* Then, I have to learn a little more of using JSON files in Phaser. In this, I spent time, but it has been use wisely.
* One of the difficulties of progressions this weekend with Phaser when implementing the Pause menu. That is, because in phaser, making the game pause, pauses everything. And also, there wasn't an direct method to make the pause menu, like other state. So, I followed the example in the Phaser page, to make the menu. And to make it clickable in the stats icons, I used the method "getBoundaries()", to listen the clicks that the user does in the interface.


### Bugs

* Finally, I fixed the enemies shoot bug!. The problem was, with the initial object of "WeaponList". The same element, was used by the enemies and the player. So, when a new enemies where created, the rate of fire increases indefinitely, making it useless on the framework. So the solution, is to clone the WeaponList object for the enemies and the player.
* Still, the game has an issue with changing the tension of the music.


### Other things to develop


* The boss battle
* Using little presets of maps, to make an unique map every time
* Multiple levels in the game
* Enemies can have the ability of shooting themselves.

