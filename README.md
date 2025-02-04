2048 Game in Python (Pygame)
Overview

This is a Python implementation of the popular 2048 game using the Pygame library. The objective of the game is to combine tiles with the same value by moving them in one of four directions (left, right, up, or down) to ultimately create a tile with the number 2048.
Features

    Smooth tile animations
    Random tile generation
    Dynamic color changes based on tile values
    Game over detection
    Restart on game over

Requirements

Before running the game, ensure you have Python and Pygame installed.
Installation:

    Install Python (if not already installed):
        Download it from python.org.
    Install Pygame using pip:

    pip install pygame

How to Run

    Download or clone this repository.
    Navigate to the project directory.
    Run the following command:

    python game.py

    (Assuming you have saved the script as game.py)

Controls

    Arrow Keys: Move the tiles
    Esc / Close Button: Exit the game

Game Rules

    At the start, two tiles (either 2 or 4) appear at random positions on a 4x4 grid.
    Pressing an arrow key moves all tiles in that direction.
    Tiles with the same number merge when they collide, forming a new tile with double the value.
    The goal is to reach the 2048 tile (or continue beyond it for a high score).
    If the grid is full and no moves are possible, the game ends.

License

This project is open-source and free to use.
