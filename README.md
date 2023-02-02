# Gomoku-AI-Python


# Overview
This is strategy board game played on 15 * 15 Go Board, which is most widely played in Asian countries like China,Korea and Japan. This is a multi agent game where two players place their coins on board on alternate basis.
Players will be assigned with coloured coins.
Player 1 (Black Coin) Player 2 (White coin)
Winning Criteria:
Players can win this game by placing five same coloured coins in a vertical,horizontal and diagonal line.

# This Game uses adversarial search where the player will try to minimize the winning chances of the opponent player.

● To implement this game, the Minimax algorithm is being used with alpha beta pruning to identify the best possible move for the AI.

● Utility functions are used by AI for pattern matching. This function consists of a pattern and a heuristic value which will help AI to make the best possible move.

● Heuristics: Every board position on 15 * 15 boards are assigned a heuristic value. This value is also used by AI to identify the best position to place the coin.


# Game Versions:
● Human vs AI
Here AI will maximize its chances of winning while minimizing the winning chances of its opponent using a minimax algorithm.
● Human vs Human
Here both players will play against each other to win the game.
