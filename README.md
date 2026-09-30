# Deep Learning-Based Robust and Explainable Wheat and Rice Disease Classification under Image Degradations

This repository contains the reproducibility materials for the study:

**Deep Learning-Based Robust and Explainable Wheat and Rice Disease Classification under Image Degradations: A Cloud–Edge-Oriented Evaluation**

## Study Overview

This study presents a systematic evaluation of deep learning models for wheat and rice disease classification under clean and controlled degraded-image conditions.

The study evaluates:

- EfficientNet-B0
- MobileNetV2
- Degradation-aware EfficientNet-B0

The evaluation includes:

- Clean-test classification performance
- Gaussian blur robustness
- Brightness variation robustness
- JPEG compression robustness
- Class-wise F1-score analysis
- Confusion matrices
- Grad-CAM explainability
- Computational efficiency
- Cloud–edge-oriented deployment analysis

## Reproducibility

The experiments use fixed experimental splits and a random seed of 42.

The main experimental notebook is provided in:

`notebooks/wheat-rice-degradation.ipynb`

## Datasets

### Wheat
Wheat Plant Diseases Dataset
https://www.kaggle.com/datasets/kushagra3204/wheat-plant-diseases

### Rice
Paddy Doctor: Paddy Disease Classification
https://www.kaggle.com/competitions/paddy-disease-classification

## Results

Final experimental tables and figures are provided in the `results/` directory.

## Hardware

Computational benchmarking was performed using an NVIDIA Tesla T4 GPU with CUDA.

## Cloud–Edge Analysis

CPU inference was used as an edge-side proxy, while NVIDIA Tesla T4 inference was used as a cloud/GPU proxy.

Image transmission times were estimated from JPEG payload size and nominal network bandwidths.

## Citation

If you use this repository or the associated experimental materials, please cite the corresponding research paper.
