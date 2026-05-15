# CNN-Based Surface Defect Classification

## Project Overview

This project focuses on solving a computer vision image classification problem using Convolutional Neural Networks (CNNs).

The dataset contains four classes of surface conditions:
- dent
- normal
- scratch
- stain

The objective of the project is to train a CNN model capable of automatically classifying surface defects from images.

---

# Problem Type

This project represents a **multi-class image classification** problem because each image belongs to one predefined category.

---

# Dataset Details

The dataset contains:
- 4 image classes
- 120 images per class
- Total images: 480
- Image size: 96 × 96 pixels

Classes:
- dent
- normal
- scratch
- stain

The dataset is balanced since all classes contain an equal number of images.

---

# Image Preprocessing

The following preprocessing techniques were applied:
- image normalization
- training-validation split
- data augmentation
- resizing images to fixed dimensions

---

# CNN Architecture

The CNN model includes:
- Convolution layers
- ReLU activation functions
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

---

# Model Performance

The CNN model achieved strong classification performance on the validation dataset.

Key results:
- Training Accuracy: ~86%
- Validation Accuracy: ~91%

---

# Results

## Accuracy and Loss Curves
The training and validation curves show continuous improvement in model learning performance.

## Confusion Matrix
The confusion matrix demonstrates strong class-wise prediction accuracy with only minor misclassifications.

## Sample Predictions
The CNN model successfully classified most defect images correctly.

---

# CNN Concepts Explained

## What is Convolution?
Convolution helps CNNs extract visual features such as edges, textures, and patterns from images.

## Why is Pooling Used?
Pooling reduces feature map dimensions and improves computational efficiency.

## Why is ReLU Used?
ReLU introduces non-linearity and improves deep learning performance.

## Why are CNNs Better for Images?
CNNs preserve spatial image information and automatically learn visual features.

---

# Business Use Case

This type of CNN-based defect detection system can be used in manufacturing industries for automated quality inspection and defect detection.

---

# Repository Structure

```text id="z8cny8"
part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
├── sample_predictions/
│   └── prediction_outputs.png
│
└── results/
    ├── accuracy_loss_curves.png
    └── confusion_matrix.png
