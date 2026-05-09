# Puzzle Solvers

A small collection of scripts to help solve puzzles.

## NineColors

A puzzle based on the [Nine-Color Cube](https://en.wikipedia.org/wiki/Nine-Colour_Cube), which consists of multiple pieces made up of smaller colored cubes. One piece is made up of 3 cubes in a long line, the other 12 pieces are made up of two smaller pieces each. The puzzle lies in the task to have each face contain all colors exactly once.

This program uses graph search for the solution space with early pruning and duplicate removal (The big piece can only go through the center, lie in an edge of go through the middle of a face. One position can be chosen each, all other positions will be rotations or reflections.)
