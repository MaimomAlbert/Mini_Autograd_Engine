Mini Autograd Engine & Neural Network Framework (Micrograd-Inspired)

A lightweight implementation of an automatic differentiation engine and a minimal neural network library built from scratch in Python.
The project demonstrates how reverse-mode backpropagation works internally using dynamic computation graphs, similar to PyTorch, but at a scalar level for clarity and learning.

🚀 Features

Reverse-mode automatic differentiation (backpropagation)

Dynamic computation graph (DAG) construction

Scalar-based Value engine with gradient tracking

PyTorch-like neural network API

Support for MLPs, ReLU activation, custom loss functions

Training with Stochastic Gradient Descent (SGD)

Computation graph visualization with forward values and gradients
micrograd/
├── engine.py        # Core autograd engine (Value class)
├── nn.py            # Neural network modules (Neuron, Layer, MLP)
├── demo.ipynb       # Binary classification demo
├── trace_graph.ipynb# Computation graph visualization
└── README.md
