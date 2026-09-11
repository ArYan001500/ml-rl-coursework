# RL Project 2: Temporal-Difference Learning and Planning

This project studies Cliff Walking with temporal-difference and model-based reinforcement-learning methods.

## What I built

- A custom Cliff Walking environment.
- n-step SARSA training on a 5x20 grid for 500 episodes.
- Dyna-Q with different numbers of planning steps.
- Dyna-Q and Dyna-Q+ comparisons in a changing environment.

## Reported observations

Dyna-Q learned faster and more smoothly than pure n-step SARSA when planning steps were used. In the non-stationary setting, Dyna-Q+ adapted faster after the environment changed because the exploration bonus encouraged revisiting actions that had not been tried recently.
