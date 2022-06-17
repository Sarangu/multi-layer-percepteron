# multi-layer-percepteron
Implement a Implementing a multi-layer perceptron (MLP) 3-class classifier with multiple hidden layers and a regularization on the weights.

## Problem
Objective: To implement a multi-layer perceptron (MLP) 3-class classifier with multiple hidden layers and a regularization on the weights.

Input: Two dimensional input from three separate classes. 

Activiation function: ReLU or leaky ReLU. 

Predictions: Softmax on a linear output layer.

## Implementation and Results

Each layer type (hidden, output, and loss) has been implemented as separate python classes, each with methods for initialization, forward propagation, and backpropagation.
MLP has been implemented as its own class, with separate methods for initialization, adding a layer, forward propagation, backpropagation, training and prediction.

The results shown are:
1. The decision regions of the trained classifier by densely generating points in the plane and color coding these points with the three different labels.
2. Repeat (1) by varying the number of hidden units (3, 8, 16), the number of hidden layers (1 and 3), and the regularization value.
3. Re-use this same network on 4 dimensional iris-flower dataset with 3 class classification.
