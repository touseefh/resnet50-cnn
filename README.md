# ResNet-50 Image Classification 
## Overview
This project provides a training pipeline for fine-tuning a pre-trained ResNet-50 model (Convolutional Neural Network) using PyTorch for a 6-class image classification task. It includes data preprocessing, model training, evaluation, and visualization of results, utilizing transfer learning for effective performance.

## Features
### Data Handling: 
Processes a dataset with train/test splits, applying augmentation and normalization.
### Model: 
Adapts a pre-trained ResNet-50 with a modified fully connected layer for 6 classes.
### Training: 
Employs CrossEntropyLoss, SGD optimizer, and a learning rate scheduler, with early stopping based on test accuracy.
### Evaluation: 
Produces metrics like confusion matrix and classification report, along with visualized loss/accuracy trends.
### Requirements
1. Python 3.x
2. Libraries: PyTorch, Torchvision, Matplotlib, Seaborn, Scikit-learn
