---
layout: post
title:  "Next Step: Improving games"
date:   2016-04-01 16:32:20 -0300
---

![alt tag](https://p5b4y2t6.ssl.hwcdn.net/game-thumbnail/300/138566-crop8_160_596_491-a4kthuxi.jpg)

[Link of the game](http://gamejolt.com/games/element-rampage/138566)

This week, I published my games to be public past Monday (because I didn't do that before). Set a deadline until March 31, to see who games are going to be improved. The results are the following:

- Game 1 First place, Game 2 Second, and Game 5 third.

So, it's clear that the first prototype it's winning. But considering the following human factors, that everyone do in their daily life, could influence the result:

- Prototype 1 its winning because I posted to Facebook to play the games. As a person, I have the tendency to open always the first link provide in the post. So because of that, game 1 it's the most visited and played.
- The others, should have a similar behaviour. So, game 3 should be the less visited and played. But, it has more view than the prototype 3 and 4, so it could be a little more successful.

As the developer, I had to choose one of the games to do the improvements. As a personal preference, I want to choose the 5th game, but because of the visits and plays, it should be the first.

So, I choose to improve some features of the first and fifth game, and combine the two games into a new game. It will have the following improvements.

### Game ideas

- Better behaviour of the opponents, now they can have different probabilities of choosing rock, paper or scissors.
    - In this thing, I changed the system of the "rock paper scissors", into a "element battle". Instead of three options, now the player has to choose between "fire, water of leaf". Fire defeats Leaf, but has weakness versus water..., and so on. This change of gameplay, that follows the system of rock paper scissors, reduces the friction between the player and the game, adding more dynamics.
- 2d movement, and remove the platformer. So, it's going to have movement around the space, like in game 1.
    - In compassion to the prototype one, I done some important fixes. The diagonal movement, now is at the same speed as the strictly directions. Before, the values of the x and y axis, were summed. So, the magnitude of the velocity, now it's the same. So, the player now, don't have that privilege. And the other part, now the bullets are not infinite. The player starts with 3 bullets, and to win more bullets, the player has to deal a certain amount of damage to unlock the bonus.
- Better design, and sounds:
    - Now, compared to the previous games, now the game has more "understable" sprites. The color of the player, and the enemy, represents the primary element (it defines the armor of the objective). So, the player has to guess, what means the mix of colours, and do a strategy with this signals.

Now, the game consists of the following:

- First, the player has to create a character. Has to choose between three element, one Primary, and one Secondary. The Primary, is going to define a type of attack, and also (and important), the type of armor that it's going to have. That is, because depending of this factor, the player will have an advantage, or weakness versus certain types of enemies.
- Next, the game starts. The player will see five enemies in all the map. These enemies, are going to move around the map, but they'll not follow the player to attack him (not yet, but it's going to be implemented). To win score, and going forward in the game, the player has to defeat the more possible number of enemies in the map.
- The bonuses (health and bullet), are going to display in a random part of the map. The player has to get these times, to survive more in the game.

### Using game design tools and frameworks

The idea of the session, it's to now use a framework, to determinate the gameplay and aspect that are going to be implemented. This tool, it's used to define elements like the player feelings, the behaviour and goals of enemies, and more things in the way. I'm going to use two frameworks, that are described in the following article of Gamasutra [(Link)](http://www.gamasutra.com/view/feature/187777/game_design_tools_for_collaboration.php?print=1).

#### Token Based Model

The idea, is to define the game fundamental elements as tokens. There are described in a matrix, where the cell represent the interaction. The X are obviously, no action. In the Element Rampage game, this it's the matrix:

![alt_tag](https://dl.dropboxusercontent.com/u/50497061/img1.png)
![alt_tag](https://dl.dropboxusercontent.com/u/50497061/img3.png)


#### Game Layers

The difference with the previous one, is now decompose the game into layers. This add other points of view to the game, like the gamer feelings, emphasis on goals, and more. This is the model used in the game:

![alt_tag](https://dl.dropboxusercontent.com/u/50497061/img2.png)

### Conclusion

The new game, look more like a playable game than the others, because now have more dynamics in the gameplay. Therefore, some implementations are still missing, but with the video game course running during the weeks, I'm going to put more of them.
The framework are a great idea to discover the topic of the game that can be missing. With the second one (Game Layers), I realize that part of the "player feeling" it's not clearly defined. So, in the next "developing sessions", this elements are going to be covered more in depth.


[Link of the game](http://gamejolt.com/games/element-rampage/138566)

