# Skin Disease Classification — HAM10000

A deep learning project to classify dermoscopic skin-lesion images as **Benign vs Malignant** using transfer learning.

**Owner:** Akash Adhikary

---

## Overview

This project applies EfficientNetB0 and ResNet50 on the HAM10000 dataset with rich metadata EDA (age, sex, lesion type, localisation) and comparative evaluation.

**Dataset:** [HAM10000 — Skin Cancer MNIST — Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

---

## Project Structure

```
├── Skin_Disease_Classification.ipynb   # Main notebook
└── README.md
```

---

## Pipeline

1. Setup & Imports
2. Dataset Download
3. Metadata EDA — Class, Age, Sex, Localisation
4. Multivariate Analysis
5. Image-level EDA — Colour Stats, Dimensions, Previews
6. Binary Label Mapping (Benign / Malignant)
7. Balanced Subset Construction (~1500 images)
8. Augmentation Pipeline
9. EfficientNetB0 Training
10. ResNet50 Training
11. Comparative Evaluation

---

## Tech Stack

`TensorFlow` · `Keras` · `OpenCV` · `scikit-learn` · `Plotly` · `Seaborn`

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells sequentially
3. A Kaggle account is required for dataset download via `kagglehub`
