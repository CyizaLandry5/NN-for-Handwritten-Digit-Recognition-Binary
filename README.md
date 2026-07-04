# Neural Networks for Handwritten Digit Recognition, Binary

## Assignment Information

- **Student Name:** Mpayimana Cyiza Landry
- **Assignment Title:** Neural Networks for Handwritten Digit Recognition, Binary
- **School:** Stanford University
- **Course:** Supervised Machine Learning: Regression and Classification

---

## Assignment Overview

In this practice lab, I implemented a neural network to recognize handwritten digits zero and one using binary classification. The assignment covered building neural networks using TensorFlow/Keras, implementing forward propagation from scratch in NumPy, and understanding the differences between scalar, vectorized, and matrix-based implementations.

---

## What I Learned

### 1. **Neural Network Fundamentals**
- Built a 3-layer neural network for binary classification
- Used sigmoid activation functions in all layers
- Understood the architecture: input layer, hidden layers, output layer

### 2. **TensorFlow/Keras Implementation**
- Constructed Sequential models using Keras
- Implemented Dense layers with sigmoid activation
- Compiled models with Binary Crossentropy loss and Adam optimizer
- Trained models using the `fit()` method

### 3. **NumPy Implementation from Scratch**
- Implemented forward propagation without using high-level frameworks
- Built dense layer subroutine using for loops
- Understood the mathematical operations: `z = w·x + b`, `a = g(z)`

### 4. **Vectorization**
- Learned the difference between scalar and vectorized implementations
- Implemented matrix-based operations for efficiency
- Understood NumPy broadcasting for adding bias vectors

### 5. **Model Evaluation**
- Made predictions using trained models
- Applied threshold (0.5) for binary classification
- Visualized predictions and identified errors

---

## What I Accomplished

### ✅ Implemented Core Functions

1. **TensorFlow/Keras Model**
   - Built Sequential model with 3 dense layers
   - Layer 1: 25 units, sigmoid activation
   - Layer 2: 15 units, sigmoid activation
   - Layer 3: 1 unit, sigmoid activation
   - Total parameters: 10,431

2. **NumPy Forward Propagation (my_dense)**
   - Implemented dense layer using for loops
   - Computed `z = dot(w, a_in) + b` for each unit
   - Applied activation function `g(z)`

3. **Vectorized NumPy Implementation (my_dense_v)**
   - Implemented matrix-based dense layer
   - Used `np.matmul()` for matrix multiplication
   - Applied broadcasting for bias addition

### ✅ Built Complete Neural Network

- **Dataset**: 1000 training examples (20×20 pixel images)
- **Features**: 400 (flattened image)
- **Classes**: 2 (digit 0 and digit 1)
- **Training**: 20 epochs with Adam optimizer
- **Accuracy**: ~99-100% on training data

### ✅ Achieved Understanding

- Discovered the power of neural networks for image recognition
- Learned to implement neural networks both with and without TensorFlow
- Understood the importance of vectorization for performance
- Visualized model predictions and identified misclassifications

---
