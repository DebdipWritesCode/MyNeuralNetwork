# Heart Disease Prediction Neural Network

## Project Overview
This project implements a custom neural network from scratch using a **sigmoid activation function** and a **linear hypothesis**. The model was trained and tested on the **Heart Disease Dataset**, achieving an accuracy of **65%**.

## Features
- **Custom Neural Network**: Built without relying on high-level libraries, providing a deeper understanding of neural network structure and training.
- **Activation Function**: Utilizes the **sigmoid function** for neuron activations, ideal for binary classification tasks.
- **Dataset**: Tested on the Heart Disease Dataset, offering insight into how neural networks can predict the likelihood of heart disease.

## Technical Details
- **Activation Function**: Sigmoid function
  - Formula: ![sigmoid](https://latex.codecogs.com/svg.latex?%5Csigma%28x%29%3D%5Cfrac%7B1%7D%7B1&plus;e%5E%7B-x%7D%7D)
- **Hypothesis**: Linear hypothesis model, where:
  - Output = Activation(Weights * Input + Biases)
- **Training Parameters**:
  - **Epochs**: 1000
  - **Learning Rate**: 0.01

## Results
The model achieved **65% accuracy** on the test set, showing promising results in predicting heart disease.

## Future Improvements
- **Experiment with more complex architectures** to potentially increase accuracy.
- **Adjust hyperparameters**, such as learning rate and epochs, for performance optimization.
- **Data preprocessing techniques** and normalization could also enhance model performance.
