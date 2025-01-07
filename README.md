# Breakout Game

This is a simple Breakout-style game built using HTML5 `<canvas>` and JavaScript. The goal of the game is to destroy all the bricks by bouncing the ball off a paddle. The game increases in difficulty as you clear more bricks, and if the ball touches the bottom of the screen, the game is over.

## Features

- **Ball**: The ball bounces off the walls, paddle, and bricks.
- **Paddle**: Controlled by arrow keys to move left and right.
- **Bricks**: A set of bricks that need to be destroyed by hitting them with the ball.
- **Score**: Tracks how many bricks you've destroyed.
- **Game Over**: When the ball touches the bottom of the screen, the game is over.

## How to Play

1. Use the **left** and **right arrow keys** to move the paddle.
2. Destroy all the bricks by bouncing the ball off the paddle.
3. When you destroy all bricks, they will reset, and the ball speed will increase.
4. If the ball touches the bottom, the game resets.

## Requirements

This game uses HTML5 and JavaScript, so all you need is a modern web browser with support for the `<canvas>` element.

## Running the Game

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser to start playing.

```bash
git clone https://github.com/yourusername/breakout-game.git
cd breakout-game
open index.html
