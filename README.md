# MSRA-CNN: A Multi-Scale Residual Squeeze-and-Excitation Network for Explainable Brain Tumor Classification in MRI

## Overview

This project presents a custom deep learning architecture for multiclass brain tumor classification using MRI images.

### Key Features

- Multi-Scale Convolution Block
- Residual Connections
- Squeeze-and-Excitation (SE) Attention
- Batch Normalization
- Global Average Pooling
- Mixed Precision Training
- Grad-CAM Explainability

## Dataset
dataset link: https://drive.google.com/file/d/1OPUSnue5Kj0jjgOnSmE4Cbzu9jYztZJG/view?usp=drive_link

Classes:
- Glioma
- Meningioma
- No Tumor
- Pituitary

Image Size: 224×224

## Model Performance

| Metric | Value |
|----------|----------|
| Accuracy | 99.31% |
| Precision | 99.31% |
| Recall | 99.31% |
| F1 Score | 99.31% |
| Kappa Score | 0.9905 |
| MCC | 0.9905 |

## Model Complexity

Total Parameters: 4.7 Million

## Explainability

Grad-CAM visualization is used to highlight tumor-relevant regions in MRI images, improving model interpretability.

## Author

akila ibnath
