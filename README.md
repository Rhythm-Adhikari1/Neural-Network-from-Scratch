Neural Network from Scratch

This project demonstrates how to build a deep neural network (DNN) from scratch using Python and NumPy. The primary focus is on implementing the neural network architecture, forward and backward propagation, and training with gradient descent. The breast cancer dataset is used as a demonstration to show that the neural network works well for binary classification tasks, but the emphasis is on the neural network itself, not on breast cancer detection.

Features

Neural Network Architecture: Multi-layer network with ReLU activation for hidden layers and sigmoid activation for the output layer.

Forward Propagation: Linear transformations followed by ReLU or sigmoid activation functions.

Backpropagation: Gradient computation and weight updates using gradient descent.

Cost Function: Cross-entropy loss function for binary classification.

Data Preprocessing: Standardization of features for optimal training.

How It Works

Forward Propagation: Each layer performs a linear transformation of the input, followed by an activation function (ReLU for hidden layers, Sigmoid for the output).

Backpropagation: Gradients are calculated for the parameters and updated via gradient descent to minimize the cost function.
Training: The model trains on the dataset, iterating over a set number of iterations to improve the parameters.

Future Improvements

Experiment with deeper architectures and additional layers.

Implement hyperparameter tuning for improved performance.

Explore regularization techniques like dropout to prevent overfitting.
