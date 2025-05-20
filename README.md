# Tic-Tac-Toe Game

This is a simple command-line Tic-Tac-Toe game implemented in Python.

**Author: SURYADIP BERA**

## Description

This project is a basic implementation of the classic Tic-Tac-Toe game played in the command line. The computer plays as 'X' and always starts by placing its first move in the center of the board. The user plays as 'O' and inputs their moves by selecting a numbered square on the board. The game checks for wins, ties, and valid moves, and the computer makes random moves without any AI strategy. This simple game demonstrates basic Python programming concepts such as input validation, game state management, and random choice.

## Features

- The computer plays as 'X' and always makes the first move by placing 'X' in the middle of the board.
- The user plays as 'O' and inputs their moves by entering the number of the square they want to occupy.
- The board squares are numbered 1 to 9, row-wise:
  ```
   1 | 2 | 3
  ---+---+---
   4 | 5 | 6
  ---+---+---
   7 | 8 | 9
  ```
- The program validates user input to ensure it is a valid, unoccupied square.
- The game checks for wins, ties, and continues accordingly.
- The computer makes random valid moves (no AI).

## How to Run

1. Make sure you have Python 3 installed on your system.
2. Run the game by executing the following command in your terminal or command prompt:
   ```
   python tic_tac_toe.py
   ```
3. Follow the on-screen instructions to play the game.

## Gameplay

- The computer always starts by placing an 'X' in the middle square.
- You will be prompted to enter your move by typing a number between 1 and 9 corresponding to the board position.
- The game will alternate turns until there is a winner or a tie.
- The program will announce the result at the end.

## License

This project is provided as-is for educational purposes.
