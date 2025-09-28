# Credit-Risk-Modeling
Credit Risk Modeling – Loan Default Prediction. Overview This project predicts the probability of loan default (Probability of Default, PD) using historical credit data.   The model helps financial institutions assess creditworthiness and manage risk effectively.

# Credit Risk Modeling using Lending Club Dataset

## Overview
This project predicts the likelihood of loan defaults using historical Lending Club loan data. It demonstrates **end-to-end data processing**, **feature engineering**, and **machine learning modeling** for credit risk assessment.  

---

## Key Highlights
- Efficient handling of **large datasets (~1.5 GB)** using sampling.  
- Implements **Random Forest** and **Logistic Regression** for classification.  
- Provides **evaluation metrics** including Confusion Matrix, Classification Report, and Feature Importance.  
- Fully reproducible in **Google Colab** using **Google Drive integration**.  

---

## Dataset
- Source: [Lending Club Loan Data on Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club)  
- Contains loan-related information including:  
  - Loan amounts, interest rates, term, grades, employment length, annual income  
  - Credit history features (delinquency, revol_util, total_acc)  
  - Target variable: `loan_status` (Fully Paid or Charged Off)  

---

## Preprocessing Steps
1. Handle missing values and drop irrelevant columns (e.g., IDs).  
2. Encode categorical variables into numeric values using Label Encoding.  
3. Convert `loan_status` to binary:  
   - Fully Paid → 0  
   - Charged Off → 1  
4. Split data into **training and testing sets** (80/20 split).  

---

## Modeling
- **Random Forest Classifier**: Robust, handles multiple features, good for large datasets.  
- **Logistic Regression**: Baseline model for comparison.  
- **Evaluation Metrics**:  
  - Confusion Matrix  
  - Classification Report (Precision, Recall, F1-Score, Accuracy)  
  - Feature Importance visualization (for Random Forest)  

---

## How to Run
1. Upload the dataset to **Google Drive**.  
2. Mount Drive in Colab:


## Future Work

Hyperparameter tuning for Random Forest and Gradient Boosting.
Incorporate rejected applications for richer modeling.
Deploy the model as a web app using Streamlit or Flask.


## Author
*Sagar Meti*  
MSc Data Science | Madras School of Economics
