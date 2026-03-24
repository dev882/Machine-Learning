# Activation Functions in Neural Networks: ReLU vs Sigmoid vs Tanh

This repository contains the code and tutorial for a machine learning experiment comparing different activation functions in neural networks.

The project investigates how three commonly used activation functions — ReLU, Sigmoid, and Tanh — influence neural network training behaviour and classification performance when applied to the MNIST handwritten digit dataset.

## Project Overview

Activation functions are a critical component of neural networks because they introduce non-linearity into the model. The choice of activation function can significantly affect how quickly a neural network learns and how well it performs on unseen data.

This tutorial compares three activation functions:

- ReLU (Rectified Linear Unit)
- Sigmoid
- Tanh

A simple neural network architecture is trained using each activation function and their performance is evaluated using several metrics and visualisations.

## Dataset

The MNIST dataset is used for the experiments. It contains grayscale images of handwritten digits from 0 to 9.

Dataset details:

- Total images: 70,000
- Training images: 60,000
- Test images: 10,000
- Image resolution: 28 × 28 pixels

Reference:

LeCun, Y., Bottou, L., Bengio, Y. and Haffner, P., 1998. Gradient-based learning applied to document recognition.

## Neural Network Architecture

The neural network used in this experiment consists of:

- Flatten input layer
- Two hidden layers with 128 neurons
- Output layer with 10 neurons

The hidden layers use different activation functions depending on the experiment.

Training configuration:

- Optimizer: Adam
- Loss function: Sparse categorical crossentropy
- Epochs: 10
- Batch size: 128
