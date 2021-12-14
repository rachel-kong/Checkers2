# Checkers2
by Sumya Sultana and Rachel Kong for CS 102 Section C Fall 2021
# Introduction

Checkers is played by two people who oppose each other across a board of 64 light and dark squares, the same as a chessboard. The 24 playing pieces are disk-shaped and of contrasting colors. At the start of the game, each contestant has 12 pieces arranged on the board. The notation used in describing the game is based on numbering the squares on the board. The black pieces always occupy squares 1 to 12, and the white pieces invariably rest on squares 21 to 32. The pieces can only move forward diagonally.

To account for the limited graphics in C, we used different symbols to denote our black and red pieces. (The red pieces are denoted by $. The black pieces are denoted by @).

E denotes empty spots as where these are the open spaces where each player can move to.
Only diagonal moves are allowed by jumping over opponent pieces to capture pieces. One player has the dark pieces; the other has the light pieces. Players alternate turns, and a player may not move an opponent's piece. A move consists of moving a piece diagonally to an adjacent unoccupied square that is denoted by E. 

We created a 2 player game in which each user inputs a starting point to indicate which piece they want to move. Our program then asks for an entry of where the player wants to move their piece. If the player attempts to make an "illegal" move, the game will inform the user that the move was illegal and will be requested to try again. 

If the adjacent square contains an opponent's piece, and the square immediately beyond it is empty or unoccupied, the piece may be captured by jumping over it. These rules are accounted for in our code. 

# Technical Description

# Screenshots of Working Program

# Link to YouTube video recording of presentation and code walk through
