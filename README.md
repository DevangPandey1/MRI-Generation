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

## Abstract
With over 320,000 new cases diagnosed annually worldwide, brain tumors present a significant global health challenge [1]. Despite the prevalence of these tumors, diagnosis often takes months to attain, leaving a significant lag in treatment initiation. Additionally, the high cost of neuroimaging and the rarity of many brain tumors contribute to a fragmented data landscape, where datasets are often too small or suffer from class imbalances, preventing the development of larger diagnostic models. This research explores how the addition of synthetic data can enhance classification accuracy in brain tumor diagnosis. This study investigates the impact of varying proportions of synthetic data, generated using SD-Turbo, on the classification performance of a ResNet50-based architecture. We tested ResNet50 across eight training conditions with increasing proportions of synthetic MRI tumor images. Our results show that moderate inclusion of synthetic data (up to 50%) led to performance degradation, whereas larger synthetic ratios (≥ 2×) consistently improved all classification metrics. Most notably, synthetic data augmentation at a 1:4 ratio boosted classification accuracy to 94.81%, a 1.3 percent gain over real-data training alone. These findings showcase the potential of integrating synthetic data in enhancing model performance.
---
For questions or collaboration, please contact Devang Pandey @ depa9289@colorado.edu 
