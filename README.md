# 8 Puzzle Game using A* Algorithm
This Python program is a console-based implementation of the classic 8 puzzle game. The game uses the A* algorithm to find the optimal solution to the puzzle.

## Getting Started
To run the game, you need to have Python 3.x installed on your system. You can download Python from the official website.

Once you have Python installed, download the source code from the repository and extract it to a directory of your choice.

## Running the Game
To run the game, navigate to the directory where the source code is located and run the following command in the terminal:


python main.py

This will start the game, and you can follow the on-screen instructions to play the game.

## How to Play
The objective of the game is to rearrange the tiles in the puzzle to form the correct order. The tiles are numbered from 1 to 8, and there is an empty tile that can be used to slide the other tiles around.

To move a tile, you can use the arrow keys on your keyboard. You can only move a tile into the empty space. The game is won when the tiles are arranged in the correct order:


1 2 3
4 5 6
7 8  

## A* Algorithm
The A* algorithm is used to find the optimal solution to the puzzle. It is a search algorithm that uses heuristics to guide the search towards the goal state. In this implementation, the heuristic used is the Manhattan distance. The algorithm explores the state space by expanding nodes and keeping track of the best path to each node.

## Acknowledgments
This game was developed as part of a programming challenge. The A* algorithm implementation was inspired by the pseudocode provided in the textbook "Artificial Intelligence: A Modern Approach" by Stuart Russell and Peter Norvig.