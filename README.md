# Diagnosis-of-RCC-by-using-CNN

## Overview
This project focuses on the **early diagnosis of Renal Cell Carcinoma (RCC)** using **Convolutional Neural Networks (CNN)** and medical image analysis. The model classifies kidney images into **Normal** and **Tumor** categories to assist in faster and more accurate diagnosis.

The goal of this project is to improve diagnostic efficiency and support healthcare professionals with an AI-powered solution for RCC detection.

---

## Problem Statement
Renal Cell Carcinoma (RCC) is one of the most common types of kidney cancer. Early diagnosis is critical for successful treatment, but manual image analysis can be time-consuming and prone to errors.

This project leverages **Deep Learning (CNN)** to automate the classification process and improve detection accuracy.

---

## Objectives
- Detect RCC from medical image data.
- Classify images into:
  - Normal
  - Tumor
- Improve diagnostic speed and reliability.
- Provide visual insights using performance graphs and predictions.

---

## Features
- Medical image preprocessing
- CNN-based image classification
- Model training and evaluation
- Accuracy/Loss visualization
- Confusion Matrix generation
- Image prediction on test samples
- Early detection support for RCC

---

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn
- Kaggle Notebook / Jupyter Notebook

---

## Dataset
The dataset contains kidney medical images organized into:

```text
dataset/
│── train/
│   ├── normal/
│   └── tumor/
│
└── test/
    ├── normal/
    └── tumor/
