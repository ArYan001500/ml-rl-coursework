# RL Project 1: Dynamic Programming and Bandits

This project covers foundational reinforcement-learning algorithms from tabular settings.

## What I built

- Policy iteration for a 4x4 Gridworld with terminal states and discount factor `gamma = 0.9`.
- Ten-armed bandit experiments comparing epsilon-greedy action selection and UCB.
- A 5x5 Gridworld value-matrix solution using a Markov reward process and a closed-form linear-system solve.

## Reported observations

In the bandit experiment, UCB with `c = 2` produced higher and more stable average reward than epsilon-greedy with `epsilon = 0.1` across 2000 runs. The Gridworld tasks helped connect Bellman equations, policy evaluation, policy improvement, and matrix-based value solving.
