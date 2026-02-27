# 🧩 Sudoku Solver

A **Sudoku Solver** built using the C programming language that solves standard 9×9 Sudoku puzzles using a backtracking algorithm.

Sudoku is a logic-based number placement puzzle where each row, column, and 3×3 subgrid must contain digits from 1 to 9 without repetition. This project automatically finds a valid solution for a given incomplete Sudoku grid.

---

## 🎯 Features

- 🧠 Efficient Backtracking Algorithm
- 🔢 Solves standard 9×9 Sudoku puzzles
- ✅ Validity checking for rows, columns, and subgrids
- 🖥️ Simple terminal-based interface
- ⚡ Fast recursive solving approach

---

## 🛠️ Tech Stack

- Language: C
- Algorithm: Backtracking
- Execution: Terminal / Console
- Compiler: GCC

---

## 📂 Project Structure

Sudoku-Solver/
│
├── SudokuSolver.c
└── README.md

---

## 🚀 How to Run the Project

1. Clone the repository:

   git clone https://github.com/dipanshu-kashyap00/Sudoku-Solver.git

2. Move to the project directory:

   cd Sudoku-Solver

3. Compile the program:

   gcc SudokuSolver.c -o SudokuSolver

4. Run the program:

   ./SudokuSolver

---

## 📌 How It Works

- The Sudoku grid is represented using a 2D array.
- Empty cells are represented using 0.
- The solver scans the grid to find empty cells.
- For each empty cell, it tries numbers from 1 to 9.
- It checks whether placing a number is valid:
  - No repetition in the same row
  - No repetition in the same column
  - No repetition in the 3×3 subgrid
- If valid, the number is placed and the function continues recursively.
- If no number fits, the algorithm backtracks and tries a different value.

This process continues until the puzzle is completely solved.

---

## ⚠️ Important Notes

- Works for standard 9×9 Sudoku puzzles only.
- Assumes that the puzzle has at least one valid solution.
- Runs completely in the terminal.
- No external libraries required.

---

## 🎯 Learning Outcomes

This project helps in understanding:

- Recursive programming
- Backtracking algorithms
- 2D array manipulation
- Constraint validation logic
- Problem-solving using structured programming in C

---

## 👨‍💻 Author

Dipanshu Kashyap  
GitHub: https://github.com/dipanshu-kashyap00

---

## 📄 License

This project is open-source and free to use for learning purposes.
