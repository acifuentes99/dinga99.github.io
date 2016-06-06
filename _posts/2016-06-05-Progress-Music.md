---
layout: post
title:  "Progress with the Gameplay, and Music"
date:   2016-06-05 11:00:20 -0300
---

[Link of the game](http://gamejolt.com/games/element-rampage-beta/149862)


I think that 2 weeks has just passed, not doing things to progress with the game. That because of some exams that I had in the University. But now, I got a lot of new ideas, to make progress with the game. Tomorrow (June, Monday 6) I must have some advances with the game. In the best case, the Gameplay done. I'm going to describe the progress that I have this days of the week:

### Music

The Videogame course has make an alliance with a Videogame music course of another institute, so, every group of my course, now has a team to make Videogame music. In my case, I wanted some "retro-feeling" music for the game. So, it's a work for the musicians, to make a great audio, that represent the feeling of the game, to make the player more connected with the gameplay.

There are two main focus with the music: An stage music, and a Boss music. Both tracks are going to split in two parts: A tension part (more action), and a normal mode (not so much action).

### New sprites for the game


* One of the factors that the game had missing, is that the sprites are inconsistent with the theme of the game. So, I searched for a base for sprites in internet, and give them some edits in Gimp. It took a lot of my Saturday (because learning more how to use a program like Gimp, and the fun that I get when editing the sprites), but the result is good. Now, in the next week, I want to make more progress in the visual part of the game. (To make it more attractive).


### Harder enemies

Now, this is a very interesting part. I followed, and spend a lot of time, studding this tutorial:

[Tutorial](http://gamedevelopment.tutsplus.com/series/understanding-steering-behaviors--gamedev-12732)

It's about how the enemies (or other element of the game, that it's not the player) can get more natural behaviours. In a rouge like game, that's an very important factor to consider for the gameplay, because it make it like the player to understand the game, has to study the behavior of the enemies.
Now, I implemented the "seek", "evade collisions" behaviours in the enemies of my game, because are more important in this first time, for a basic development of the enemies part of the game.

The results are great, but the game got a lot harder now, in comparison of before. So, new problems, or new challenges in this interesting part has come.

### Implementation of weapons

A thing that I like a lot of rouge likes.., is that has a variety of weapons to choose. Every one of them, has their advantages and weaknesses. In the game, the "Only melee contact player vs enemy" it's now optional, But the primary weapons it's to fire the opponents.

For now, the only option is, when the player kills an enemy, it drops the "red bullet". That gives the player the shotgun. For now, it's not possible to change weapons, or wait until the shotgun has no ammo, but for the next two weeks, that feature it's going to be implemented.

### Other things / future ideas

The game it's getting on form. There are a lot of new ideas since the past weeks, but because are a lot, them weren't implemented at this time (because, I was thinking how I can code them).

This is the list:

* Implementation of Chests and Golden Chest: This chests, gives the player some bonuses or "anti-bonuses", making a more rouge like experience with the game.
* Hud: The HUD will give the player, the information of: Weapons, ammo, health, experience, score, and more other things.
* Upgrades: The player will have an upgrade mode, that the player can spend the experience, rewarded by defeating enemies, to improve things like weapons, speed, damage, and others
* Boss battle: The boss battle, it's something important in the Game. That will make an objective for the player, to be the strongest as possible to face him, and win the battle. It is a priority element for the gameplay, will be implemented during the week.


### Bugs

As the game is going forward in the development..., now some bugs started to appear (I tried to fix them... But it's a problem about computer resources, the framework, or something that at this moments I don't know how to fix them). So, that's the way of developing something in a computer. The bugs are:


* Going up-left or down-left while shooting doesn't work. (Going up-right and down-right works).
* Starting at the third wave, the enemies stop to shoot the player, or do that less frequently. That could be because of resources of the framework, or that could be some function not used at the right way.
* Enemies when following the player, start to stack one on another, looking like there's only 1 enemy, but are more than 1.

