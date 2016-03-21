---
layout: post
title:  "Second Post"
date:   2016-03-20 20:00:20 -0300
---

Second week after beginning the semester in the University, and also the second developer work on the Videogames Course. This time, the objective it's to develop 3 prototypes more, and 2 of them, must have some kind of "asynchronous response of the game, based on user events". So, what I understand, is that I have to make the game do some actions, in base of the user.

All started with a new mentality for this week: the ideas of the prototypes, must be clear at Thursday. Then, from Wednesday to Saturday (I hope), where going to be the time to develop games. Unfortunately, because of still learning, and checking how Phaser works, it took me until Sunday to consider finish the prototype part (there are still not ready, but playable yes).

So, here its the story of developing:

* The chosen ideas where: A peanut delivery game, an "Operation Game", and a "Rock, paper, scissors" platform.
* The Developing story for every game, and how the asynchronous factor is applied.



### Game 3: Peanut Delivery 

The game consist of delivering peanuts to people in a park. The player uses a peanut train to reach the customers. The customers are going to appear randomly in the screen. And the player had only a capacity of 10 peanuts to deliver, but can charge the storage in the "peanut reserve", in the lower left part of the Screen.
The asynchronous part: For every recharge of peanut, in a number between 2 or 8 peanut delivered, a random queen will appear on screen. She will move fast, but if the player reaches her, will be awarded with a bonus in the score, and time left.

#### Controls:

* Keyboard Cursors: Move around the screen
* Spacebar: Use Turbo.

#### Developing 

The new part on this game, it's the running time out, and the Spacebar turbo. This brings the player an option to reach faster the map. Another one, are the queens. The direction chosen, it's random. Making the game a little more challenging.

[Link to the Game](http://gamejolt.com/games/prototype-3-peanut-delivery/134475)



### Game 4: Save the Alien 

The objective, it's try to maximize the life of the alien, bringing him medicine to the selected areas. The game will highlight some are in particular, and if the player drops the ball there, will be award with a bonus.

#### Controls
* Mouse: Drag and Drop medicines

#### Developing

This game, was not as easy as I thought it's going to be. The drag and drop mechanics were ok, but with the Overlap function in Phaser, I had a lot of problems calling functions of the code, and also, I was complicated searching in the internet about it (took me the Sunday :( ). But anyways, the basic implementations works, and the Asynchronous part will be in the next game.

[Link to the Game](http://gamejolt.com/games/protoype-4-save-the-alien/134819)



### Game 5: Monster Rock, Paper, Scissors 

This it's an endless game. The objective it play rock, paper & scissors with the other monsters that appear on the screen. You have to reach them. And also, Some bonuses will be appearing on the screen, to maintain the overall health of the player.

#### Controls

* In Platform mode:
    * Keyboard cursors: move Around. Jump with up key.
* In Battle mode:
    * Mouse: Choose rock, paper or scissors
    * Spacebar: Retire from the battle, losing 40 HP on exit.

#### Developing
This game it's the same as game 3!!, but that was my intention, because the important factor is the battle. I wanted to practice the use of Phaser stats, and also, giving more use to JavaScript object orientation.
The bonuses appear as the player received less than 60 HP down from a battle, and also if the health it's down for 50 (it's like an "final effort" of the monster). So, it had the Asynchronous factor, that depends of the life of the player. Finally, the player has the option to retire from battles. But, 40 HP will be subtracted. So, the player had a lot of tools to make an strategy.

[Link to the Game](http://gamejolt.com/games/prototype-5-monster-rps/134820)



### Other ideas

* I wanted to put a temporary pause button in "Game 4: Save the Alien", but the problem with some Phaser functions, made me to finally discard the idea temporally, as I can finally fix my knowledge with Phaser in this part.
* Also wanted to use "tiled maps" in this projects, but because of time, I didn't yet go deep with these. For future projects, It's my intention to try tiled maps, because the use of a Json file to charge them, and a external program to make the designs, will make the developing more agile.

That's all for this part of the course. See you next time!
