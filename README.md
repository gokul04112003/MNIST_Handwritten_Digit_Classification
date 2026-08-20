# 🧠 MNIST Handwritten Digit Classification using Neural Networks

## 📌 Project Overview

This project demonstrates the implementation and comparison of Artificial Neural Network (ANN) models for handwritten digit classification using the **MNIST dataset**.

The project covers the complete machine learning workflow, including data loading, data exploration, preprocessing, neural network model building, training, and evaluation.

Multiple neural network architectures and activation functions are experimented with to understand their effect on classification performance.

---

## 🎯 Objective

The main objectives of this project are:

- Understand the fundamentals of Artificial Neural Networks.
- Load and explore the MNIST handwritten digit dataset.
- Perform data preprocessing and normalization.
- Convert image data into a suitable format for an ANN.
- Build different neural network architectures.
- Compare activation functions such as:
  - Sigmoid
  - Tanh
  - ReLU
  - Softmax
- Train the neural networks on handwritten digit images.
- Evaluate model performance on validation and test data.
- Identify the architecture that provides better classification performance.

---

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

The dataset contains:

- **60,000** training images
- **10,000** testing images
- Image size: **28 × 28 pixels**
- Number of classes: **10**
- Classes: digits **0–9**

Each image is converted from a `28 × 28` matrix into **784 input features** for the fully connected neural network.

---

## 🔄 Project Workflow

```text
MNIST Dataset
      ↓
Data Overview
      ↓
Data Preprocessing
      ↓
Train / Validation Split
      ↓
Data Normalization
      ↓
Image Reshaping
      ↓
Target Encoding
      ↓
Model Building
      ↓
Model Compilation
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Digit Prediction
