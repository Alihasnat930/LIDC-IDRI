# Lung Nodule Classifier (LIDC-IDRI)

This project uses a Convolutional Neural Network (CNN) to classify lung nodules as benign or malignant using the LIDC-IDRI dataset.

#📁 Dataset

- Source: [LIDC-IDRI - The Cancer Imaging Archive (TCIA)](https://www.kaggle.com/datasets/zhangweiled/lidcidri)
- Format: Preprocessed PNG images (e.g., `slice-0.png`)
- Directory structure:

# Model
CNN with:

Conv2D, MaxPooling, BatchNorm, Dense layers

Input size: 128x128 grayscale

Augmentation: rotation, flip, shift

Output: 2 classes (binary classification)

# Output
Trained model saved as: lidc_final_model.h5

Accuracy: ~62% (can be improved with proper labels)

# Notes
Currently uses random labels. Replace with true labels for real medical classification.

Works with PNG slices derived from CT scans.

Download model: [Model file](https://www.kaggle.com/code/syedalihasnat/lidc-idri-model/output)
