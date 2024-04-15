# Monte-Carlo-Simulation-
Monte Carlo Simulation is a computational algorithm that works on the principle that a random sample from the population has the properties of the population. It simulates the range of possible outcomes for an uncertain event. 
It has four steps which are run for several iterations. The steps are:
  1. Selection
  2. Expansion
  3. Rollout
  4. Backup

The selection process selects the best node by balancing the exploration and exploitation. It uses the predefined UTC (Upper Confidence Bound) formula.
The Expansion process digs deeper into the tree until it meets the leaf node(node that has not been explored yet).
After the leaf node is reached, a random simulation is carried out till the game is over. The randomness is mandatory for the simulation to learn better. At the end of the random play, a reward is granted for the win or loss.
The reward granted at the end of the random play is back transferred via the branch where the expansion was carried out and the value for each node is updated.
Now, one iteration for the monte carlo is completed. Several similar iterations are carried out and at the end, the node with the highest value is chosen as the best move.
