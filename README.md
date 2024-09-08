# Connect Four Game

This is a Python implementation of the classic **Connect Four** game using the Pygame library for graphics and NumPy for managing the game board.

## Game Overview

The game allows two players to take turns to drop colored discs into a grid. The goal is to be the first player to form a horizontal, vertical, or diagonal line of four discs of their own color.

- Player 1 discs are red.
- Player 2 discs are yellow.

The game ends when either player manages to connect four of their pieces in a row, or if the board becomes full without any player winning (in which case it is a draw).

## Features

- **Graphical Interface**: The game uses Pygame to draw the grid and pieces, and to handle mouse input.
- **Two Players**: The game alternates turns between Player 1 and Player 2.
- **Win Detection**: The game checks for horizontal, vertical, and diagonal wins.
- **Smooth Animations**: Player moves are updated visually in real-time.

## Installation

### Prerequisites

Make sure you have Python installed on your system (version 3.7+ is recommended). You also need to install the following libraries:

- `pygame`: For handling game graphics and user inputs.
- `numpy`: For managing the game board.

You can install the dependencies using pip:

```bash
pip install pygame numpy
