# Snake Game

## Overview

A classic Snake Game implemented in Java using Swing for graphical user interface and array data structures to manage game state and rendering. The game allows players to control a snake to eat apples and grow while avoiding collisions with the walls and itself.

## Features

- **Game Mechanics**: 
  - **Movement**: Arrow keys control the direction of the snake (left, right, up, down).
  - **Apple Generation**: Apples appear at random positions, and the snake grows when an apple is eaten.
  - **Collision Detection**: Detects collisions with the snake itself, walls, and handles game over conditions.

- **Graphics and User Interface**:
  - **Custom Images**: Utilizes custom images for the snake’s head, body, and apples.
  - **Game Screen**: Provides a visual representation of the game board with real-time updates of the snake's position and apple location.

- **Timer Integration**:
  - **Game Loop**: Uses a `Timer` to regularly update the game state and repaint the screen, ensuring smooth gameplay.

## Technologies Used

- **Java**: Programming language used to implement the game logic and user interface.
- **Swing**: Java library used for creating the graphical user interface.
- **AWT**: Used for handling graphics and user input.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Harsh1106/SnakeGame
