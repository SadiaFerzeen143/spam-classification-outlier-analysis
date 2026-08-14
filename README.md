Spam Classification and Outlier Analysis

Overview

This project implements a machine learning-based spam classification system using an SMS spam dataset.

The project focuses on data preprocessing, missing value analysis, outlier detection and removal, data visualization, and classification model evaluation.

Objectives

- Perform data preprocessing
- Analyze and handle missing values
- Identify duplicate records
- Create numerical features from text messages
- Detect outliers using the IQR method
- Visualize data before and after outlier removal
- Build a spam classification model
- Compare model performance before and after outlier removal

Dataset

The project uses an SMS Spam Collection dataset containing two classes:

- Ham
- Spam

Methodology

The workflow includes:

1. Dataset loading
2. Data exploration
3. Missing value analysis
4. Duplicate removal
5. Label encoding
6. Feature engineering
7. Visualization before outlier removal
8. Outlier detection using IQR
9. Classification before outlier removal
10. Outlier removal
11. Visualization after outlier removal
12. Classification after outlier removal
13. Performance comparison

Machine Learning

The classification pipeline uses:

- TF-IDF Vectorization
- Logistic Regression

Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Before vs After Outlier Removal

The project compares classification performance before and after removing outliers to determine whether extreme feature values affect classification performance.

Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Author

Sadia Ferzeen
