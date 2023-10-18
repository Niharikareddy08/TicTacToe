# TicTacToe
Tic-Tac-Toe Game in Java
This is a simple command-line implementation of the classic Tic-Tac-Toe game in Java. Two players can take turns marking 'X' and 'O' on the 3x3 game board until there is a winner or a draw.

How to Play
Clone or download the Java code to your local machine.

Compile the code using a Java development environment or command line:

shell
Copy code
javac TicTacToe.java
Run the game:

shell
Copy code
java TicTacToe
The game board will be displayed with empty cells, and Player 'X' will start.

Follow the on-screen prompts to enter your moves. Specify the row (0, 1, 2) and column (0, 1, 2) where you want to place your mark.

The game continues until there is a winner or a draw. The program will display the result and exit.

Game Rules
Players take turns marking cells with 'X' and 'O.'
The game is won when a player has three of their marks in a row, column, or diagonal.
If all cells on the board are filled, and there is no winner, the game ends in a draw.
Enjoy playing this classic game of Tic-Tac-Toe in the terminal!

It looks like you've implemented a basic command-line version of the Tic-Tac-Toe game in Java. This code defines a 3x3 board and allows two players to take turns marking 'X' and 'O' on the board until there's a winner or a draw. Here's a breakdown of the code:

1. The `TicTacToe` class is defined with a 3x3 game board (`board`) and the current player (`currentPlayer`) initially set to 'X'.

2. The `main` method is the entry point of the game. It initializes the board, prints the board, and enters a loop to manage the game flow.

3. The `initializeBoard` method sets all elements of the board to spaces (' ') to represent an empty board.

4. The `printBoard` method prints the current state of the game board in a simple format.

5. The `getPlayerMove` method allows the current player to enter their move by specifying the row and column where they want to place their mark. It checks for valid input and ensures that the selected cell is empty.

6. The `isValidMove` method checks if the specified row and column are within the valid range and if the cell is empty.

7. The `makeMove` method updates the game board by placing the current player's mark ('X' or 'O') in the specified row and column.

8. The `checkWin` method checks for a win condition by examining rows, columns, and diagonals on the board. If a player has won, it returns `true`.

9. The `isBoardFull` method checks if the board is completely filled with player marks. If it is full, and there is no winner, it returns `true`, indicating a draw.

10. The game loop in the `main` method takes turns between players, checks for wins or a draw, and prints the appropriate message when the game ends.

The code seems to work as expected for a simple text-based Tic-Tac-Toe game. You can run it in a Java development environment to play the game.
