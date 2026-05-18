# Sudoku & Eight Queens Solver 🧩

Solving two classic **Constraint Satisfaction Problems (CSP)** using Python's 
`constraint` library with backtracking search.

## Problems Solved

### 1. Sudoku Solver
- Models a 9×9 Sudoku board as a CSP
- 81 variables (one per cell), domain 1–9
- Constraints: no repeating values in each row, column, and 3×3 box
- Solves any valid Sudoku puzzle instantly

### 2. Eight Queens Puzzle
- Places 8 queens on an 8×8 chessboard
- 8 variables (one per row), domain 0–7 (columns)
- Constraints: no two queens share the same column or diagonal
- Visualizes solution using the `chess` module

## Tech Stack
- Python
- `python-constraint` — CSP solver with backtracking
- `sudoku` — Sudoku board generator
- `chess` — Chessboard visualization
- `numpy`
- Jupyter Notebook

## How to Run

```bash
pip install python-constraint sudoku chess numpy
jupyter notebook Solution.ipynb
```

## Key Concepts
- **CSP Modeling** — variables, domains, constraints
- **AllDifferentConstraint** — ensures unique values per group
- **Backtracking Search** — automatically handled by the constraint library

## Sample Output

**Sudoku:**
