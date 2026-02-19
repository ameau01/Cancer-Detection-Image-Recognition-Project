# Cancer Detection — Histopathologic Image Classification

**Deep Learning-based image classification to detect cancer in histopathology images**

This project aims to addresses:

**Can a deep learning model distinguish between cancerous and normal histology images?**

Automated cancer detection from histopathologic images can:

- Improve diagnostic speed  
- Reduce workload for pathologists  
- Enhance accuracy with scalable prediction  

---

## Project Overview

This project demonstrates the application of convolutional neural networks (CNNs) to classify medical images as cancerous or non-cancerous using real histopathologic tissue samples.

Key components include:

- Data preprocessing & augmentation
- Custom CNN model development
- Transfer learning with state-of-the-art architectures
- Model evaluation and visualization
- Performance analysis and interpretation

---

## Dataset

- Source: Kaggle — Histopathologic Cancer Detection
- Image Format: 3-channel RGB PNG
- Task: Binary image classification
- Classes:
  - `0` – Non-cancerous tissue
  - `1` – Cancerous tissue

The dataset contains thousands of labeled image tiles extracted from histology slides.

---

## Methodology

### Data Preprocessing

- Image resizing & normalization
- Data augmentation:
  - Rotation
  - Flipping
  - Zoom & shift
  - Brightness variations

These augmentations improve generalization.

---

## CNN Neural Network Models

Two modeling approaches are included:

### Custom CNN

- Multiple convolutional & pooling layers
- Batch normalization
- Dropout for regularization

### Transfer Learning

Using pretrained architecture (e.g., ResNet / VGG / EfficientNet) to:

- Leverage feature extraction from large ImageNet models
- Fine-tune for histopathology cancer domain

---

## Results & Key Insights

- Transfer learning models significantly improve performance over custom CNN
- Data augmentation reduces overfitting
- ROC AUC shows model discrimination capacity

## Project Structure
Cancer-Detection-Image-Recognition-Project/

├── input/train_labels.csv.zip

├── histopathologeic-cancer-detection.ipynb

└── README.md
