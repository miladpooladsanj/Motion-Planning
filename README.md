Design and implement in code a Planner algorithm for a square chessboard of arbitrary size with certain cells marked red as restricted areas. There are N kings on the board, each with a specific target cell to reach. The kings move sequentially, one by one, one step at a time (K1 step1, K2 step1…. K1 step2, K2 step2…), and must adhere to two main rules: they cannot move into restricted cells, and they cannot end a move adjacent to another king (including diagonally). A king may stay in place (empty move). The task is to compute a path for each king to its target, ensuring compliance with the movement rules and the sequential order of moves.
Planner’s input would be given as 2 files:
File1 - king starting and target positions
x_from, y_from, x_to, y_to
…
File2 - chessboard size and restricted areas
N
x, y
…
x and y integer coordinates start from zero.

If plan (solution) does not exist, Planner should detect and output that plan does not exist.
If plan does exist, Planner should output a plan in format 
x_from, y_from, x_to, y_to
…
where each line is one step of one king, and king_id would be deduced by a test program from “from” coordinates.
For a 100x100 chessboard size the Planner should finish planning in reasonable time.
The Planner program should use not more than 1GB of RAM.
A reasonable simple visualization would be a plus but is not a requirement.
Your ideas on optimality of your algorithm would be a valuable add-on when discussing your solution on a call.
Implementations can be done in Go, C++ or python.
