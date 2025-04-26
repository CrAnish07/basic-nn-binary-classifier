# Neural Network from Scratch - Insurance Purchase Prediction

This project demonstrates how to build and train a simple neural network **from scratch**, without using any machine learning libraries like TensorFlow or PyTorch. It uses NumPy and core Python logic to train a binary classifier to predict whether a person buys insurance based on their age and affordability.


## 🔢 Neural Network Architecture

- Input layer: 2 neurons (`age`, `affordibility`)
- Hidden layer: no hidden layer
- Output layer: 1 neuron (sigmoid activation)


- ### Activation Functions
- Output layer: Sigmoid


## 🧮 Math Behind the Model

### Forward Propagation

For a single neuron:
z = w·x + b a = sigmoid(z)

Where:
- `w` = weights
- `x` = inputs
- `b` = bias
- `sigmoid(z)` = `1 / (1 + e^(-z))`

### Loss Function

Binary cross-entropy loss:
Loss = -(y * log(a) + (1 - y) * log(1 - a))
