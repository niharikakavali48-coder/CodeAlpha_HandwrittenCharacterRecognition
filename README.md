# CodeAlpha_HandwrittenCharacterRecognition
Handwritten Character Recognition using Convolutional Neural Network (CNN) and MNIST dataset.
# Handwritten Character Recognition Using CNN

## CodeAlpha Machine Learning Internship — Task 3

### 📌 Project Overview

This project focuses on recognizing handwritten digits using a Convolutional Neural Network (CNN). The model is trained and evaluated using the MNIST handwritten digit dataset.

### 🎯 Objective

The objective of this project is to develop a deep learning model that can identify handwritten digits from 0 to 9.

### 📊 Dataset

The project uses the MNIST handwritten digit dataset.

- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10 (digits 0–9)

### 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- Jupyter Notebook

### 🧠 Model

A Convolutional Neural Network (CNN) was developed using:

- Conv2D
- MaxPooling2D
- Flatten
- Dense Layers
- ReLU Activation
- Softmax Activation

### 🔄 Project Workflow

```text
MNIST Dataset
      ↓
Data Preprocessing
      ↓
Image Normalization
      ↓
Image Reshaping
      ↓
CNN Model
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Digit Prediction
