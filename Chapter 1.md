### Exercise 1.1
If a reinforcement learning agent played with itself, the agent will end up learning a cheated solution. The final policy can result in an environment in which one of the agent always wins or the match always ends up in a draw. 

### Exercise 1.2
Symmertricities can infact be leveraged to make the optimization process faster. Each state has four identical symmetric states, which means the next states possible from each of those four states will be identical. The value function for each of these four identical states can be shared. Sharing value function across symmetric states will make the learning process faster.

### Exercise 1.3
A greedy reinforcement learning player will learn to play much worse than a non greedy player. A non greedy player has a better chance to discovering optimal moves since it can choose a move with a lower probability but one which actually optimal. A greedy player will make non greedy decisions during the initial stages of learn as the value function for all states will be equal. Eventually, it will only prefer the moves made in the initial stages and not explore any other moves. 

### Exercise 1.4


### Exercise 1.5
