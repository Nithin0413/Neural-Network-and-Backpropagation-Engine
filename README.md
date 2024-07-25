# Backpropagation Engine and Neural Network Implementation
## Project Overview
This project implements a basic backpropagation engine and a neural network from scratch in Python. The project consists of two main components: the Value class for automatic differentiation and the neural network modules (Neuron, Layer, and MLP) for building and training a multi-layer perceptron

## Implementation Details

### Backpropagation Engine
The Value class represents a scalar value in the computational graph and supports various mathematical operations. Each Value object keeps track of its gradient and the operation used to create it. The class also includes a backward_pass method for performing backpropagation to compute gradients.

### Neural Network Modules
The neural network is implemented using three main classes:
  - Neuron: Represents a single neuron with weights and a bias.
  - Layer: Represents a layer of neurons.
  - MLP: Represents a multi-layer perceptron (MLP) consisting of multiple layers

Each of these classes supports a forward pass method (__call__) and a method for retrieving parameters (parameters)

## Acknowledgements
This project was inspired by the Micrograd library by Andrej Karpathy.
