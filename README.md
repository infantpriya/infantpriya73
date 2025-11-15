# infantpriya73
A collection of Python scripts and machine learning experiments.
# Customer Churn Prediction with SHAP Explainability

This project predicts telecom customer churn using Machine Learning and explains model behavior using SHAP (SHapley Additive exPlanations).  
The dataset contains realistic telecom customer data including service usage, contract type, billing details, and churn behavior.

---

## 🚀 Project Features
- Data cleaning & preprocessing  
- Label encoding for categorical features  
- Random Forest classification  
- SHAP explainability (global + local interpretation)  
- Visualizations for feature importance  
- Prediction for new customers  

---

## 📊 Dataset
The dataset used:  
`project_customer_churn_dataset.csv`

Contains:
- customer demographics  
- service reliability  
- monthly & total charges  
- payment and contract info  
- churn label (0 = No, 1 = Yes)

---

## 📘 Notebook
The main analysis is in:  
`notebooks/churn_analysis.ipynb`

It covers:
1. Importing libraries  
2. Loading dataset  
3. EDA (shape, info, summary stats)  
4. Handling missing values  
5. Encoding  
6. Training RandomForest model  
7. Evaluating model  
8. SHAP Global & Local explanations  

---

## 🧠 Model Explainability with SHAP

### Global Interpretability
Shows which features contributed most to churn prediction:
- `shap.summary_plot`

### Local Interpretability
Explains individual customer predictions:
- `shap.force_plot`

---

## 📦 Requirements

Install dependencies:

