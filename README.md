# rl-tutorials
Reinforcement Learning Tutorials during my TAship for course ECE1508 at the University of Toronto.

# Reinforcement Learning Tutorials

This repository contains a collection of tutorials designed to introduce and deepen understanding of various reinforcement learning (RL) techniques. Each tutorial focuses on a different method or approach commonly used in RL, with practical examples and explanations.

## Getting Started

The best way to start is to open this GitHub repository in [Google Colab](https://colab.google.com):

1. Go to [Google Colab](https://colab.google.com).
2. Click on **File** -> **Open notebook**.
3. Select the **GitHub** tab.
4. Paste this repository's link: `https://github.com/HsiaoTsan/rl-tutorials`.
5. Choose the notebook you want to open and start experimenting!

Each tutorial is contained within its own folder and includes all necessary code and explanations to get started. 

---


## Tutorials

### Tutorial 1 - Tabular RL for Continuous State Problems with State Discretization
In this tutorial, we explore tabular RL methods applied to continuous state problems. By discretizing the state space, we can use simpler tabular methods for scenarios where a continuous representation would typically be required.

- **Topics Covered**: State discretization, Q-learning, SARSA.
- **Objective**: Understand how to handle continuous states using discrete approximations.

### Tutorial 2 - Deep Q-Network (DQN) for Continuous State Problems
This tutorial introduces Deep Q-Networks (DQN), a neural network-based approach to approximate Q-values in environments with continuous states.

- **Topics Covered**: Q-learning, experience replay, epsilon-greedy policies.
- **Objective**: Implement and train a DQN to solve continuous state-space problems.

### Tutorial 3 - Policy Gradient and Actor-Critic
Here, we dive into policy gradient methods and the Actor-Critic framework, which combines both value-based and policy-based approaches to optimize RL policies.

- **Topics Covered**: Policy gradient, advantage functions, Actor-Critic methods.
- **Objective**: Learn the basics of policy-based methods and implement a simple Actor-Critic algorithm.

### Tutorial 4 - Trust Region Policy Optimization (TRPO)
This tutorial covers Trust Region Policy Optimization (TRPO), a method designed to ensure stable policy updates by constraining policy shifts to a "trust region."

- **Topics Covered**: KL divergence constraint, policy stability, TRPO algorithm.
- **Objective**: Understand TRPO's approach to limiting large policy updates and achieve stable learning.

### Tutorial 5 - Proximal Policy Optimization (PPO)
We explore Proximal Policy Optimization (PPO), an improvement on TRPO that simplifies policy optimization while maintaining stability and efficiency.

- **Topics Covered**: Clipped surrogate objective, PPO algorithm, policy constraints.
- **Objective**: Implement PPO and learn how it balances policy update stability with sample efficiency.
