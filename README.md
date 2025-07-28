# Perceptron Implementation Assignment

## Overview
Implementation of single-sample and batch Perceptron algorithms for linear classification, including:
- Fixed vs variable learning rate strategies
- Performance evaluation on 2D dataset
- Decision boundary visualization

## Assignment Tasks

### Question A: Single-sample Perceptron
1. Dataset visualization and linear separability analysis
2. Implement `train_single_sample` function with:
   - Fixed learning rate (lr=1)
   - Accuracy tracking per epoch
   - Best model preservation
3. Decision boundary plotting with `plot_model`
4. Variable learning rate implementation:
   - Recursive lr = 1/√(k_i)
   - Scheduler class implementation
5. Comparative analysis of fixed vs variable lr

### Question B: Batch Perceptron
1. Implement `train_batch` function with:
   - Theta criterion (θ=0.01)
   - Periodic reporting (every 16 samples)
   - Error history tracking
2. Training with both fixed and variable learning rates
3. Comparative performance analysis:
   - Accuracy vs error plots
   - Convergence behavior

## Technical Requirements
- Implemented in Google Colab (Python)
- Dataset: `dataset.csv` (1000 2D samples)
- Manual implementation of:
  - Perceptron update rules
  - Learning rate scheduling
  - Performance metrics
