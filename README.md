# AIM TRAINER

A simple and engaging aim training game developed using Pygame. The game dynamically generates targets that grow and shrink, challenging players to click on them before they disappear. The game tracks and displays performance metrics such as speed, accuracy, hits, and remaining lives.

## Features

- **Dynamic Target Generation**: Targets appear at random positions and change size over time.
- **Real-time Performance Tracking**: Displays metrics including speed (targets per second), accuracy, hits, and remaining lives.
- **User-Friendly Interface**: Clean and intuitive design with real-time updates on player performance.
- **Smooth Animations**: Targets smoothly grow and shrink, providing a visually appealing experience.

## Requirements

- Python 3.x
- Pygame

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/aim-trainer.git
   cd aim-trainer
   ```

2. Install the required packages:
   ```bash
   pip install pygame
   ```

## Usage

1. Run the game:
   ```bash
   python aim_trainer.py
   ```

2. Click on the targets as they appear to increase your score. Avoid missing too many targets to keep the game going.

## Game Controls

- **Mouse Click**: Click on the targets to score points.
- **Quit**: Close the window or press any key on the end screen to exit the game.

## Code Overview

- **main()**: The main game loop handling events, target updates, and rendering.
- **Target Class**: Defines target properties, updates, drawing, and collision detection.
- **Helper Functions**: Functions for drawing the interface, formatting time, and displaying the end screen.

## Acknowledgements

- Developed using Pygame.
- Inspired by aim training games for FPS games.

---

Feel free to contribute by opening issues or submitting pull requests!

Enjoy playing and improving your aim! 🎯

