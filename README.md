Breast Cancer Prediction using PyTorch

This is a small learning project where I built a neural network in PyTorch to classify breast cancer tumors as malignant or benign.
The main goal of this project was to understand how PyTorch works internally — especially how to create a model using nn.Module, how backpropagation works, and how to train a simple neural network on a real dataset.

Why I built this

I wanted to get comfortable with the basics of deep learning instead of using high-level libraries blindly.
This project helped me understand:

How forward and backward passes work

How activation functions help the model learn non-linear patterns

How to train a model step by step (compute loss, backpropagate, update weights)

How to work with the Breast Cancer dataset from scikit-learn

For me, this was mainly about strengthening fundamentals.

Dataset

I used the Breast Cancer Dataset.
It has 30 numerical features and a binary target (benign or malignant).
It’s a good dataset for trying out binary classification with a simple neural network.

Model Summary

The model is a basic feed-forward neural network (MLP).
Something like:

Input layer: 30 features

Hidden layers: a couple of layers with ReLU and last activation function is sigmoid.

Output layer: 1 neuron with sigmoid (for binary classification)

I used BCELoss() as the loss function and Adam as the optimizer.
