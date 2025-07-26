# 📘 Assignment 2 – Multiclass Classification on MNIST & CIFAR-10 using DNN with Tkinter GUI

This assignment focuses on building deep neural networks (DNNs) for multiclass classification using the MNIST and CIFAR-10 datasets. It includes a Tkinter-based GUI to test the trained model by uploading custom images for real-time predictions.

---

## 🎯 Aim

Develop a multiclass classifier using a deep multilayer perceptron (MLP) with Keras/TensorFlow on the MNIST and CIFAR-10 datasets. Fine-tune model parameters for better accuracy and develop a GUI using Tkinter to upload and test input images.

---

## 🎯 Objectives

1. Learn deep neural network modeling and training on image data.
2. Understand preprocessing techniques like normalization and standardization.
3. Deploy the trained model using a GUI built with Tkinter.
4. Evaluate the model and visualize training performance.

---

## 🧰 Tools & Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  
- scikit-learn  
- Tkinter (for GUI)  

📦 To install these dependencies locally, please refer to the [`requirements.txt`](./requirements.txt) file:
```bash
    pip install -r requirements.txt
```

---

📦 Datasets Used
1. **MNIST** – Handwritten digits (28×28 grayscale images)  
   Source: `tensorflow.keras.datasets.mnist`
2. **CIFAR-10** – Colored images in 10 categories (32×32 RGB images)  
   Source: `tensorflow.keras.datasets.cifar10`

---

# 📊 Model Overview
- **MNIST Model**:
  - Flatten → Dense(512, 256, 128, 128, 64, 32) → Dense(10, softmax)
- **CIFAR-10 Model**:
  - Flatten →  Dense(512, 128, 32) → Dense(10, softmax)
- **Common Parameters**:
  - Activation: ReLU (hidden layers), Softmax (output)
  - Loss Function: Categorical Crossentropy
  - Optimizer: Adam
  - Evaluation Metric: Accuracy

---

# 🧪 Results
- MNIST Test Accuracy: ✅ Achieved strong performance on handwritten digit recognition
- CIFAR-10 Test Accuracy: 📈 Trained and evaluated on 10-class visual objects
- Accuracy and loss graphs are plotted using matplotlib
- GUI successfully loads .jpg images and predicts their class

---

# 🖼 GUI Features (Tkinter)
- GUI allows users to upload a .jpg image
- Image is resized and normalized to match input shape
- Model predicts the class and displays the result in the window
- Built using Python’s built-in Tkinter and Pillow (PIL) libraries

---

# 📁 File Structure
```bash
  Assignment_2/
  ├── mnist_dnn_gui_classifier.ipynb     # Complete code: model + training + Tkinter GUI
  ├── requirements.txt                # Required Python packages
  ├── README.md                       # Project documentation
 
```

# ✅ Topics Covered
- Multiclass image classification using Deep Neural Networks
- Data preprocessing (standardization, normalization, train-test split)
- GUI development using Tkinter for real-time model testing

---

📌 This assignment is part of an ongoing deep learning series and the repository will be updated as I complete more assignments.

