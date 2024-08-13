Sudoku Solver

Overview

This project is a simple Sudoku solver implemented in Java. It uses a backtracking algorithm to solve the puzzle, which is a common approach for constraint satisfaction problems like Sudoku.

The solver works for a standard 9x9 Sudoku puzzle, but the implementation is designed to be easy to adapt for other sizes if needed.

Features

* Solves standard 9x9 Sudoku puzzles.
* Uses backtracking to find the solution.
* Displays the solved Sudoku board in the console.
  
Usage

Prerequisites

To run this Sudoku solver, you need:

* Java Development Kit (JDK) installed on your machine.
* A Java IDE or a text editor to edit the code (optional).
  
Code Explanation

* main Method: Initializes a Sudoku board with some pre-filled values and calls the solve method to solve the puzzle. If the puzzle is solved, it displays the board; otherwise, it prints "Cannot solve."

* solve Method: Implements the backtracking algorithm to find the solution. It searches for empty cells, tries all possible numbers, and recursively tries to solve the puzzle. If no number fits, it backtracks to try other possibilities.

* isSafe Method: Checks whether placing a specific number in a given cell is valid. It ensures that the number does not already exist in the same row, column, or 3x3 subgrid.

* display Method: Prints the Sudoku board to the console in a readable format.

Output

If the Sudoku puzzle is solvable, the program will print the solved board in the console.

If the puzzle cannot be solved, it will print "Cannot solve".
