# 2x2_solver
AI project/experiment for solving a 2x2 puzzle cube

When running the proj.ipynb notebook file, enter moves one at a time to turn the cube.  
Moves can be upper or lower case, and can contain an optional modifier at the end to denote degrees turned.

![cube](https://user-images.githubusercontent.com/71022019/156902906-60e1825d-ed9a-47e1-8ff1-cadd22c313a3.png)

Possible moves are: R, U, F, L, D, B for face turns, and X, Y, Z for cube rotations.  
Each of these moves can be done 90° clockwise (e.g. r), 90° counter-clockwise (e.g. r') or 180° double moves (e.g. r2).  Enter 0 to terminate the program.

A scramble is generated when you run the code, following a vaguely WCA-complient scrambling algorithm.  
This algorithm generates 10 moves only involving the R, U and F faces, and makes sure no same-face turns occur consecutively.
