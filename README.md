# 🧠 CNN-Based Detection and Multi-class Classification of Brain Tumors in MRI Scans

This project implements a Convolutional Neural Network (CNN) to automatically detect and classify brain tumors from MRI scans. The model distinguishes between **Glioma**, **Meningioma**, **Pituitary Tumor**, and **No Tumor** classes using deep learning.

---

## 🔍 Objective

- Detect presence of brain tumors in MRI scans.
- Classify the tumor type into 4 categories.
- Provide a lightweight, automated solution for early diagnosis support.

---

## 🧠 Tumor Classes

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

---

## 📂 Dataset

- Publicly available brain MRI dataset.
- Consists of 3000+ labeled MRI images.
- Data is split into training, validation, and test sets.

---

## ⚙️ Tech Stack

- Python 🐍
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- Matplotlib / Seaborn

---

## 🏗️ Model Architecture

- Input Layer: 128x128 grayscale MRI images
- 4 Convolutional layers + MaxPooling
- Dropout layers for regularization
- Fully connected Dense layers
- Softmax output layer for multi-class classification

---

## 📈 Results

| Metric     | Value |
|------------|-------|
| Accuracy   | 95%  |
| Precision  | High  |
| Recall     | High  |
| F1 Score   | High  |

---

## 📊 Visuals

- Training vs Validation Accuracy and Loss plots  
- Confusion matrix for multi-class prediction  
- Sample prediction results on test MRI images
