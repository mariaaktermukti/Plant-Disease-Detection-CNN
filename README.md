# 🌿 Plant Disease Detection using CNN

This project implements a Convolutional Neural Network (CNN) in PyTorch to classify plant diseases from leaf images using the **PlantVillage** dataset.

## 📌 Features
- Custom dataset loader for multi‑class classification
- Data augmentation using `torchvision.transforms`
- CNN architecture with BatchNorm, Dropout, and MaxPooling
- Training and evaluation loops
- Easily switch between **subset** (fast testing) and **full dataset**

## 🗂️ Dataset
- Source: [PlantVillage on Kaggle](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage)
- 38 classes of healthy and diseased leaves
- Original dataset split: train (43,444 images), val (10,861 images)

> ⚠️ The notebook uses a **subset of 100 images per split** for quick testing. To train on the full dataset, change the `Subset` lines in the notebook.

## 🧰 Requirements
Install dependencies:
```bash
pip install torch torchvision kagglehub pillow
