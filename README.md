# MNIST Handwritten Digit Classification Using Neural Network

## 📌 Project Overview

This project implements a simple Artificial Neural Network using **TensorFlow and Keras** to classify handwritten digits from **0 to 9** using the MNIST dataset.

The project demonstrates the complete workflow of a neural network:

- Loading the MNIST dataset
- Exploring and visualizing handwritten digit images
- Data preprocessing
- Building a neural network
- Compiling the model
- Training the model
- Evaluating test accuracy
- Visualizing training and validation performance
- Predicting handwritten digits
- Comparing actual and predicted labels
- Performing an experiment by modifying the neural network architecture

---

## 🚀 Open Project in Google Colab

### ▶️ Click here to open the notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Eo6uR3SYX5bS3WCN1LPewH2qo9YotV9Q?usp=sharing)

**[🔗 Open Google Colab Notebook](https://colab.research.google.com/drive/1Eo6uR3SYX5bS3WCN1LPewH2qo9YotV9Q?usp=sharing)**

---

## 📊 Dataset

The **MNIST handwritten digit dataset** contains grayscale images of handwritten digits from 0 to 9.

### Dataset Details

| Property | Value |
|---|---|
| Dataset | MNIST |
| Image Size | 28 × 28 pixels |
| Image Type | Grayscale |
| Number of Classes | 10 |
| Classes | 0–9 |
| Training Images | 60,000 |
| Testing Images | 10,000 |

The dataset is available directly through TensorFlow/Keras.

---

## 🧠 Neural Network Architecture

The neural network used in this project consists of:

```text
Input Image
    ↓
28 × 28 Pixels
    ↓
Flatten Layer
    ↓
Dense Layer - 128 Neurons
    ↓
Dropout - 20%
    ↓
Dense Layer - 64 Neurons
    ↓
Output Layer - 10 Neurons
    ↓
Softmax
    ↓
Predicted Digit (0–9)
