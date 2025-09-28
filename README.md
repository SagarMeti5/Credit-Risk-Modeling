# Credit-Risk-Modeling
Credit Risk Modeling – Loan Default Prediction. Overview This project predicts the probability of loan default (Probability of Default, PD) using historical credit data.   The model helps financial institutions assess creditworthiness and manage risk effectively.
# Credit Risk Modeling – Loan Default Prediction

Credit Risk Modeling with Lending Club Dataset
Project Overview

This project predicts the probability of loan default using historical loan data from Lending Club. It demonstrates data preprocessing, exploratory data analysis, feature engineering, and machine learning modeling to build a robust credit risk model.

Key Features

Handles large datasets efficiently using sampling and preprocessing.

Implements both Random Forest and Logistic Regression models for classification.

Provides evaluation metrics: Confusion Matrix, Classification Report, and Feature Importance.

Fully reproducible in Google Colab using Google Drive integration.

Dataset

Source: Lending Club Loan Data

Size: ~1.5 GB (CSV)

Includes information on loan amounts, interest rates, employment length, credit grades, and loan status.

Preprocessing Steps

Handle missing values and drop irrelevant columns (e.g., IDs).

Encode categorical variables into numeric values.

Convert target variable (loan_status) to binary:

Fully Paid → 0

Charged Off → 1

Scale numeric features if needed.

Split data into training and testing sets.

Modeling

Random Forest Classifier: Handles large datasets with multiple features, robust to overfitting.

Logistic Regression: Simple baseline model for comparison.

Evaluated using:

Confusion Matrix

Classification Report (Precision, Recall, F1-Score, Accuracy)

Feature Importance (for Random Forest)

How to Run

Upload dataset to Google Drive.

Mount Drive in Colab:

Update the file_path variable in the notebook to point to your CSV.

Run cells step by step:

Load dataset

Preprocess

Train models

Evaluate results

Requirements

Python 3.x

Pandas

Scikit-learn

Matplotlib / Seaborn (optional for visualization)

Install missing packages in Colab:

!pip install pandas scikit-learn matplotlib seaborn

Project Structure
credit_risk_model/
├── README.md
├── credit_risk_model.ipynb   # Main Colab notebook
├── data/                     # Folder to store dataset

Future Work

Hyperparameter tuning for Random Forest and Gradient Boosting.

Incorporate more features from rejected applications.

Deploy as a web app using Streamlit or Flask.

## Author
*Sagar Meti*  
MSc Data Science | Madras School of Economics
