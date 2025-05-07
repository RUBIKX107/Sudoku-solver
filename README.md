

# Sudoku CSP Solver

A Sudoku puzzle solver built using **Constraint Satisfaction Problem (CSP)** techniques in Python.

This project is part of my AI learning journey, inspired by the [CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2020/).

## Features

- Solves standard 9x9 Sudoku puzzles
- Uses **backtracking search** with **constraint propagation**
- Easily customizable Sudoku boards
- Includes examples of solvable puzzles and solutions

## Technologies

- Python 3
- Logic-based AI (CSP)
- No external libraries required

## How it works

The solver treats each blank cell as a variable with a domain of possible numbers (1-9). It applies constraints (row, column, box) and uses inference to narrow possibilities, solving the puzzle efficiently.

## Try It

You can test different boards by editing the puzzle in `sudoku.py`:

```python
board = [
    [0, 0, 3, 0, 2, 0, 6, 0, 0],
    [9, 0, 0, 3, 0, 5, 0, 0, 1],
    ...
]

