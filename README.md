# Annealing_Slicing_Layout
This project uses slicing layouts and the Simulated Annealing Heuristic to find solutions to block layout placement problem. Slicing layouts are represented in Polish notation using Horizontal "H" cuts and Vertical "V" cuts to combine blocks in a chip layout.

For example, a layout may be represented by a string of blocks and cut operations: B1 B2 H B3 B4 HV
This string also can be represented as a tree of operations and blocks as the leaves.

The simulated annealing is performed by making small perturbations in the slicing layout string, and then re-evaluating the layout produced by that string. After many moves, the heuristic (hopefully) produces an acceptable layout for the blocks and with minimized wirelength.
