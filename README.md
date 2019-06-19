# Solve Sudoku with AI

## Synopsis

In this project, we leverage techniques, such as constraint propagation and depth first search search, to solve _diagonal_ Sudoku puzzles. We also implement a new constraint strategy called "naked twins". A diagonal Sudoku puzzle is identical to traditional Sudoku puzzles with the added constraint that the boxes on the two main diagonals of the board must also contain the digits 1-9 in each cell (just like the rows, columns, and 3x3 blocks).


## Quickstart Guide

You can run the code with visualization (see the last section of the readme for more information)

    `$ python solution.py`


## Visualization

**Note:** The `pygame` library is required to visualize the solution -- however, the `pygame` module can be troublesome to install and configure. It should be installed by default with the AIND conda environment, but it is not reliable across all operating systems or versions. Please refer to the pygame documentation [here](http://www.pygame.org/download.shtml), or discuss among your peers in the slack group or discussion forum if you need help.

Running `python solution.py` will automatically attempt to visualize your solution, but you mustuse the provided `assign_value` function (defined in `utils.py`) to track the puzzle solution progress for reconstruction during visuzalization.

This project is a part of Udacity AI Nanodegree.
