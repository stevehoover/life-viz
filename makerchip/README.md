# Conway's Game of Life

This example implements Conway's Game of Life.
In this "game", a grid of cells (10x10) are born and die based on the
number of live neighbors they have in each step (clock cycle).
A cell's neighbors are the surrounding 8 cells, which includes the
diagonals.
- A cell is born if exactly 3 neighbors are alive.
- A cell dies from overcrowding or starvation if it have >3 or <2
    neighbors.

Output shows the grid in each step of simulation.
 
