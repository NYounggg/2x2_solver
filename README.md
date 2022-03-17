# 2x2_solver
AI project/experiment for solving a 2x2 puzzle cube

When running the proj.ipynb Jupyter Notebook file, enter moves one at a time to turn the cube.  
Moves can be upper or lower case, and can contain an optional modifier at the end to denote degrees turned.

![cube](https://user-images.githubusercontent.com/71022019/156902906-60e1825d-ed9a-47e1-8ff1-cadd22c313a3.png)

Possible moves are: R, U, F, L, D, B (Right, Up, Front, Left, Down, Back) for face turns, and X, Y, Z for cube rotations along the corresponding axes.  
Each of these moves can be performed 90° clockwise, 90° counter-clockwise or 180° 'double' moves.  

A scramble can be generated by entering 'scramble'.  This scramble performs 10 random R, U and F moves, with no same-face moves occuring consecutively.


### Command Key

Move | Description                       |
-----|-----------------------------------|
R/r | Turn Right face 90° clockwise |
L/l | Turn Left face 90° clockwise |
U/u | Turn Up face 90° clockwise |
D/d | Turn Down face 90° clockwise |
F/f | Turn Front face 90° clockwise |
B/b | Turn Back face 90° clockwise |
X/x | Rotate whole cube 90° clockwise along the X axis |
Y/y | Rotate whole cube 90° clockwise along the Y axis |
Z/z | Rotate whole cube 90° clockwise along the Z axis |

Modifier | Description | Example |
---------|-------------|---------|
None | No modifier indicates a 90° clockwise turn | R, r 
' | Apostrophe indicates a 90° counter-clockwise turn | R', r'
2 | 2 indicates a double turn, i.e. a 180° turn | R2, r2

Other Commands | Description |
---------------|-------------|
scramble | Scrambles the cube and prints the scramble |
prev | Prints all of the previous moves |
quit | Terminates the program
