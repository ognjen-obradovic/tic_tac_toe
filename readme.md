# Tic-Tac-Toe Game in Python

## Description

This is a simple command-line Tic-Tac-Toe game written in Python. The game allows two players to take turns and place their symbols (either "X" or "O") on a 3x3 board. The game ends when one player wins by aligning three of their symbols in a row, column, or diagonal, or when the board is filled with no winner (a draw).

## How to Play

1. The game is played on a 3x3 grid.
2. Player X starts first, followed by Player O.
3. Players take turns choosing a position on the board, numbered from 1 to 9.
4. To make a move, enter the number corresponding to the desired position on the board. If the move is valid, it will be recorded; otherwise, an error message will prompt the player to choose again.
5. The game ends with one of the following outcomes:

- A player wins by completing a row, column, or diagonal.
- The board is filled, resulting in a draw.

## Features

- **Two-player mode**: Allows two players to play against each other in turns.
- **Winner Detection**: Detects when a player has aligned three of their symbols.
- **Draw Detection**: Identifies when the board is full with no winner.
- **Input Validation**: Ensures players enter valid moves.

## Code Structure

- `prikazi_tablu(tabla)`: Displays the current state of the board.
- `proveri_pobednika(tabla, igrac)`: Checks if the current player has won.
- `tabla_puna(tabla)`: Checks if the board is full.
- `tic_tac_toe()`: Runs the main game loop.

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.

### How to Run

1. Clone this repository.
2. Open a terminal and navigate to the project directory.
3. Run the game with the following command:

```bash
python tic_tac_toe.py
```
