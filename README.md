Experiment 1: Perceptron Learning Algorithm for NAND & XOR
Objective
To implement the Perceptron Learning Algorithm using NumPy in Python and evaluate its performance on NAND and XOR truth tables.

Description of the Model
A single-layer perceptron is a basic neural network model that uses a linear decision boundary to classify inputs.

NAND is linearly separable, so a perceptron can learn it.
XOR is not linearly separable, so a perceptron fails to learn it.
Perceptron Learning Rule:
Initialize weights and bias to zero.
For each training example:
Compute the weighted sum.
Apply a step activation function (output 1 if sum ≥ 0, else 0).
Adjust weights using:
w = w + learning rate × error × x
Repeat until convergence.
