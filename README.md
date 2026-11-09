# Bottle-Cap-Defect-Detection
Deep Learning-Based Bottle Cap Defect Detection and Classification

## Project Description

This project focuses on the automated detection and classification of bottle cap defects using deep learning techniques.

The objective is to classify bottle cap images into five categories:

- OK: Normal
- ZW: Contamination
- QS: Missing Parts
- HS: Scratch
- AK: Pit

## Dataset

The project uses the bottle_cap subset of the Real-IAD dataset, containing 5,015 images of 1,003 physical bottle caps.

A group-based train-validation-test split is used to prevent data leakage between different camera views of the same physical cap.

## Models

Three models are implemented and compared:

1. Artificial Neural Network (ANN)
2. Convolutional Neural Network (CNN)
3. ResNet18 (Transfer Learning)

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- Macro-F1 Score
- Confusion Matrix

## Results

ResNet18 achieved the best performance in the five-class image-level classification task, reaching 97.22% test accuracy and 0.9697 macro-F1.

## Implementation

The complete implementation and experimental workflow are provided in the Jupyter Notebook included in this repository.
