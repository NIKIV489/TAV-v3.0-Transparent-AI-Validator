
# ⚡ TAV v3.0 — Transparent AI Validator
### Universal AutoML with Intelligent Per-Model Feature Selection

TAV v3.0 is an advanced, interactive AutoML classification system built with Streamlit. 
It enables users to upload any CSV dataset and automatically perform preprocessing, 
model training, evaluation, benchmarking, and model export — all within a single dashboard.

Unlike traditional AutoML systems that focus only on accuracy, 
TAV emphasizes transparency, fairness, reliability, and model comparability.

---

## 🚀 Overview

TAV v3.0 provides an end-to-end machine learning workflow for classification tasks:

- Automated data preprocessing  
- Intelligent feature selection per model  
- Class imbalance handling using SMOTE  
- Multi-model training and benchmarking  
- ROC curve and confusion matrix visualization  
- Cross-validation analysis  
- Exportable trained model and performance report  

Supports both binary and multiclass classification problems.

---

## 🔍 Key Features

### 1. Universal Dataset Support
- Accepts any CSV classification dataset  
- Automatically detects numeric and categorical features  
- Handles mixed-type datasets seamlessly  

### 2. Smart Preprocessing Pipeline
- Missing value imputation  
- Feature scaling  
- Categorical encoding  
- Target label encoding  
- Train-test split before preprocessing (prevents data leakage)  
- Optional SMOTE for class imbalance  

### 3. Per-Model Feature Selection
Supported methods:
- Mutual Information  
- F-Statistic  
- Chi-Square  
- Auto mode (model-specific best strategy)  

### 4. Models Implemented
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  

Each evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  
- Stratified K-Fold Cross Validation  

---

## 🏆 Best Model Selection

Primary metric: ROC-AUC  
Secondary metric: F1 Score  

---

## 📦 Export Options

- Best Model (.pkl) including:
  - Trained model  
  - Preprocessor  
  - Target encoder  
  - Feature selector  

- Model comparison report (.csv)

---

## 🛠 Technology Stack

- Python  
- Streamlit  
- Scikit-learn  
- XGBoost  
- Imbalanced-learn  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- SHAP  

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open in browser:
http://localhost:8501

---

## 📌 Version

TAV v3.0  
Universal AutoML Classification Engine  
Built with Streamlit + Scikit-learn
