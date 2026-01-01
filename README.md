# Self-Supervised Learning Project

## Overview
This project explores Self-Supervised Learning (SSL) techniques for image classification using the CIFAR-10 dataset. It was developed as part of the **Deep Learning course at Umeå University**.

The primary objective was to demonstrate how meaningful image representations can be learned without labeled data during the pre-training phase, utilizing data augmentation and contrastive learning principles.

## Methodology
- **Framework:** TensorFlow / Keras
- **Dataset:** CIFAR-10
- **Technique:** Self-Supervised Learning
- **Data Augmentation:** Random cropping, resizing, color jittering (brightness, contrast, saturation, hue)

## Results
The model underwent a two-stage training process:
1. **Self-Supervised Pre-training:** Learning feature representations.
2. **Fine-tuning:** Training a classifier on top of the frozen encoder.

The final model achieved a **Validation Accuracy of approx. 80.1%** on the CIFAR-10 test set.

## Project Structure
- `Umeå_project_ssl.ipynb`: Jupyter Notebook containing the full implementation, from data preprocessing to model evaluation.
- `Deep_learning_report.pdf`: Comprehensive report detailing the theoretical background, experiments, and results.
