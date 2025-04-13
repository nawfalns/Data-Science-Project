# Data-Science-Project
Project Ownership
Nawfal Khan Basheer Mohamed
Student ID: 23025098
University of Hertfordshire

# Derivative Acknowledgment
This project is a derivative work based on open-source projects and academic research listed above.
There are no additional contributors; all development, adaptation, and experimentation were done independently.


This repository presents a project built from scratch to compare segmentation models for road segmentation on urban scenes using the Cityscapes dataset. The project evaluates **ResNet-based U-Net** and **U-Net** using key performance metrics—specifically, Intersection over Union (IoU).

---

## Introduction

Segmentation is a crucial task in the fields of autonomous driving and urban scene analysis. In this project, two segmentation architectures are evaluated:

- **U-Net:** An encoder-decoder architecture with skip connections that preserves spatial details while incorporating global context.
- **ResNet-based U-Net:** An enhanced version of U-Net that replaces the standard encoder with a ResNet, utilizing residual learning to improve feature extraction and training stability.

The goal is to determine which architectural design better suits road segmentation tasks under real-world conditions.

---

## Research Question

**How do the segmentation performance metrics (IoU, etc.) of ResNet-based U-Net, U-Net, and other segmentation models compare when applied to road segmentation using the Cityscapes dataset?**

---

## Dataset

The project employs the [Cityscapes dataset](https://www.cityscapes-dataset.com/), known for:
- **High-resolution images** of urban environments.
- **Pixel-level annotations** suitable for semantic segmentation tasks.
- **Predefined training, validation, and test splits** for standardized.
## Models

### U-Net
An encoder-decoder model with skip connections that helps recover fine-grained spatial details while learning high-level features.

### ResNet-based U-Net
A variant of U-Net where the encoder is replaced by a ResNet backbone, leveraging residual connections to enhance feature learning.


## Derivative Acknowledgment

This project is a derivative work inspired by and adapted from the open-source repositories and academic research papers listed in the **Code References** and **Paper References** sections above.  
All development, implementation, and experimentation have been carried out independently by the author. There are no additional contributors.

