# Automated-Galaxy-Classification

This repository contains the implementation for a galaxy image classification project developed as part of a Machine Learning course assignment. The objective is to classify galaxy images into four morphological classes using both traditional machine learning techniques and deep learning models.

## 📁 Notebooks Included

| File | Description |
|------|-------------|
| `Galaxy_classification_LR1_LR3_SVM3.ipynb` | Logistic Regression (LR1, LR3) and Support Vector Machine (SVM3) models using hand-crafted features |
| `Galaxy_classification_CNN_RGB.ipynb` | Convolutional Neural Network (CNN) trained on raw RGB images |
| `Galaxy_classification_CNN_grayscale.ipynb` | CNN trained on grayscale images to test performance without color |

---

## 📌 Project Overview

### 🔭 Problem
Classify galaxy images into four categories:
- Spiral  
- Barred Spiral  
- Elliptical  
- Irregular  

### 🧠 Methods Used
- **Logistic Regression (LR1, LR3)** with color histograms and texture features
- **Support Vector Machine (SVM)** with structured feature inputs
- **Convolutional Neural Networks (CNNs)** using raw image data (RGB and Grayscale)

### 🗂 Dataset
- 11,000 galaxy images (224×224 pixels)
- Pre-split into:
  - **Training set:** 10,000 images (2,500/class)
  - **Test set:** 1,000 images (250/class)

---

## 🛠️ Setup & Dependencies

These notebooks require:

- Python 3.8+
- PyTorch
- torchvision
- matplotlib
- numpy

You can install dependencies using:

```bash
pip install torch torchvision matplotlib numpy

