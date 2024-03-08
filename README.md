TicTacToe game:

TicTacToe Game Documentation
Overview
TicTacToe is a simple console-based game implemented in Java. It allows two players to take turns marking spaces in a 3x3 grid to achieve a winning pattern.

Features
Human vs. Human: Two human players can play against each other.
Human vs. Computer: A human player can play against the computer.
Dynamic Grid: The game board is represented as a 3x3 grid.
Winner Detection: The game detects when a player achieves a winning pattern.
Draw Detection: The game detects when the grid is filled without a winner, resulting in a draw.
Classes
TicTacToe
Main class: Contains the main method to start the game.
Static variables:
board: 2D array representing the game board.
currentPlayer: Character representing the current player ('X' or 'O').
isComputerPlayer: Boolean indicating whether the second player is a computer.
Methods:
main(String[] args): Entry point of the game.
printBoard(): Prints the current state of the game board.
makeHumanMove(Scanner scanner): Allows the human player to make a move.
makeComputerMove(): Allows the computer player to make a move.
isValidMove(int row, int col): Checks if a move is valid.
checkWinner(): Checks if a player has achieved a winning pattern.
isBoardFull(): Checks if the game board is full, resulting in a draw.
Usage
Run the TicTacToe class.
Follow the on-screen prompts to select game options and make moves.
Play until a player wins or the game ends in a draw.
Examples
Human vs. Human: Players take turns entering row and column coordinates to make moves.
Human vs. Computer: Player enters moves, and the computer randomly selects valid moves.
Dependencies
java.util.Scanner: Used for user input.
java.util.Random: Used for generating random moves for the computer player.
Notes
The game does not implement advanced AI for the computer player.
The game ends when a player wins or the grid is full, regardless of the game configuration.
