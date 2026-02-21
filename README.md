# 🚗 Waze User Churn Prediction  
### End-to-End Machine Learning Project

---

## 📌 Project Summary

Built a churn prediction model on 14,999 Waze users that improved churn detection from **9% (baseline)** to **~50% recall** using XGBoost with threshold optimization.

The objective was to identify high-risk users and support data-driven retention strategies.

---

## 📊 Dataset Overview

- 14,999 user-level records  
- 13 behavioral features  
- Churn rate: **17.7%**  
- Retention rate: **82.3%**  
- Moderate class imbalance  

---

## 🔎 Approach

### 1️⃣ Data Preparation

- Data inspection and missing value handling  
- Feature selection and preprocessing  
- Train-validation-test split  
- Class imbalance analysis  

### 2️⃣ Exploratory Data Analysis

- Behavioral trend analysis  
- Device-based usage comparison  
- Engagement distribution insights  

### 3️⃣ Statistical Validation

- Welch’s t-test to compare device behavior groups  
- Confirmed statistically significant behavioral differences  

### 4️⃣ Modeling

- Logistic Regression (baseline)  
- Random Forest  
- XGBoost  

---

## 📊 Model Performance (Test Set)

| Model | Precision | Recall | F1 Score | Accuracy |
|-------|-----------|--------|----------|----------|
| Logistic Regression | 0.52 | 0.09 | 0.16 | 82% |
| Random Forest | 0.445 | 0.120 | 0.189 | 81.75% |
| XGBoost | 0.424 | 0.181 | 0.254 | 81.12% |
| **XGBoost (Optimized Threshold = 0.194)** | **0.293** | **0.499** | **0.369** | 69.79% |

---

## 🎯 Key Results

- Logistic Regression detected only 9% of churners  
- XGBoost improved churn recall to 18%  
- Threshold optimization increased churn detection to ~50%  
- Achieved 5x improvement in churn recall  

---

## 🏆 Final Model Recommendation

XGBoost with optimized decision threshold (0.194)

- Highest churn recall (~50%)  
- Best F1 score  
- Business-aligned performance tuning  
- Strong generalization across validation and test sets  

---

## 💼 Business Impact

If deployed, this model enables:

- Proactive churn prevention  
- Targeted retention campaigns  
- Improved marketing resource allocation  
- Reduced missed churn opportunities  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- SciPy  
- Matplotlib  
- Seaborn  

---

## 🔥 Resume-Ready Summary

Built an end-to-end churn prediction pipeline on 15K Waze users using Logistic Regression, Random Forest, and XGBoost. Improved churn detection from 9% to ~50% through threshold optimization, delivering a business-aligned model for targeted retention strategies.hold optimization, delivering a business-aligned model for targeted retention strategies.
