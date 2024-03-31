# Summary

This repo focuses on solving the n-Queens problem using various local search algorithms. The n-Queens problem entails placing 𝑛 queens on an 𝑛×𝑛 chessboard in such a way that no two queens threaten each other. This means no two queens share the same row, column, or diagonal.

The notebook outlines the problem statement, including the state space representation and objective function. It then introduces helper functions for generating random boards, calculating conflicts, and visualizing the board.

Tasks are defined to implement different local search algorithms:

- Steepest-ascend Hill Climbing Search: Choose the move that results in the least conflicts among all possible moves.

- Stochastic Hill Climbing 1: Randomly select uphill moves until a local optimum is reached.

- Stochastic Hill Climbing 2: Generate a single random neighbor at a time and accept it if it improves the objective function. Terminate if no improvement is made after a certain number of tries.

- Hill Climbing Search with Random Restarts: Perform hill climbing multiple times (up to 100) with random starting boards to find a better solution.

- Simulated Annealing: A stochastic hill climbing approach that allows downhill moves with a probability based on a temperature parameter. The temperature decreases over iterations according to an annealing schedule.

Finally, we compare the performance of these algorithms in terms of runtime, number of conflicts, and the percentage of runs ending in an optimal solution for different board sizes (4x4 and 8x8).


Overall, this notebook provides a comprehensive exploration of different local search algorithms for solving the n-Queens problem and encourages experimentation and analysis of their performance.





