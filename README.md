# Fallen Tree Stem Detection from UAV Images

## Overview

This project focuses on detecting fallen tree stems from UAV orthomosaic imagery using deep learning and computer vision techniques.

## Pipeline

```
Orthomosaic
      ↓
Image Tiling
      ↓
Annotation (Roboflow + SAM)
      ↓
U-Net (ResNet34)
      ↓
Threshold Sweep
      ↓
Post-processing
      ↓
Skeletonization
      ↓
Segment Reconnection
      ↓
Evaluation
```

## Model

- U-Net
- ResNet34 Encoder

## Framework

- PyTorch
- segmentation_models_pytorch
- Albumentations
- OpenCV
- scikit-image

## Repository Structure

```
docs/
figures/
notebooks/
src/
```
