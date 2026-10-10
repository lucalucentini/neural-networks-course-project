# Neural Networks: Mathematical Foundations and Python Implementations

Course project for **Numerical Mathematics for Machine Learning**, University of Milano-Bicocca, academic year 2024–2025.

This project explores the mathematical foundations of feed-forward and convolutional neural networks through theoretical explanations, Python implementations, and classification experiments. It connects the derivation of learning algorithms with their practical behaviour on synthetic datasets and image classification tasks.

## Contents

### Mathematical foundations
- Feed-forward neural networks, activation functions, and empirical risk minimization.
- Gradient descent and stochastic gradient descent.
- Derivation of backpropagation, with a proof in the appendix.
- Convolutional layers, pooling, and convolutional neural network architectures.

### Python implementations
- A feed-forward neural network implemented from scratch using NumPy, including forward propagation, gradient computation, and parameter updates.
- Feed-forward and convolutional models implemented with TensorFlow/Keras.
- Experiments with different architectures, activation functions, loss functions, and optimizers.
- Evaluation through learning curves, classification accuracy, and confusion matrices.

### Experiments
- **Synthetic datasets:** analysis of decision boundaries and the effects of model and training choices.
- **MNIST:** handwritten digit classification using feed-forward and convolutional networks.
- **CIFAR-10:** image classification experiments examining the limitations of simple CNN architectures.
- **SVHN:** digit recognition in natural images, including a comparison of CNN configurations.

## Main observations

The experiments illustrate how architecture, loss function, and optimizer choices affect convergence and predictive performance. On one synthetic classification task, switching to Adam and cross-entropy enabled effective learning where the initial configuration struggled.

The image classification experiments show that architectures performing well on MNIST do not necessarily transfer successfully to more complex datasets. Results on CIFAR-10 motivate further investigation of deeper architectures, regularization, and data augmentation.

## Report

The PDF report is written in **Italian** and includes mathematical derivations, Python code listings, experimental results, and figures. This README provides an English overview.

The work was completed as part of university laboratory coursework and is presented as an educational project.

## Technologies

Python · NumPy · Matplotlib · TensorFlow/Keras

## Author

Luca Lucentini  
MSc student in Statistical and Economic Sciences, University of Milano-Bicocca
