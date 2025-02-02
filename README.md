# Neural-Network-from-Numpy
# MNIST Digit Classification with Neural Network from Scratch
## Description
A simple yet effective neural network implemented from scratch in NumPy to classify handwritten digits from the MNIST dataset. This project demonstrates the complete process of building a neural network from scratch, including forward and backward propagation, training with Stochastic Gradient Descent (SGD), and achieving a 90.6% accuracy.

## 📊 Results

### Sample Predictions vs Actual Labels
| Predictions | 0 | 5 | 1 | 3 | 1 | 5 | 8 | 4 | 6 | 7 |
|-------------|---|---|---|---|---|---|---|---|---|---|
| Actual      | 0 | 5 | 1 | 3 | 1 | 3 | 8 | 4 | 6 | 7 |

**Accuracy**: 90.6%  
*(9/10 correct in this sample, 90.6% overall test accuracy)*

### Performance on Test Set
The neural network performs well on the test set, achieving 90.6% accuracy. This is a good baseline result when training from scratch using basic optimization techniques and without using deep learning frameworks

## 🚀 Features
- Pure NumPy implementation (no ML frameworks)
- Custom neural network with:
  - Input layer (784 neurons)
  - Hidden layer (10 neurons, ReLU activation)
  - Output layer (10 neurons, Softmax activation)
- Training accuracy tracking
- One-hot encoding implementation

## 🔧 Technical Details
Forward Propagation: Matrix operations with ReLU/Softmax

Backward Propagation: Manual gradient calculations

Loss Function: Cross-entropy loss

## 📚 Usage
- Training the Model: The training process can be initiated by running the script. You can experiment with the learning rate and number of epochs to optimize performance.
- Testing the Model: After training, the model will be tested on the test dataset, and accuracy will be printed.

## ⚙️ Configuration
You can modify the following parameters to tune the network:

- Learning Rate: Controls the step size for weight updates.
- Epochs: Number of times the model will iterate over the entire dataset.
- Batch Size: Number of training samples used in each gradient update step.
- Neurons in Hidden Layer: You can experiment with different values for the number of neurons in the hidden layer.

## 🤝 Contribution
Feel free to fork this repository, make changes, and submit a pull request. Contributions are always welcome!
Optimizer: Stochastic Gradient Descent (SGD)

