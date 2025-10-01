# Brain Tumor Segmentation with U-Net

This repository contains an educational implementation of a U-Net based semantic segmentation model for brain tumor detection from CT scans.

---

## Purpose

This project is for **learning purposes only**.  
The model is **not fully trained or optimized**, since training takes a long time.  
The main goal is to understand how semantic segmentation works in medical imaging.

---

## Dataset

- Loaded from **HuggingFace Datasets**.  
- Contains **brain CT images**.  
- Tumor regions are provided as **segmentation masks**.  
- The data is split into **train, validation, and test sets**.

---

## Model Architecture

- Implemented in **TensorFlow / Keras**.  
- **U-Net architecture** is used, commonly applied in biomedical image segmentation.  
- **Input size:** 128x128 RGB images  
- **Output:** Binary mask (tumor = 1, background = 0)

---

## Training

- Preprocessing:
  - Resize images to 128x128
  - Normalize pixel values
  - Generate masks from polygon coordinates
- Train/validation/test splits are prepared
- Training is **partially completed**; results are not
