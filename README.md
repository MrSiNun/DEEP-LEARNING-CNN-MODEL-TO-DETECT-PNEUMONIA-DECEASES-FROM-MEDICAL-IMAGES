# DEEP-LEARNING-CNN-MODEL-TO-DETECT-PNEUMONIA-DECEASES-FROM-MEDICAL-IMAGES
Automated methods to detect pneumonia diseases from medical images.
# Pneumonia Detection Using Convolutional Neural Networks (CNNs)

This repository contains the implementation of a project to detect pneumonia from chest X-ray images using state-of-the-art deep learning techniques. It is developed as part of the MSc Data Science and AI course at the University of Liverpool.

## Table of Contents
1. [Introduction](#introduction)
2. [Repository Structure](#repository-structure)
3. [Getting Started](#getting-started)
4. [Usage](#usage)
5. [Contributors](#contributors)

## Introduction
The project explores three different approaches to train CNN models:
1. Class Weight Adjustment to handle imbalanced datasets.
2. K-Fold Cross-Validation to ensure model generalizability.
3. Transfer Learning using ResNet15 for leveraging pre-trained models.

### Dataset
The dataset is sourced from Kaggle and consists of 5,856 chest X-ray images categorized into "Normal" and "Pneumonia."

## Repository Structure
├── data/ │ ├── raw/ # Original dataset │ ├── processed/ # Preprocessed data ├── notebooks/ │ ├── chapter3_class_weights.ipynb │ ├── chapter4_kfold_validation.ipynb │ ├── chapter5_transfer_learning.ipynb ├── models/ # Trained model files ├── reports/ │ └── CSCK506_EMA_GroupC_Report.pdf ├── results/ # Performance metrics and plots ├── scripts/ │ └── preprocess.py │ └── train_model.py └── README.md

## Getting Started
### Prerequisites
- Python 3.8+
- TensorFlow 2.5+
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pneumonia-detection-cnn.git

## Getting Started
### Prerequisites
- Python 3.8+
- TensorFlow 2.5+
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pneumonia-detection-cnn.git

## Getting Started
### Prerequisites
- Python 3.8+
- TensorFlow 2.5+
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pneumonia-detection-cnn.git

## Getting Started
### Prerequisites
- Python 3.8+
- TensorFlow 2.5+
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pneumonia-detection-cnn.git
pip install -r requirements.txt
Dataset
Download the Kaggle dataset and place it in the data/raw/ directory.

Usage
Run the preprocessing scriptpython scripts/preprocess.py
python scripts/preprocess.py
jupyter notebook
Evaluate models using the saved outputs in the results/ directory.
Contributors
Sinan Bilir - Lead Developer
Tsz Yeung Cheng
Omar Hussein
Zsuzsanna Sándor
Saniya Yesmakanova
License
This project is licensed under the MIT License. See the LICENSE file for details.

Copy code





