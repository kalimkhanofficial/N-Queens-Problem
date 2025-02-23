N-Queens Problem

A solution to the classic N-Queens problem, where the goal is to place N queens on an NxN chessboard such that no two queens attack each other.

Description
This project provides a C++ solution to the N-Queens problem using backtracking. The solution checks for safe positions to place queens on the board and recursively tries to place queens in each column.

Features
- Solves the N-Queens problem for any board size (NxN)
- Uses backtracking to efficiently find solutions
- Prints the solution board with queens represented by 'Q' and empty spaces represented by '.'

Usage
1. Compile the code using a C++ compiler (e.g., `g++`).
2. Run the compiled executable and enter the number of queens when prompted.
3. The program will display a solution board if one exists.

Code Structure
- `isSafe` function: Checks if a queen can be placed at a given position on the board.
- `solveNQueens` function: Recursively tries to place queens on the board using backtracking.
- `printBoard` function: Prints the solution board.
- `main` function: Gets user input, initializes the board, and calls the `solveNQueens` function.

Example Use Case
- Input: `Enter the number of queens: 4`
- Output:

Solution found!

. Q . .
. . . Q
Q . . .
. . Q .


To use this code in VS Code:

1. Open VS Code and create a new folder for your project.
2. Copy the code into a file named `n_queens.cpp` in your project folder.
3. Install the C/C++ extension for VS Code if you haven't already.
4. Compile the code using the `g++` compiler or another C++ compiler of your choice.
5. Run the compiled executable and enter the number of queens when prompted.

To use this code in an online compiler:

1. Copy the code into an online compiler such as Repl.it, Ideone, or Codepad.
2. Select the C++ language and compiler options.
3. Run the code and enter the number of queens when prompted.
