# micrograd
micrograd is an Autograd engine that implements backpropagration (reverse automatic differentiation) to train a neural network to predict the desired scalar values.
The neural network deals with zero-dimensional tensors (scalar values) only. 
An additional open-source library called graphviz was also used to visualize the DAGs (Directed Acyclic Graphs).
The activation function of choice was the hyperbolic tangent function (tanh(x)), though the exercise implements softmax.
