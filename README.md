# CPSC-481
# Jason Duong
# Danny Diep
# MightyHellRazr (I forgot your real name srrrrr!!!)

Using computers to simulate human intelligence. Production systems, pattern recognition, problem solving, searching game trees, knowledge representation and logical reasoning. Programming in AI environments.

Note:
Since there is a recursion limitation on our machine and DFS run time is O(n), the function will stop at the limit when solving the 3x3 puzzle.

2x2 puzzle:
Initial State [0, 3, 2, 1]
Goal State - [1, 2, 3, 0]
There are 7 states explored when using the DFS method. The steps are RIGHT, DOWN, LEFT, UP, RIGHT, DOWN to reach the goal state.
There are 11 states explored when using the BFS method. The steps are RIGHT, DOWN, LEFT, UP, RIGHT, DOWN to reach the goal state.

3x3 puzzle:
Initial State - [1, 4, 3, 7, 0, 6, 5, 8, 2]
Goal State - [1, 2, 3, 4, 5, 6, 7, 8, 0]
There are 3712 states explored when using BFS method. The steps are UP, RIGHT, DOWN, DOWN, LEFT, LEFT, UP, RIGHT, RIGHT, UP, UP, LEFT DOWN, DOWN, RIGHT to reach the goal state.
As mentions above, the DFS function stops at the recursion limit when it explored 169 states.
