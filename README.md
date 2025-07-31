# Synthetic Brain Tumor MRI Generation

This repository contains code and data for generating synthetic brain tumor MRI images using testing ratios of real to synthetic ratios in classification tasks using Keras ResNet50.

## Project Overview
- **Goal:** Generate realistic synthetic MRI images of brain tumors to support research and model development.
- **Methods:** Fine-tuning Stable Diffusion for image generation and benchmarking with ResNet50-based classification experiments.

## Dataset
- **Total Images:** 3,064
- **Classes:** Meningioma, Glioma, Pituitary Tumor
- **Splits:**
  - Train: 2,144 images (70%)
  - Validation: 612 images (20%)
  - Test: 308 images (10%)

## Repository Structure
- `Experiments/` — Keras ResNet50 experiment notebooks
- `StableDiffusionModel.ipynb` — Main notebook for synthetic image generation
- `Training_Dataset/` — MRI dataset (train/val/test splits)

## Usage
- See the provided Jupyter notebooks for step-by-step instructions on data loading, model training, and image generation.

---
For questions or collaboration, please contact Devang Pandey @ depa9289@colorado.edu 
