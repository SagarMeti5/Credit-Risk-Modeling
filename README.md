# Credit-Risk-Modeling
Credit Risk Modeling – Loan Default Prediction. Overview This project predicts the probability of loan default (Probability of Default, PD) using historical credit data.   The model helps financial institutions assess creditworthiness and manage risk effectively.
# Credit Risk Modeling – Loan Default Prediction

## Overview
This project predicts the probability of loan default (Probability of Default, PD) using historical credit data.  
The model helps financial institutions assess creditworthiness and manage risk effectively.

---

## Dataset
- *Source:* [Lending Club Loan Data (Kaggle)](https://www.kaggle.com/datasets/wordsforthewise/lending-club)  
- Features: Loan amount, interest rate, credit score, employment, debt-to-income ratio, etc.  
- Target: loan_status → Default (1) or Non-Default (0)  

---

##  Techniques & Tools
- Logistic Regression (baseline model)  
- Handling imbalanced datasets  
- Feature engineering & standardization  
- Python: pandas, numpy, scikit-learn, matplotlib, seaborn  

---

## Steps
1. Data preprocessing & cleaning  
2. Feature selection & transformation  
3. Train-test split (80-20)  
4. Logistic Regression model training  
5. Model evaluation (AUC, Confusion Matrix, Classification Report)  

---

## Results
- Achieved *AUC: ~0.87* on test set  
- Identified key risk factors influencing default probability  

---

## Future Work
- Implement XGBoost / LightGBM for improved performance  
- Deploy as an interactive web app using *Streamlit*  

---

## Author
*Sagar Meti*  
MSc Data Science | Madras School of Economics
