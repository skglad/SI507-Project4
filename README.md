<h2>Brick Breaker Type Game</h2>

I have created a brick breaker type game from the pong game code that we used in class.
Some changes I made to the game include:

* created a wall of 6 x 11 bricks
* moved the started point of the ball to the lower left-hand corner of the game and changed the angle so it initially moves towards the wall
* removed one paddle so that the game is a one person game
* changed the left-hand wall so it deflects the ball

According to the tasks set out for us in project 4, I have changed some of the features of the game as well:

* the bricks from the wall will be removed when they are hit
* the ball will increase it's speed every 10th brick that is hit

The creative feature that I've added is:

* every time the left-hand wall is hit, the velocity of the ball increases (but not as much as if the ball hits 10 bricks)
* if the left-hand wall is hit 3 times, then the game will end

<h2>Running The Game</h2>

To run this game you will to clone or download the files in this repo to a directory on your computer.
You will then go to your terminal and navigate to that directory. When you are in the directory with the program file you will enter into the terminal:

python3 basepong_2.py

This will initialize the window and start the game.

<h2>playing the Game</h2>
To play the game, you will need to move the paddle up and down in order to block the ball from hitting the end wall so that the ball can remove all of the bricks.

To move the paddle up, you press the "w" button your keyboard.
To move the paddle down, you press the "s" button your keyboard.
To pause the game, press the "p" button on your keyboard (to unpause press "p" again)
To exit the game, press "q" or "escape" on your keyboard.

The goal is to keep the ball from hitting the side wall 3 times, while removing all of the bricks from the wall. If you hit the left-side wall 3 times, the game will quit and you will lose. 
