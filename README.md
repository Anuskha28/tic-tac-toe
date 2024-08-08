# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game implemented in C++. It allows a player to play against the computer.

## Description

The game is played on a 3x3 board. The player is assigned the 'X' marker, and the computer is assigned the 'O' marker. The player and the computer take turns to place their markers on the board. The game continues until either the player or the computer wins, or the board is full resulting in a tie.

## How to Play

1. The game starts by displaying an empty 3x3 board.
2. The player is prompted to enter a spot number (1-9) to place their marker.
3. After the player makes a move, the board is updated and displayed.
4. The computer then makes a random move.
5. Steps 2-4 repeat until there is a winner or a tie.

## Winning Conditions

A player wins if they can place three of their markers in a row, column, or diagonal. The game will announce the winner and end. If the board is full and there is no winner, the game will announce a tie.

## Files

- `tic_tac_toe.cpp`: The main C++ source file containing the game logic.

## Functions

### `void drawBoard(char *spaces)`

Draws the current state of the game board.

### `void playerMove(char *spaces, char player)`

Prompts the player to enter a move and updates the board.

### `void computerMove(char *spaces, char computer)`

Generates a random move for the computer and updates the board.

### `bool checkWinner(char *spaces, char player, char computer)`

Checks if there is a winner and prints the winner.

### `bool checkTie(char *spaces)`

Checks if the game is a tie.

## Getting Started

### Prerequisites

- C++ compiler (e.g., g++)

### Compilation

Compile the `tic_tac_toe.cpp` file using a C++ compiler:

```sh
g++ tic_tac_toe.cpp -o tic_tac_toe
