# 📊 Telecom Customer Churn Prediction

## 📌 Project Overview
This project focuses on building and evaluating **machine learning models** to predict customer churn in the telecom sector.  
The goal was twofold:
1. Demonstrate **conceptual depth** in ML model building, feature engineering, and evaluation.
2. Connect model outcomes with **business insights** for customer retention strategies.

The dataset contains information on **7,043 customers** with 21 attributes related to demographics, account details, and subscribed services.

---

## ⚙️ Workflow

1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis of categorical and numerical features.
   - Correlation analysis to understand feature-target relationships.

2. **Data Preprocessing**
   - Handling missing values and inconsistent data types.
   - Feature engineering (tenure grouping, contract duration).
   - Categorical encoding (Label Encoding, One-Hot Encoding).
   - Normalization/standardization of numeric variables.

3. **Model Development**
   - Algorithms applied:  
     - Logistic Regression  
     - Random Forest  
     - XGBoost  
     - LightGBM  
     - CatBoost  
   - Baseline vs. feature-engineered datasets for performance comparison.

4. **Model Evaluation**
   - Metrics used: **Accuracy, Precision, Recall, F1-score, ROC-AUC**.
   - Best performing model: **XGBoost with ROC-AUC = 0.85**.

5. **Model Interpretability**
   - Applied **SHAP** and **LIME** for local & global interpretability.
   - Identified key churn drivers:  
     - Short-term contracts  
     - High monthly charges  
     - Low customer tenure  

---

## 📈 Results & Insights
- Feature engineering and scaling improved model robustness and generalization.  
- Tree-based ensemble models (XGBoost, LightGBM) outperformed linear models.  
- Model interpretability provided actionable insights into churn behavior, bridging **ML predictions with business understanding**.  

---

## 🛠️ Tech Stack
- **Python**  
- **pandas, numpy, seaborn, matplotlib** (data analysis & visualization)  
- **scikit-learn** (modeling, preprocessing, evaluation)  
- **XGBoost, LightGBM, CatBoost** (advanced classifiers)  
- **SHAP, LIME** (model interpretability)  

---

## 📂 Repository Structure

