🧠 AlexNet on MNIST using PyTorch
This repository contains an implementation of the AlexNet Convolutional Neural Network (CNN) architecture, adapted to classify handwritten digits from the MNIST dataset using PyTorch.
📌 Overview
Model Architecture: A modified version of AlexNet tailored for grayscale images (1 channel) and small input size (32x32).
Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/), a standard benchmark dataset for digit recognition (digits 0-9).
Framework: PyTorch.
Goal: Train a CNN model to classify MNIST digits with high accuracy.

🏗️ Key Components
AlexNet class: Defines the architecture with 5 convolutional layers and 3 fully connected layers.
DataLoader: Loads and preprocesses MNIST data with resizing and normalization.
Training Loop: Optimizes the model using the Adam optimizer and CrossEntropy loss.
Evaluation: Computes classification accuracy on the test set.

