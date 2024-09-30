# Tic-Tac-Toe Game in Java

This is a simple command-line Tic-Tac-Toe game implemented in Java. Two players can play this game by taking turns.

## Features

- Two-player mode (Player X vs Player O)
- 3x3 grid for the game board
- Simple input for moves
- Detects win conditions (rows, columns, and diagonals)
- Draw detection when the board is full

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Yashapradha/Tic-Tac-Toe-game-using-Java.git
   ```

2. Navigate to the project directory:
   ```bash
   cd tic-tac-toe-java
   ```

3. Compile the Java file:
   ```bash
   javac TicTacToe.java
   ```

4. Run the game:
   ```bash
   java TicTacToe
   ```

## Game Instructions

1. The game board is a 3x3 grid.
2. Players take turns. Player X always goes first.
3. On your turn, enter the row and column number (from 1 to 3) where you want to place your marker.
4. The first player to get three markers in a row (horizontally, vertically, or diagonally) wins the game.
5. If all spaces are filled without a winner, the game will result in a draw.

## Example

```
Current Board:
- - - 
- - - 
- - - 
Player X, enter your move (row and column): 1 1

Current Board:
X - - 
- - - 
- - - 
Player O, enter your move (row and column): 2 2

Current Board:
X - - 
- O - 
- - - 
...
```
