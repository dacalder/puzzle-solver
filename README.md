# puzzle-solver

![puzzle](https://github.com/dacalder/puzzle-solver/blob/master/docs/images/puzzle.png)

<h3> Overview </h3>
The objective of this puzzle is to move the red block (0) to a defined location. For example, an objective could be to move the red block to where the orange piece is currently located. 

Rules:
1. The black pieces can't be moved
2. Pieces can't overlap
3. Pieces can't be rotated

<h3> Main methods </h3>
PuzzleSolver.java

* **bfs** - returns a list of states to be followed to reach the objective
* **stateChange** - deep copies a state and performs an action on it
* **reachedObjective** - returns true if the objective has been reached
* **validState** - returns true if an action perfomed on a state is valid

