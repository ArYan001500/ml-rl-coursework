# CA4 Advanced Experiments: Flower Classification

This folder contains a separate working version of the flower-classification assignment. It is not a direct duplicate of the submitted CA4 folder; it appears to be an experimental continuation with deeper CNNs, transfer learning, and Keras Tuner runs.

## What I built

- A regularized CNN with residual-style blocks, squeeze-and-excitation components, stochastic depth, and MixUp.
- EfficientNetB0 transfer-learning experiments.
- Keras Tuner experiments for architecture and training hyperparameters.

## Reported results

The notebook contains several experimental tracks. A transfer-learning run reached about 93.73% validation accuracy during training. Later evaluation output in the same notebook is inconsistent with that high validation number, so I keep this result framed as an experimental training observation rather than a final verified benchmark.

Generated tuner folders, local checkpoints, cache files, and the EfficientNet cache weight file were excluded from this GitHub-ready copy.
