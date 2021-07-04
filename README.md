# FeedForward Neural Networks in Deep Learning

## Hey There!

This repo contains my work on studying and building Feed Forward Neural Networks in Python. Until now, I have been working with single neurons using the Sigmoid activation to classify data. These are useful when we work with Binary classification tasks having linealy separable data. It is common however, to be dealing with tasks wherein we might have to do classification into more than two categories or work with data not having a linear boundary. In such cases, neurons are combined to form what is known as a _Neural Network_ such that we can use more complex functions to relate the inputs to the outputs. These networks have a multitude of parameters and hyperparameters, that make them suitable to train on a wide variety of data. The data flows through the network predicting outputs from which a loss is calculated. Based on this value, the weights are updated such that the model can predict better. The process of training these weights involves the use of mathematical concepts of calculus and is known as backpropagation.

The networks in the notebook are built and trained using Python and some basic libraries only. Popular frameworks such as PyTorch or Tensorflow are not used.

Notebook Outline:
- Writing down classes for the Sigmoid Neuron, and training on non-lineraly separable data, depicting its limitations.
- Building a class for a custom feedforward network having 3 neurons, for a binary classification task.
- Training our network on the data which our Sigmoid neuron could not predict.
- Building a class for a general feedforward network, taking number of parameters and hidden layers as inputs.
- Training the general network to predict on our data, showing better results.
- Building a general feedforward network for _Multi Class Classification_ taking parameters, number of output categories and hidden layers as inputs.
- Training on our given data and visualizing results.
- Training our networks on different types of data, for multi class classification.

Data Used in this notebook will be imported from sklearn_datasets.
