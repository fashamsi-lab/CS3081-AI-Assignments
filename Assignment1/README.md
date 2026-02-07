Assignment 1 files
# Tic-Tac-Toe AI using Minimax

**Name:** Faisal Shamsi  
**Student ID:** (S23108709)  
**Course:** CS3081 – Artificial Intelligence  
**Instructor:** Dr. Naila Marir  

## Description
This project implements an unbeatable Tic-Tac-Toe AI using the Minimax algorithm.  
The AI evaluates all possible game states and always chooses the optimal move.

## Implementation Approach
- The board is represented as a 3x3 list
- X is the maximizing player, O is the minimizing player
- Terminal states are checked using the winner and board fullness
- Minimax recursively evaluates all outcomes to select the best move

## Challenges
The main challenge was ensuring the board was not modified during recursion.  
This was solved using deep copies of the board in the `result()` function.

## Bonus
Alpha-Beta pruning was not implemented.
