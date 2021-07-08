## JS Racer

Vroom vroom! Let's play! Write a simple game called JS Racer. The rules are simple: roll the dice and move forward. There is no strategy or decision making, just hope for luck and [Math.random()] (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)!

A game is a race between two players. Both players start at the beginning of the track, side by side. The players take turns rolling the dice and advance along the track **by one step**, depending on the numbers on the dice, and do this until one of them reaches the end of the track and wins the duel.

However, in the process of creating our game, some difficulties may arise:
1. Management of the state of the game (for example, tracking players' positions)
2. Converting data from one structure to another (for example, converting game data to a printed board).

Below is the console game version. If you want, you can make it with a web interface to play in a browser.

![](readme-assets/JSracer.gif)

### Release 0. Create a minimalistic version of the game 

You need to create a working version of *JS Racer*. What does it mean? It begins, and 2 cars should somehow move in the game. When one of them reaches the finish line, the user is informed about this, and then the game ends.
In fact, the task is not as simple as it seems! We recommend that you study the `setTimeout ()` and `setInterval ()` functions very carefully. These 2 functions work quite interestingly. Here you will smoothly begin your acquaintance with the concept of `Asynchrony`.

### Release 1. More features needed *(optional)*

What would make this game more fun? Now that the basic version of the game is working, let's see if we can improve it a bit? Below are some suggestions for improvement, but you can add your own features as well.

- Why limit the game to two players, always called `a` and` b`? Allow any number of players to take part in the race and choose their own name symbols.
- Instead of using one letter characters for each player, you can use [ASCII] art (https://sites.google.com/site/asciisandbox/art/vehicles), [word conversion] (https://github.com/miketierney / artii)).
- You can make the game more like "Chutes and Ladders", providing players with unexpected bonuses in the form of acceleration of the car, accidental reversing, accidents that force you to skip turns.
- You can reduce the amount of randomness in the game, giving players more control over how they move in all directions.
