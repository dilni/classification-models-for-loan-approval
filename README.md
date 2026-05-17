# Loan Approval Classification ML Project

## Overview
This project focuses on building and evaluating supervised machine learning models to predict loan approval status. The project compares multiple classification algorithms and applies hyperparameter tuning to improve model performance.

The notebook includes:
- Data preprocessing
- Feature scaling
- Train-test splitting
- Model training
- Model comparison
- Hyperparameter tuning
- Confusion matrix analysis
- ROC-AUC evaluation
- Performance visualization

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## Machine Learning Models

The following classification models were implemented and evaluated:

1. Logistic Regression
2. Gaussian Naive Bayes
3. K-Nearest Neighbors (KNN)

---

## Features Implemented

### Data Preparation
- Loaded cleaned loan dataset
- Defined input features and target variable
- Performed train-test split
- Standardized numerical features using `StandardScaler`

### Model Training
- Logistic Regression model
- Gaussian Naive Bayes model
- KNN baseline model

### Evaluation Metrics
- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

### Hyperparameter Tuning
Used `GridSearchCV` to optimize:
- Number of neighbors (`n_neighbors`)
- Weight strategy (`weights`)

---

## Project Structure

```bash
├── Notebook1.ipynb
├── Notebook3.ipynb
├── cleaned_loan_data.csv
├── README.md
