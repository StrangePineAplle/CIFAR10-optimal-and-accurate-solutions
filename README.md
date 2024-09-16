# CIFAR10-optimal-and-accurate-solutions
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![Pytorch](https://img.shields.io/badge/PyTorch-orange)

## Overview

This repository contains two Jupyter notebooks that provide solutions for the CIFAR-10 dataset using two different models: ResNet-9 and Vision Transformer (ViT). The focus is on offering users a choice between a lightweight model with reasonable accuracy and a more complex model that achieves higher accuracy.

### Models

1. **ResNet-9**
   - **Description**: ResNet-9 is a lightweight deep residual network designed for fast image classification. It consists of 9 layers and is optimized for performance on less complex tasks, making it suitable for scenarios where computational resources are limited.
   - **Accuracy**: Achieves approximately **92.5%** accuracy on the CIFAR-10 dataset.
   - **Model Weight**: Lightweight, making it ideal for deployment in resource-constrained environments.

2. **Vision Transformer (ViT)**
   - **Description**: Vision Transformer leverages self-attention mechanisms to process images. It has shown superior performance on various image classification tasks, especially when trained on large datasets.
   - **Accuracy**: Achieves an impressive **97.9%** accuracy on the CIFAR-10 dataset.
   - **Model Weight**: Heavier than ResNet-9, requiring more computational resources but providing significantly better accuracy.

## Comparison

| Model       | Accuracy | Model Weight       |
|-------------|----------|--------------------|
| ResNet-9   | 0.925    | Lightweight         |
| ViT        | 0.979      | Heavier             |

### Key Differences

- **Performance**: While ResNet-9 provides a good balance of speed and accuracy, ViT excels in terms of accuracy at the cost of increased model complexity and resource requirements.
  
- **Use Cases**:
  - Use **ResNet-9** when you need a fast solution that can run efficiently on devices with limited computational power.
  - Choose **ViT** when the highest possible accuracy is required and you have access to sufficient computational resources.
