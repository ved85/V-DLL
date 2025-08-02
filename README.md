# 🔢 Handwritten Digit Classification using Deep Neural Network (MNIST)

This project implements a **Deep Neural Network (DNN)** trained on the **MNIST** dataset to classify handwritten digits (0–9). It demonstrates the application of deep learning in computer vision using a simple and efficient model architecture.

---

## 🧠 Overview

The **MNIST dataset** consists of 70,000 grayscale images of handwritten digits:

- **60,000** for training
- **10,000** for testing
- Image size: **28×28 pixels**
- Labels: digits **0** through **9**

---

## 📊 Model Architecture

A basic fully connected deep neural network (DNN) with:

| Layer Type     | Output Size | Activation |
|----------------|-------------|------------|
| Input (Flatten)| 784 (28×28) | -          |
| Dense #1       | 512         | ReLU       |
| Output         | 10          | Softmax    |

> Optimizer: `RMSprop`  
> Loss: `categorical_crossentropy`  
> Metrics: `accuracy`

---
## ✅ Results

> Accuracy: 0.98
> Loss: 0.06
