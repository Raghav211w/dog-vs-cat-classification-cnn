# 🐶🐱 Dog vs Cat Image Classification using CNN

## 📌 Overview

This project builds a **Convolutional Neural Network (CNN)** to classify images as either dogs or cats.
The model is trained on a real-world dataset and achieves strong performance on validation data.

---

## 📂 Dataset

* Source: Kaggle Dog vs Cat Dataset
* https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset

### Dataset Details:

* Total Images: **25,000**
* Dog Images: **12,500**
* Cat Images: **12,500**
* Balanced dataset across both classes

---

## ⚙️ Data Handling

* Detected and removed corrupted image files
* Standardized all images to RGB format
* Ensured clean and consistent input data for training

---

## 🧠 Model

A custom CNN architecture was used with:

* Convolutional layers for feature extraction
* MaxPooling layers for dimensionality reduction
* Dense layers for classification
* ReLU activation in hidden layers
* Sigmoid activation in output layer
* Optimizer: Adam
* Loss Function: Binary Crossentropy

---

## 📊 Performance

| Metric              | Value      |
| ------------------- | ---------- |
| Training Accuracy   | **0.9438** |
| Validation Accuracy | **0.9306** |
| Training Loss       | **0.1457** |
| Validation Loss     | **0.1701** |

---

## 🚀 Key Points

* Implemented an end-to-end CNN-based image classification pipeline
* Achieved ~93% validation accuracy on unseen data
* Handled real-world dataset issues like corrupted images
* Maintained balanced dataset for unbiased training

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* PIL

---

## 👤 Author

Raghav Gupta
