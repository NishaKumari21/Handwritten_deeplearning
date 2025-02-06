# 🧠 MNIST Digit Classification using TensorFlow/Keras

This project builds a simple **Neural Network (NN)** to classify handwritten digits (0-9) using the **MNIST dataset**. The model is implemented using **TensorFlow 2.x** and **Keras**.

---

## 📌 Dataset: MNIST Handwritten Digits
- The MNIST dataset contains **60,000 training images** and **10,000 test images** of handwritten digits (0-9).
- Each image is **28×28 pixels** in grayscale.

---

## 🚀 Model Architecture
This project uses a **simple feedforward neural network (single-layer)**:

- **Input Layer:** 784 neurons (**28×28 pixels flattened**)
- **Dense Layer:** 10 neurons (one for each digit 0-9) with **Sigmoid activation**
- **Loss Function:** `sparse_categorical_crossentropy`
- **Optimizer:** `adam`
- **Evaluation Metric:** Accuracy

---

## 🔧 Installation & Requirements
Before running the project, install the required dependencies:

```bash
pip install tensorflow matplotlib numpy
