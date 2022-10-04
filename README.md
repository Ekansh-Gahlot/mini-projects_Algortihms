# PROJECTS BASED ON FAMOUS ALGORITHMS.

# SUDOKU SOLVER
The following code uses backtracking to solve Sudoku problem.
The algorithm deployed is as follows - 
1) We first make sure that the number is valid placement satifying the conditions - 
    Rule 1 - Each row must contain the numbers from 1 to 9, without repetitions.
    Rule 2 - Each column must contain the numbers from 1 to 9, without repetitions.
    Rule 3 - The digits can only occur once per localblock.
 2) If the number is valid for that place we add the number.
 3) We do this recursively for all empty places (here represented with 0).
 4) If we ever encounter a situation where we cannot find any valid number from 0 to 9, we use backtracking and se the previously set number to zero and the process continues.
 5) If backtracking is successfull and we cna add the numbers to all the blocks, we return the with message "Solved successfully".
 6) Else we return "Unsolvable board"
 7) Print the board.
 8) END
