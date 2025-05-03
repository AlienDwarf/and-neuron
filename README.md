# Neural Network Visualizer: AND Gate

[Demo](https://aliendwarf.github.io/and-neuron/) 

This project provides an interactive visualization of a simple neural network designed to simulate the behavior of an AND gate. It uses a sigmoid activation function and allows users to adjust the inputs (x₁ and x₂) via sliders, with the output of the neural network being displayed dynamically.

## Table of AND Gate Truth Table

| x₁ | x₂ | Output (y) |
| --- | --- | ---------- |
|  0  |  0  |     0      |
|  0  |  1  |     0      |
|  1  |  0  |     0      |
|  1  |  1  |     1      |

## How It Works

The neural network in this demo is a simple perceptron with the following structure:
- Inputs: x₁, x₂
- Weights: w₁, w₂
- Bias: b
- Activation Function: Sigmoid function

The network calculates a weighted sum of inputs and applies the sigmoid activation function to produce the output.
