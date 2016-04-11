---
layout: post
title:  "Using Analytics"
date:   2016-04-11 12:11:20 -0300
---

The last week, now in the course, I have two objectives to accomplish:

* Analytics on the game, to see what the user are doing
* Implement a "Compulsion loop", to make the game more attractive

My main focus therefore, was the first point: Implement analytics in my game. And for the second objective, I think that I had to do a little improvements to the game. I will go objective from objective:

### Implementing Analytics

The main and important factor this week, was finding an effective analytics tool for the game. I never before use them with so many detail, only used google analytics to see a website traffic. So, I spent two days to decide the analytics tool to use. I tried using Flurry, the Game Jolt api, and Google Analytics.

Flurry looks interesting, but for the reason that I didn't work for me in a day, I discarded it.
Next, the Game Jolt Api. It works well, but the problem is that only recollect analytics from the registered users in the platform. For casuals players, the API doesn't work for what I want. But it have some interesting things, like Trophies for the player, that can generate some satisfaction in the gameplay.
Finally, Google Analytics. First, like Flurry, I don't wanted to use the tool, because I cannot see in real time the results. But the next day, I saw in the page, that the Analytics where there!. So, the refresh rate is 1 day.

And after all, I stayed with google analytics, for the simple factor that I have a account, and also had the feature to use custom analytics (But it requires some previous learning of how it works).

I used the "event" tracking tool per sessions, because it was the more easy to use feature in the moment. The elements that I choose to track per session are the following:

* Enemies Kills (Kill)
* Item Spawn (Spawn)
* Item Picks (Pick)
* Damages more than 0.6 of the total (Damage)
* Game Sessions (Session)
* Game time per session, duration of an average session (the classic variable of web analytics)

For this game version, they are going to be the variables. In a future release, more variables are going to be inserted.

The objective of using these variables are:

* See how much the player plays the game
* See the behaviour of the player during the session. That's why the previous events are tracked. This is information to get a better game experience.
* Finally, see how Google Analytics works, and learn more about how to use the features of the tool, to get the best results.


### Compulsion loop

This part wasn't really my main point this week, because I think that to implement better compulsion loops, have analytics in the game it's a must have. The thing that I did to make a compulsion game, are the following:

* A "Critical!" text box, that is displayed, when the player makes a critical hit. That means, when the player attacks with the strongest type, and the opponent uses the weakness to the player attack, the player makes an critical hit.
The objective of this, is that the player sees that made a critical  hit. So, will learn that using certain element, to a cretin type of enemy, the player will maximize the damage done to the enemy. This also means, that more bonus can be spawned in the game, and meaning that the player improves play after play.

Also, the player is going to discover, that killing enemies will spawn more items in the map, like bullets or health bonus, that are going to make better scores.

When I research more about other examples of the Compulsion Loop, I'm going to implement more factors to the gameplay. Also to make the game more attractive to the audience. For the next week, there are some ideas to implement to the game (if them are possible):

* Optional boss battle
* Bonus, that it's going to make enemies use only one type of attack. Also, the enemies are going to change their color.
* A larger map, and objectives (are going to appear when the player advances through the game).


