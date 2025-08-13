Sudoku Solver 

This is a simple Java program that solves any standard 9×9 Sudoku puzzle using a backtracking algorithm.
The puzzle is hardcoded in the code (0 represents empty cells), and the program fills in the blanks to produce a valid solution.

📌 Features
Solves any valid Sudoku puzzle using backtracking.

Displays the puzzle in a neat, readable format.

Prints the solution in the console.

Works entirely offline — no external libraries needed.

🖥️ How It Works
The Sudoku puzzle is stored in a 2D integer array.

0 represents an empty cell.

The program tries numbers 1 to 9 in each empty spot.

For each number, it checks if placing it is valid (row, column, and 3×3 box check).

If valid, it proceeds; otherwise, it backtracks until the puzzle is solved.

📂 Code Structure
solve() → The recursive backtracking function that fills the board.

isValid() → Checks if a number can be placed in a given cell.

printBoard() → Prints the Sudoku board in a clean format.

▶️ How to Run
Save the code in a file named SudokuSolver.java.

Compile the program:

bash
Copy
Edit
javac SudokuSolver.java
Run it:

bash
Copy
Edit
java SudokuSolver
