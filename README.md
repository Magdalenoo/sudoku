# Sudoku solver
This project is a python sudoku solver using backtracking algorithm.
Sudoku board is delivered at the top of the file. 

# How to use:
python3 sudoku.py

Feel free to download and use this app to solve your sudoku. If you need you can adjust board but remember that the table is rotated 90 degrees to the left. Zeros represent empty fields to be filled in.

# How it works:
The backtracking algorithm fills in the blanks in such a way that they are not repeated in intersecting columns. If it turns out that a number does not meet expectations and needs to be placed somewhere else, the algorithm goes back and changes the number that was placed earlier to adapt to the new layout.
