# Flexible-Tic-Tac-Toe-Challenge

This is a simple command-line implementation of the classic game Tic Tac Toe in C. The game is played by a single player against a computer opponent.

# How to Play

1 - Download and compile the source code using a C compiler, such as GCC.<br>
2 - Run the executable to start the game.<br>
3 - The game will prompt the player to enter their move by specifying the row and column of the board they wish to place their marker in.<br>
4 - The computer will make its move immediately after the player.<br>
5 - The game will continue until one player wins, the game ends in a tie, or the player chooses to quit.<br>
6 - The player can choose to play again after the game ends.<br>

# Features

<li>The game board is displayed in the console, and markers are represented by X's and O's.</li><br>
<li>The computer AI randomly selects an empty space on the board to make its move.</li><br>
<li>The game can be played multiple times without restarting the program.</li><br>
<li>The player can quit the game at any time by entering 'N' when prompted to play again.</li><br>

# Code
The source code is written in C and contains the following functions:

```c
 resetBoard() Initializes the game board with empty spaces.
```
```c
printBoard(): Prints the current state of the game board to the console.
```
```c
checkFreeSpaces(): Counts the number of empty spaces remaining on the board.
```
```c
playerMove(): Prompts the player to enter their move and places their marker on the board if the space is empty.
```
```c
computerMove(): Selects a random empty space on the board and places the computer's marker.
```
```c
checkWinner(): Checks if either player has won the game by examining the rows, columns, and diagonals of the board.
```
```c
printWinner(char): Prints a message to the console indicating the winner of the game or a tie.
```

# Contributing

If you would like to contribute to this project, feel free to create a pull request.
