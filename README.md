# Self-Pruning Neural Network

This project implements a feed-forward neural network that learns to prune its own weights using learnable gates and L1 regularization.

## Dataset
CIFAR-10

## Results

| Lambda | Accuracy | Sparsity |
|--------|---------|----------|
| 0.001  | 55.08% | 1.03% |
| 0.01   | 55.41% | 25.35% |
| 0.1    | 54.00% | 94.02% |

## Description
The model demonstrates a trade-off between accuracy and sparsity. As the regularization parameter increases, more weights are pruned while maintaining reasonable performance.
