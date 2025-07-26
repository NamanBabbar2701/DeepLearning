# 📘 Assignment 1 – Environment Setup & Binary Classification using TensorFlow/Keras

This assignment focuses on setting up a development environment using platforms like Google Colab, Kaggle, Anaconda, and GitHub, and implementing a binary classification model using deep learning libraries like TensorFlow and Keras.

---

## 🎯 Aim

Develop a binary classifier using deep multilayer perceptron (MLP) with Keras/TensorFlow. Configure and use Google Colab, Kaggle GPU, and GitHub for environment setup and model training.

---

## 🎯 Objectives

1. Learn the configuration of Google Colab, Kaggle, GitHub, and Anaconda.
2. Understand basic usage of deep learning libraries like TensorFlow and Keras.
3. Perform binary classification using real-world dataset.
4. Explore basic model training, evaluation, and result visualization.

---

## 🧰 Tools & Technologies Used

- Python
- TensorFlow / Keras
- Pandas, NumPy, Matplotlib
- Google Colab
- Kaggle (for dataset)
- Git and GitHub

📦 To install these dependencies locally, please refer to the [`requirements.txt`](./requirements.txt) file:
```bash
    pip install -r requirements.txt
```
---

## 📦 Dataset Used

COVID-19 Tweets, Vaccination, and Deaths Data  
Source: [Kaggle Dataset](https://www.kaggle.com/datasets/aryagavande/covid-19-tweets-vaccination-and-deaths-data)

---

## 📊 Model Overview

- Input: Processed and standardized features from the dataset
- Model: Deep Neural Network with 4 dense layers
- Activation Functions: ReLU and Sigmoid
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Evaluation Metrics: Accuracy

---

## 🧪 Results

- Final Test Accuracy: `~58%`
- Visualized training and validation loss/accuracy over epochs

---

## 🔐 How to Generate Kaggle API Token

To use Kaggle datasets in Google Colab or your code, follow these steps to generate and use the Kaggle API token:

### Step-by-step Guide:

1. Go to [https://www.kaggle.com](https://www.kaggle.com) and sign in to your account.
2. Click on your **profile picture** in the top right corner → Go to **"Account"**.
3. Scroll down to the section titled **"API"**.
4. Click the **"Create New API Token"** button.
5. A file named `kaggle.json` will be downloaded. This file contains your username and API key.
6. Upload this file to your Google Colab environment using:
   ```python
   from google.colab import files
   files.upload()
7. Move the file to the appropriate directory and set permissions:
   ```python
    !mkdir -p ~/.kaggle
    !mv kaggle.json ~/.kaggle/
    !chmod 600 ~/.kaggle/kaggle.json
Now you're ready to access Kaggle datasets directly via code!

---

## ✅ Topics Covered

- Deep Neural Network modeling for binary classification
- Environment setup and configuration with Google Colab, Kaggle, and GitHub

---

This assignment is part of an ongoing deep learning series and the repository will be updated as I complete more assignments.
