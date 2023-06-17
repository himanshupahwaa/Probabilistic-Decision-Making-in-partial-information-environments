# Probabilistic-Pursuit-and-Adaptive-Decision-Making-in-Dynamic-Environments

The environment consists of a graph with 50 randomly connected nodes. The prey moves in random directions with a certain probabilities while the predator always chases the agent in the direction of the shortest path. The objective is for the Agent to capture the Prey while evading capture by the Predator in a partial or no information environment.

There are several settings in which the agents operate:

Complete Information Setting: The Agent knows the exact locations of the Predator and the Prey. Two agents, Agent 1 and Agent 2, are implemented in this setting.

Partial Prey Information Setting: The Agent knows the Predator's location but not the Prey's. The Agent can survey nodes to determine if the Prey is present and updates its belief state about the Prey's location. Two agents, Agent 3 and Agent 4, are implemented in this setting.

Partial Predator Information Setting: The Agent knows the Prey's location but not the Predator's. The Agent can survey nodes to determine if the Predator is present and updates its belief state about the Predator's location. Two agents, Agent 5 and Agent 6, are implemented in this setting.

Combined Partial Information Setting: The Agent does not know the exact locations of the Predator or the Prey. The Agent can survey nodes to determine the occupants and maintains belief states for both the Predator and the Prey. Two agents, Agent 7 and Agent 8, are implemented in this setting.

The objective is to analyze the performance of each agent in terms of how often the Predator catches the Agent, how often the Agent catches the Prey, the occurrence of simulation hang, and the accuracy of the Agent's knowledge about the Predator and the Prey. The report should compare the specified agents' performance and evaluate if the agents effectively utilize the available information.

**To see the full approach and strategy implementation for the above mentioned scenarios, please refer to the ProbabilisticPursuit.pdf in the repository.**
