# n_queens
 N-Queens Solver using Backtracking

The N-Queens Problem is a classic backtracking problem where the goal is to place N queens on an N × N chessboard such that no two queens attack each other.

A queen can attack:
-- Horizontally
-- Vertically
-- Diagonally

The challenge is to place all queens safely.

FEATURES:

Works for any value of N
Uses efficient backtracking
Prints all possible solutions
Easy-to-understand implementation

APPROACH(BACKTRACKING):

We solve the problem column by column:

Start from column 0
Try placing a queen in each row
Check if the position is safe:
No queen in same row (left side)
No queen in upper diagonal
No queen in lower diagonal
If safe:
Place queen
Move to next column
If not safe:
Try next row
If no position works:
Backtrack

* TIME & SPACE COMPLEXITY:

Time Complexity: O(N!) (approx)
Space Complexity: O(N²)
