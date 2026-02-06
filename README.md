I used MacOS for this assignment.

### Negamax

The negamax algorithm works by going through every possible game state and assigning a score to the
terminal states (0 - draw, 10 - win). Similar to minimax, the algorithm tries to maximize the score
for the AI player, but negamax works differently by treating each player as the maximizing player. This is why we take
the negative of the output of the algorithm and the negative of the score of the terminal state of winning.
As we recursively go through the game tree, when the AI player is maximizing, it will add to the score, and
when the human player is maximizing, it will subtract from the score. The AI then chooses the move with the best
score after evaluating the score for all of the possible moves. 