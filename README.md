# Dimesion_reduction-using-K-means-clustering-for-human-activity

This project implements Human Activity Recognition (HAR) using sensor data from smartphones. The data is processed, reduced in dimensionality using K-means clustering, and then used for classification with Gaussian Naive Bayes.

## Overview

Human Activity Recognition using Smartphones with Dimension Reduction

The goal of this project is to predict human activity based on sensor data from smartphones. We start by preprocessing the data, including feature scaling and dimensionality reduction. After that, we perform classification using the Gaussian Naive Bayes model. We also evaluate the model’s accuracy and performance using a confusion matrix.

### Steps:
1. **Data Loading**: Download the dataset from the UCI Machine Learning Repository and load it.
2. **Data Preprocessing**:
   - Handle missing values.
   - Scale the features using StandardScaler.
   - Encode class labels with LabelEncoder.
3. **Dimensionality Reduction**: Apply K-means clustering to select relevant features.
4. **Model Training**: Train a Gaussian Naive Bayes model using a pipeline.
5. **Evaluation**: Evaluate the model with accuracy and confusion matrix.

## Requirements

The following Python libraries are required:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `scikit-learn` for machine learning models and metrics
- `requests` for downloading datasets
- `BeautifulSoup` for web scraping
- `time` for measuring model training time

To install the required libraries, run:

```bash
pip install -r requirements.txt
python src/main.py

#example output
Accuracy: 0.85
Confusion Matrix:
[[200  50]
 [ 40 210]]
Total Time: 12.34 seconds

