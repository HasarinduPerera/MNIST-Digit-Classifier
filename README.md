# MNIST Digit Classifier Project

## Project Overview

This project was completed as part of the Machine Learning Fundamentals Udacity Nanodegree. It involves building a character recognition system using the MNIST database of handwritten digits, serving as a proof of concept for optical character recognition.

## Data Loading and Exploration

- Data was transformed into tensors for use in neural networks.
- DataLoader objects were created for the training and test sets.
- The dataset's size and shape were explored and visualized using `plt.imshow`.
- Necessary preprocessing steps were justified in comments or markdown blocks.

## Model Design and Training

- A neural network for image classification was designed using PyTorch.
- At least two hidden layers were implemented with a forward method for predicting class probabilities.
- An appropriate loss function for classification was specified.
- An optimizer from `torch.optim` was used to minimize the loss function and update model parameters.

## Model Testing and Evaluation

- Model accuracy was tested using the DataLoader and the test set.
- Hyperparameters were optimized to achieve at least 90% classification accuracy.
- Trained model parameters were saved for future use using `torch.save()`.

## Project Summary

This project demonstrates the creation of a character recognition system using the MNIST dataset for optical character recognition. It involves data preprocessing, model design, training, testing, and evaluation. Preprocessing justifications were provided, and the model achieved the target accuracy of at least 90% on the test set. The trained model is saved for potential future use.