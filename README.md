# 🩺 RSNA Pneumonia Detection

Deep Learning framework for automatic pneumonia detection from chest X-ray images using the **RSNA Pneumonia Detection Challenge** dataset.

---

## 📌 Project Overview

This project proposes several computer vision and deep learning approaches for binary pneumonia classification and compares their performance on the RSNA Pneumonia Detection Challenge dataset.

The following approaches are evaluated:

- HOG + Linear SVM
- ResNet50 (Transfer Learning)
- DenseNet121 (Transfer Learning)
- DenseNet121 + Lung Segmentation (U-Net)
- DenseNet121 + Optuna Hyperparameter Optimization

---

## 📂 Dataset

- RSNA Pneumonia Detection Challenge
- Chest radiographs (DICOM format)
- Binary classification:
  - 0 → No Pneumonia
  - 1 → Pneumonia

---

## 🔬 Project Pipeline

DICOM Images

↓

Intensity Normalization

↓

CLAHE Contrast Enhancement

↓

Data Augmentation

↓


Deep Learning Models

↓

Performance Evaluation

---

## 🧠 Models

- HOG + SVM
- ResNet50
- DenseNet121
- DenseNet121 + Segmentation
- DenseNet121 + Optuna

---

## 📈 Results

| Model | Accuracy | Precision | Recall | F1-score | AUC |
|--------|----------|-----------|--------|----------|------|
| HOG + SVM | 0.666 | 0.672 | 0.648 | 0.659 | — |
| ResNet50 | 0.738 | 0.454 | 0.805 | 0.581 | 0.836 |
| DenseNet121 | **0.802** | **0.547** | 0.698 | 0.614 | 0.865 |
| DenseNet121 + Segmentation | 0.729 | 0.446 | **0.830** | 0.580 | 0.847 |
| DenseNet121 + Optuna | 0.785 | 0.516 | 0.787 | **0.623** | **0.880** |

---

## 🛠 Technologies

- Python
- PyTorch
- TensorFlow / Keras
- OpenCV
- Albumentations
- Optuna
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

---

## 👨‍💻 Author

**Souhail Mdaouer**
