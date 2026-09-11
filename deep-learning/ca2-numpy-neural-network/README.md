# CA2: Neural Network From Scratch With NumPy

This project implements feed-forward neural networks and backpropagation manually in NumPy for a cardiovascular dataset classification task.

## What I built

- Data loading and preprocessing with train/test splitting and feature standardization.
- Manual forward propagation, loss calculation, backpropagation, and parameter updates.
- Experiments with shallow networks, deeper networks, hidden-layer size, activation functions, initialization, and Adam-style optimization.

## Reported results

- Initial model: about 72.54% training accuracy and 72.24% test accuracy.
- Three-layer tanh model: about 72.46% training accuracy and 72.03% test accuracy.
- Optimized ReLU model with Xavier initialization and Adam-style updates: about 74.04% training accuracy and 72.97% test accuracy.

These results are treated as coursework experiment results, not as a clinical model or a production medical system.
