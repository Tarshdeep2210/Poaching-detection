# Wildlife Poaching Risk Prediction System

A deep learning–based wildlife surveillance system designed to identify poaching risk using image classification and synthetic data generation.

## Overview

Wildlife conservation efforts often face limited surveillance coverage and severe class imbalance due to the scarcity of poacher images.

This project addresses that challenge by generating synthetic surveillance data and training a computer vision model capable of classifying wildlife monitoring images into meaningful categories.

## Objective

Develop an intelligent image classification pipeline capable of identifying:

- Animal
- Empty Scene
- Poacher

while improving robustness through augmentation, synthetic data generation, and explainable AI techniques.

---

## Features

- Multi-class wildlife image classification
- Synthetic poacher image generation
- EfficientNet / EfficientNetV2 transfer learning
- Data augmentation pipeline
- Class imbalance handling using class weighting
- Model explainability using Grad-CAM
- Evaluation using ROC, Precision–Recall Curves, and Confusion Matrix

---

## Tech Stack

### Languages
- Python

### Frameworks & Libraries
- TensorFlow
- EfficientNet / EfficientNetV2
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Project Workflow

### 1. Data Preparation
- Organize wildlife surveillance dataset
- Create train / validation / test splits

### 2. Synthetic Data Generation
- Generate synthetic poacher images
- Combine human cutouts with wildlife backgrounds

### 3. Data Processing
- Resize and normalize images
- Apply augmentation techniques

### 4. Model Training
- Train EfficientNet-based classifier
- Apply class balancing techniques

### 5. Evaluation

Generate:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curves
- Precision–Recall Curves
- Confusion Matrix

### 6. Explainability
- Visualize model attention using Grad-CAM

---

## Repository Structure

```plaintext
Poaching-detection/
│
├── notebooks/
├── dataset/
├── outputs/
├── models/
├── README.md
└── requirements.txt
```

---

## Installation

Clone repository:

```bash
git clone <repo-url>
cd Poaching-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run

Open notebooks and execute cells sequentially.

```bash
jupyter notebook
```

---

## Future Improvements

- Real-time wildlife monitoring
- Edge-device deployment
- Video surveillance support
- Temporal event detection
- Deployment using APIs
