# Credit Scoring Based on Machine Learning

## Project Overview

This project focuses on developing machine learning models to predict the risk of home equity loan defaults using the Home Equity dataset (HMEQ). The goal is to classify applicants as high-risk (likely to default or become seriously delinquent) or low-risk, leveraging 12 input features. The project encompasses data preprocessing, model selection, hyperparameter tuning, and evaluation to identify the best-performing algorithm for this binary classification task.

## Table of Contents

- [Background](#background)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Model Development](#model-development)
- [Results Evaluation](#results-evaluation)

## Background

Home equity loans are secured loans where borrowers use their home equity as collateral. Lenders face significant risks if borrowers default, making accurate risk assessment critical. Traditional credit scoring methods may not capture nuanced patterns in borrower behavior. Machine learning offers a data-driven approach to improve default prediction by analyzing historical loan performance.

## Dataset

- **Dataset Name**: The Home Equity dataset (HMEQ)
- **Dataset Source**: [HMEQ Link](https://www.kaggle.com/datasets/ajay1735/hmeq-data/data)
- **Dataset content**: The Home Equity dataset (HMEQ) contains baseline and loan performance information for 5,960 recent home equity loans. The target (BAD) is a binary variable indicating whether an applicant eventually defaulted or was seriously delinquent. This adverse outcome occurred in 1,189 cases (20%). For each applicant, 12 input variables were recorded.

## Tech Stack

- **Programming Language**: Python
- **Machine Learning Libraries**: Scikit-learn, TensorFlow
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn

## Model Development

1. Data Preprocessing
   - Handling missing values
   - Handling unbalanced data
   - Feature selection
   - Data normalization

2. Model Selection
   - Random Forest
   - Decision Tree
   - K-Nearest Neighbors
   - Support Vector Machine (SVM)
   - XG Boosting
   - Gradient Boosting Decision Tree (GBDT)

3. Model Training and Optimization
   - Hyperparameter tuning

## Results Evaluation

- Evaluate model performance using accuracy, recall, F1-score, and other metrics.
- Visualize results with confusion matrices.
