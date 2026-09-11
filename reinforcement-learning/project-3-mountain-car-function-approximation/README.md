# RL Project 3: Mountain Car With Function Approximation

This project applies tile coding and semi-gradient SARSA to Mountain Car.

## What I built

- A custom AIUT Mountain Car environment.
- Tile coding with 8 tilings and an 8x8 grid per tiling.
- Semi-gradient SARSA with linear action-value approximation.
- Cost-to-go and learning-curve visualizations.
- A separate Gymnasium MountainCar-v0 notebook for comparison.

## Reported observations

The custom AIUT Mountain Car experiment was trained for 5000 episodes and repeated across multiple runs. The reported learning curves converge toward roughly 130 to 140 steps per episode near the end of training. The Gymnasium version was trained for 500 episodes and reached roughly 149 steps after learning in the reported run.
