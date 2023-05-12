# minesweeper

![Minesweeper](https://github.com/ShubhamPhapale/minesweeper/assets/94707673/f5b2d1b7-1f06-4286-8b61-a4bc1893c8c2)

Minesweeper is a puzzle game that consists of a grid of cells, where some of the cells contain hidden “mines.” Clicking on a cell that contains a mine detonates the mine, and causes the user to lose the game. Clicking on a “safe” cell (i.e., a cell that does not contain a mine) reveals a number that indicates how many neighboring cells – where a neighbor is a cell that is one square to the left, right, up, down, or diagonal from the given cell – contain a mine.

We have implemented an AI to play Minesweeper.

It uses the knowledge that it has and try to come up with inferences and new knowledge and makes move.

When you run your AI (as by clicking “AI Move”), note that it will not always win! There will be some cases where the AI must guess, because it lacks sufficient information to make a safe move. This is to be expected. runner.py will print whether the AI is making a move it believes to be safe or whether it is making a random move.
