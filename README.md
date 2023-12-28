# Snake Game README

This repository contains a simple Snake Game implemented using HTML, CSS, and JavaScript. The game is played on a grid, and the player controls the snake's movement using arrow keys or on-screen buttons.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Game Controls](#game-controls)
- [Scoring](#scoring)
- [Game Over](#game-over)
- [Responsive Design](#responsive-design)

## Features

- Responsive grid-based game layout.
- Snake movement controlled by arrow keys or on-screen buttons.
- Dynamic generation of food for the snake.
- Score tracking and display.
- Game over conditions and reset functionality.

## Usage

1. Clone the repository to your local machine.
   ```bash
   git clone <repository-url>
   ```

2. Open the `index.html` file in a web browser to play the Snake Game.

## Game Controls

### Keyboard Controls
- **Arrow Up:** Move the snake upward.
- **Arrow Down:** Move the snake downward.
- **Arrow Left:** Move the snake to the left.
- **Arrow Right:** Move the snake to the right.

### On-Screen Controls
On-screen arrow buttons are provided for mobile or touch devices.

## Scoring

- The player earns 10 points each time the snake consumes the food.

## Game Over

The game ends under the following conditions:
- The snake collides with the game boundaries.
- The snake collides with its own body.

When the game is over, an alert is displayed, and the player's score is reset. The player can restart the game by refreshing the page.

## Responsive Design

The game layout is responsive, adapting to different screen sizes. On smaller screens, on-screen arrow buttons are displayed for ease of control.
