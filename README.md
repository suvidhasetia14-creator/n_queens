# N-Queens Problem Solver

## Description
The N-Queens Problem is a classic chess and computer science problem where the objective is to place *N queens* on an *N × N chessboard* such that no two queens attack each other.

Since a queen can move horizontally, vertically, and diagonally, the challenge is to find a valid arrangement where every queen is safe from the others.

This project implements a solution using the *Backtracking Algorithm*, a recursive approach that efficiently explores possible queen placements and backtracks whenever a conflict occurs.


## Objectives
- Solve the N-Queens problem for a given board size.
- Demonstrate the use of recursion and backtracking.
- Understand constraint satisfaction problems.
- Improve problem-solving and algorithmic thinking skills.

## Technologies Used
- Python 3.13
- Backtracking Algorithm
- Recursion

## How the Algorithm Works
1. Place a queen in the first row.
2. Move to the next row and find a safe position.
3. Continue placing queens row by row.
4. If a row has no safe position, backtrack to the previous row and try a different position.
5. Repeat until all queens are successfully placed.


## Example Output

For N = 4:

text
. Q . .
. . . Q
Q . . .
. . Q .


Where:
- Q = Queen
- . = Empty space


## Concepts Covered
- Backtracking
- Recursion
- Constraint Satisfaction Problems
- Matrix Representation
- Algorithm Design


## Author

*Suvidha Setia*  
B.Tech CSE (AI & ML) Student  
Passionate about Programming, Problem Solving, and Software Development.

## License

This project is created for educational and learning purposes.
