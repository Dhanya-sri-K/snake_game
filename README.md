
# Snake Game Using Jack

This repository contains the implementation of the classic Snake Game developed using the Jack programming language.

## Project Overview

The Snake Game demonstrates core principles of game development using Jack, targeting the Hack computer platform as defined in the Nand2Tetris course. It involves real-time rendering, user input handling, game state management, and procedural logic to simulate a dynamic, playable game environment.

The game runs on the Hack platform via the supplied virtual machine emulator and provides an engaging experience with features such as score tracking, level progression, and interactive gameplay.

## Features

- Snake movement controlled via keyboard input
- Real-time score tracking and level progression
- Randomized food generation
- Pause and resume functionality
- Scoreboard display upon game over
- Modular design using six separate Jack files for better maintainability

## Project Structure

The project consists of the following core files:

| File Name         | Description |
|-------------------|-------------|
| Main.jack         | Initializes and launches the game loop |
| Random.jack       | Implements a pseudo-random number generator |
| RandSeed.jack     | Handles the seeding of the random number generator based on user key press |
| Snake.jack        | Manages the snake’s position, growth, and movement |
| SnakeGrid.jack    | Manages the grid, including food placement and grid updates |
| SnakeGame.jack    | Combines all components to manage game logic, scoring, levels, and pause functionality |

## How to Run

1. Load all .jack files into the Jack compiler to generate corresponding .vm files.
2. Use the supplied virtual machine emulator from the Nand2Tetris toolset to run the game.
3. Follow on-screen instructions:
   - Press any key to start the game
   - Use arrow keys to control the snake
   - Press 'P' to pause and resume the game

The game ends when the snake collides with the border, at which point a scoreboard is displayed.

## Results and Performance

The game runs smoothly on the Hack platform, with no visible performance issues. The gameplay becomes progressively more challenging as the snake grows, and the speed increases with each level.

## Future Work

Planned improvements include:
- Introducing obstacles within the grid
- Adding life-based gameplay allowing restart after collisions
- Implementing power-ups to modify gameplay dynamics


## References

- https://github.com/SeaRbSg/nand2tetris
- https://github.com/wendyyuchensun/snakeGame
- https://github.com/RakovBogdan/Snake
