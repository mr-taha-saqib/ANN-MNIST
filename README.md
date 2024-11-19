# Perceptron Learning and ANN Lab Manual

## Overview  
This lab manual focuses on fundamental concepts in artificial intelligence and machine learning, specifically perceptrons and artificial neural networks (ANNs). Through practical exercises, students will gain hands-on experience in building perceptron-based systems and implementing logic gates, as well as developing and enhancing ANN models for image classification.

---

## Objectives  
After completing this lab, students will be able to:  
- ✔ Understand the single perceptron architecture.  
- ✔ Apply the perceptron learning rule.  
- ✔ Train a perceptron for binary classification tasks.  
- ✔ Implement logic gates (AND, OR) using the perceptron learning scheme.  
- ✔ Build and optimize ANN models for image classification tasks.

---

## Key Topics  

### 1. Single Perceptron  
- **Definition**: A single-layer neural network unit used for supervised learning of binary classifiers.  
- **Types**:  
  - **Single-layer Perceptron**: Suitable for linearly separable patterns.  
  - **Multilayer Perceptron**: Used for more complex patterns with greater processing power.  
- **Function**:  
  - Computes weighted inputs and applies an activation function to produce a binary output.  
  - Output: `1` or `0` (or `1` or `-1` depending on the activation function).  

---

### 2. Perceptron Training Algorithm  
- **Rule**:  
  - Update weights using the formula:  
    ```  
    newW = oldW + (y - ŷ) * X  
    ```  
    where `X` is the input vector, and `y` and `ŷ` are the actual and predicted outputs, respectively.  
- **Focus**: Perceptron learning rule for linearly separable data.  

---

### 3. Logic Gates with Perceptron  
- **AND Gate**: Outputs TRUE (`+1`) if both inputs are TRUE.  
- **OR Gate**: Outputs TRUE (`+1`) if at least one input is TRUE.  
- **Implementation**: Leverages the perceptron learning rule.  

---

### 4. Artificial Neural Networks (ANN)  
- **Definition**: Computational models inspired by biological neural networks.  
- **Structure**:  
  - Input Layer: Accepts raw data.  
  - Hidden Layers: Perform transformations and computations.  
  - Output Layer: Produces predictions.  
- **Training**: Uses the backpropagation algorithm to optimize weights through:  
  - **Forward Pass**: Computes outputs.  
  - **Backward Pass**: Adjusts weights using gradient descent.  
- **Activation Functions**:  
  - Step, Sigmoid, ReLU, Softmax, and others.  

---

### 5. Image Classification with ANN  
- **Dataset**: Fashion-MNIST (60,000 training images, 10,000 test images).  
- **Classes**:  
  - Labels range from `0` (T-shirt/top) to `9` (Ankle boot).  
- **Objective**: Build and optimize a neural network model using scikit-learn.

---
