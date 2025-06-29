# Lights Out Game Solver (Python + Tkinter)

This project is an interactive implementation of the classic *"Lights Out"* puzzle game using *Python's Tkinter* GUI library.  
It includes an *automated solver* that uses *Breadth-First Search (BFS)* to find the steps needed to turn off all the lights.

# Game Rules:

- The grid contains lights (white = off, black = on).
- Clicking a cell toggles that cell and its adjacent neighbors (up, down, left, right).
- The goal is to *turn off all the lights* on the grid.

# Features:
-  5x5 interactive game grid built using Tkinter.
-  Toggle lights by clicking cells.
-  Reset grid to all lights off.
-  Solve puzzle using *BFS algorithm*.
- Displays a list of steps needed to solve the current state.

# Technologies Used:

- Python 3
- tkinter – for GUI
- collections.deque – for BFS queue
