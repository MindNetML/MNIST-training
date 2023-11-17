# PyTorch MNIST Classifier

## Overview
This repository contains a Jupyter notebook focused on building and training a neural network to classify handwritten digits from the MNIST dataset using PyTorch. The project showcases data preprocessing, model creation, training, and inference, along with visualizations of the results.

## Model Description
The `MultiClassMNIST` model is a fully connected feed-forward neural network with the following architecture:
- **Input Layer:** 784 neurons (for flattened 28x28 grayscale images).
- **Hidden Layer 1:** 300 neurons, ReLU activation.
- **Hidden Layer 2:** 200 neurons, ReLU activation.
- **Output Layer:** 10 neurons (one for each digit class, 0-9).

## Features
- **Data Preprocessing:** Efficient data handling using PyTorch DataLoaders.
- **Customizable Neural Network:** A configurable model that allows varying the number of neurons in the hidden layers.
- **Training Loop:** Implementation of forward pass, loss computation, backpropagation, and optimization.
- **Inference & Visualization:** Running the model on test data and visualizing the predictions compared to the actual labels.

## Tools and Libraries
- Python
- PyTorch
- Matplotlib (for visualization)
