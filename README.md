# checkers using AI

This project implements a Checkers (Draughts) game where two AI agents play against each other. The game is powered by the MinMax algorithm with Alpha-Beta Pruning to optimize decision-making by evaluating possible moves and reducing the number of nodes to explore in the decision tree. There is no human involvement; the two AI agents take turns making moves, aiming to play the game optimally.

The project is written in Python and provides an AI-driven checkers game simulation where the two agents utilize MinMax and Alpha-Beta Pruning techniques to decide on their moves.

Checkers Game with MinMax Algorithm and Alpha-Beta Pruning
Project Overview
This project implements a Checkers (Draughts) game where two AI agents play against each other. The game is powered by the MinMax algorithm with Alpha-Beta Pruning to optimize decision-making by evaluating possible moves and reducing the number of nodes to explore in the decision tree. There is no human involvement; the two AI agents take turns making moves, aiming to play the game optimally.

The project is written in Python and provides an AI-driven checkers game simulation where the two agents utilize MinMax and Alpha-Beta Pruning techniques to decide on their moves.

# Features
1. # Game Rules
The game follows standard Checkers (Draughts) rules:
Played on an 8x8 grid.
Each player controls 12 pieces at the start.
Pieces move diagonally and capture opponent pieces by jumping over them.
A piece that reaches the opposite side of the board is "kinged" and gains additional movement abilities.
# 2. MinMax Algorithm
The MinMax algorithm is a decision-making process used by the AI to choose the optimal move by evaluating future board states. The algorithm explores all possible moves, assuming both agents play optimally.

# 3. Alpha-Beta Pruning
The Alpha-Beta pruning technique optimizes the MinMax algorithm by cutting off branches of the decision tree that are not worth exploring. It helps improve the efficiency of the search by discarding moves that are unlikely to be chosen based on the current best-known option.

# 4. Two AI Agents
There are no human players in this game. The entire game is played by two AI agents that take turns.
The AI agents use the MinMax algorithm and Alpha-Beta pruning to evaluate each possible move and select the best one for their strategy.
