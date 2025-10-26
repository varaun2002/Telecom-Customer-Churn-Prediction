# Telecom Customer Churn Prediction (Python)

Predict customer churn in the telecom industry using Python.  
This project demonstrates a complete end-to-end machine learning workflow — from data preprocessing and exploratory analysis to model training, evaluation, and interpretation.

---

## Files
- `telecom_customer_churn.csv` — Source dataset containing customer records.  
- `DSPM_HW2_vbgandhi.ipynb` — Jupyter notebook performing model building, evaluation, and interpretation.  
- `telecom_churn_model.py` — Python script implementing the ML pipeline for churn prediction.

---

## Objectives
- Clean and preprocess telecom customer data for model readiness.  
- Analyze churn patterns across demographics and service attributes.  
- Engineer predictive features to improve model accuracy.  
- Train and compare multiple classification models for churn prediction.  
- Evaluate model performance using key metrics and visualizations.

---

## Tech Stack
- **Language:** Python 3.12  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- **IDE:** VS Code / Jupyter Notebook  

---

## Workflow
1. **Load & Inspect:** Import CSV and explore structure, data types, and missing values.  
2. **Clean:** Handle nulls, outliers, and categorical encodings (e.g., contract type, payment method).  
3. **Feature Engineering:** Create derived variables like total charges per tenure and binary churn flags.  
4. **EDA:** Visualize churn distribution and feature correlations.  
5. **Model Training:** Build Logistic Regression, Decision Tree, and Random Forest models.  
6. **Model Evaluation:** Assess performance using confusion matrix, ROC curve, and F1-score.  
7. **Interpretation:** Identify top predictors of churn (e.g., tenure, monthly charges).
