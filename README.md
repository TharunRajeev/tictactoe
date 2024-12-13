## Program Details

- The implementation-defined game variables like X, O, and EMPTY.
- Functions are developed to determine the player's turn, list possible moves, generate new board states, identify winners, check game termination, assign scores to terminal boards, and find the optimal move using Minimax algorithm.
- Minimax algorithm recursively explores possible moves, minimizing the maximum possible loss (or maximizing the minimum possible win) for the player, ensuring optimal decision-making.
- Playing against this AI guarantees a tie if both sides play optimally, demonstrating its ability to play Tic-Tac-Toe perfectly.

- To implement an optimal AI for Tic-Tac-Toe using Minimax:

1. Define Game Variables: X, O, and EMPTY to represent the players and empty cells.
   
2. Implement Functions:
  - player: Determines which player's turn it is.
  - actions: Returns all possible moves on the board.
  - result: Generates a new board after a move.
  - winner: Determines if there's a winner and returns it.
  - terminal: Checks if the game is over.
  - utility: Assigns a score to a terminal board.
  - minimax: Determines the best move for the player using the Minimax algorithm.
3. Minimax Algorithm: Minimizes the worst-case scenario and maximizes the best-case scenario to find the optimal move.

4. Outcome: Playing against this AI ensures a tie if both sides play optimally, demonstrating its optimal decision-making in Tic-Tac-Toe.



