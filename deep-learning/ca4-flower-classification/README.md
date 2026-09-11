# CA4: Flower Image Classification

This project trains convolutional neural networks for five-class flower classification using the TensorFlow flower photos dataset.

## What I built

- Image loading and preprocessing pipelines.
- Controlled optimizer and learning-rate comparisons.
- CNN training with regularization and validation monitoring.
- Final evaluation with validation accuracy, precision, recall, and class-level observations.

## Reported results

The controlled comparison selected SGD with learning rate `0.01`. The final notebook reports:

- Best validation accuracy: 73.98%.
- Final training accuracy after restoring the best weights: 74.76%.
- Final validation accuracy: 73.98%.
- Validation macro precision: 73.70%.
- Validation macro recall: 73.11%.
- Train-validation accuracy gap: 0.78 percentage points.

The original flower dataset archive is large, so it is intentionally not committed. The notebook expects the TensorFlow flower photos dataset to be available locally or downloaded before running.
