#  Wine Quality Classification Project 🍷

A machine learning project to classify red wine quality based on physicochemical properties.

## Project Overview

This project analyzes a dataset of red wine samples to build classification models that predict whether a wine is "good" (quality ≥ 7) or "bad" (quality < 7) based on its chemical properties.

**Key Features:**
- Data exploration and visualization
- Synthetic data generation for class balancing
- Comparison of 6 machine learning models
- Comprehensive evaluation metrics
- Feature importance analysis

## 📊 Dataset

The dataset contains 1,599 red wine samples with 11 physicochemical features and a quality rating.

Dataset: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

## 📉 Models Evaluated

1. Support Vector Machine (SVM)
2. K-Nearest Neighbors (KNN)
3. Logistic Regression
4. Decision Tree
5. Random Forest
6. Gradient Boosting

## 🚀 How to Run

### 1. Clone and setup
```bash
git clone https://github.com/samarnayyar/Wine-Quality-Classification.git
cd wine-quality-classification
```

### 2. Run the analysis
```bash
jupyter notebook notebooks/Wine_Quality_Analysis.ipynb
```

## Results

The best performing model which was Random Forest achieved 96% accuracy.


## Requirements

Python 3.7+ with packages such as:
```bash
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=0.24.0
jupyter>=1.0.0
