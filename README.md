# evaller
The program should read a chess position an then automatically write a C eval() function for it.

NOTE:

The evaller program should:
    1) Read a chess position (e.g. a position from a rook endgame with pawns), as a root for the searchtree;
    2) Code a C eval() function tailored for the local tree rooted on the position read at (1)

The eval() function, when compiled then called, should read each node position from the searchtree and evaluate it by the evaluation algorithm designed by our evaller program for the read root position.
In the general case, the root position read by evaller may not be neccessarily be the initial chess position, but rather a chess position given for analysis.

Postulate: From a given position, the eval() function depends on the read local root node and is the same for the whole local tree (heuristical: on a depth of, e.g. 14-15 plies), but it is NOT the same for all the game of chesss.

The evaller program should creatively design, w/o human assistance, the C source file for eval(), depending of the read local root position.
The evaller program, for now, should be developed only for CPU.

