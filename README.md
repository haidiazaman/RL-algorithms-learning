# Fundamentals of RL

Understanding the theory and fundamentals of RL. Implmentations are shown for Q-learning, SARSA, DQN, etc.

get a high level understanding of the math behind the RL algos. Only after developing a solid understanding of Q-learning and DQN, can we move on to more advanced RL algos like PPO.

SARSA vs Q-learning
The difference between these two algorithms is that SARSA chooses an action following the current policy and updates its Q-values, whereas Q-learning chooses the greedy action. A greedy action is one that gives the maximum Q-value for the state, that is, it follows an optimal policy.