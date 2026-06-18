# CPSC 481 m×n Tic-Tac-Toe Tutor

This project is an AI tutor for m×n Tic-Tac-Toe. The board size and win condition are configurable. The tutor recommends moves using depth-limited minimax, alpha-beta pruning, and a heuristic evaluation function.

## Team Members
- Steven Odyan
- Kevin Fuentes
- Gilbert Cervantes

## Default Demo
- Board size: 5x5
- Win condition: 4 in a row

## Features
- Configurable m×n board size
- Configurable win length
- Legal move detection
- Win and draw detection
- AI move recommendation
- Depth-limited minimax search
- Alpha-beta pruning
- Heuristic board evaluation
- Simple graphical user interface

## AI Approach
The tutor uses minimax to search possible future moves. Alpha-beta pruning is used to reduce unnecessary searching. Since larger boards are too expensive to search completely, the AI uses a heuristic evaluation function to estimate how strong a board position is.

The evaluation function considers factors such as:
- Immediate winning moves
- Blocking opponent wins
- Creating possible winning lines
- Preventing opponent threats
- Longer sequences of marks in a row

## Planned Evaluation
We will compare the tutor's recommended moves against random legal moves on larger board sizes such as 4x4 and 5x5. We will also measure how alpha-beta pruning affects the number of board states searched.