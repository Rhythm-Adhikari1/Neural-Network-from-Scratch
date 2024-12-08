# **Neural Network from Scratch**

This project demonstrates how to build a deep neural network (DNN) from scratch using Python and NumPy. The focus is on implementing the core neural network components: architecture, forward and backward propagation, and training with gradient descent. The breast cancer dataset is used as a test case to validate the model's performance on binary classification tasks. However, the emphasis is on the neural network implementation, not on breast cancer detection.

## **Features**

- **Neural Network Architecture**: Multi-layer network with ReLU activation for hidden layers and sigmoid activation for the output layer.
- **Forward Propagation**: Linear transformations followed by ReLU or sigmoid activation functions.
- **Backpropagation**: Gradient computation and weight updates using gradient descent.
- **Cost Function**: Cross-entropy loss function for binary classification tasks.
- **Data Preprocessing**: Standardization of features to ensure optimal training performance.

## **How It Works**

- **Forward Propagation**: Each layer applies a linear transformation to the input, followed by an activation function (ReLU for hidden layers and Sigmoid for the output).
- **Backpropagation**: Gradients are computed for each parameter, and weight updates are performed using gradient descent to minimize the cost function.
- **Training**: The model trains on the dataset over a set number of iterations, gradually improving the parameters.

## **Future Improvements**

- Experiment with deeper architectures and more complex layer configurations.
- Implement hyperparameter tuning to improve model performance.
- Explore regularization techniques such as dropout to prevent overfitting.
