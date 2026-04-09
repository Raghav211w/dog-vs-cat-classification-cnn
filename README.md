# 🐶🐱 Dog vs Cat Image Classification using CNN

## 📌 Overview

This project implements a **Convolutional Neural Network (CNN)** to classify images of dogs and cats.
The model is trained on a real-world dataset and achieves strong performance on unseen validation data.

---

## 📂 Dataset

* Source: Kaggle Dog vs Cat Dataset
* https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset

The dataset contains labeled images belonging to two classes:

* Dog 🐶
* Cat 🐱

---

## ⚙️ Data Handling

* Identified and handled corrupted images in the dataset
* Ensured all images are properly formatted (RGB) for training
* Prepared a clean dataset pipeline for stable model training

---

## 🧠 Model Architecture

The CNN model consists of:

* Convolutional layers for feature extraction
* MaxPooling layers for dimensionality reduction
* Fully connected dense layers for classification
* Activation functions: ReLU and Sigmoid
* Optimizer: Adam
* Loss Function: Binary Crossentropy

---

## 📊 Results

| Metric              | Value      |
| ------------------- | ---------- |
| Training Accuracy   | **0.9438** |
| Validation Accuracy | **0.9306** |
| Training Loss       | **0.1457** |
| Validation Loss     | **0.1701** |

---

## 🚀 Highlights

* Built a complete deep learning pipeline for image classification
* Achieved ~93% validation accuracy using a custom CNN
* Handled real-world dataset issues like corrupted images
* Structured and efficient model training workflow

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* PIL

---

## 🙌 Author

Raghav Gupta
