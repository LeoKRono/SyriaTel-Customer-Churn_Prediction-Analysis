# 📈 SyriaTel Customer Churn Prediction

This repository contains a machine learning project that predicts customer churn for SyriaTel. It includes data analysis, EDA visualizations, feature engineering, model training, evaluation, and actionable recommendations—all structured in a single notebook: `index.ipynb`.

---

## 🔍 Project Overview

**Objective:** Build predictive models to identify customers likely to churn, enabling SyriaTel to proactively engage high-risk users and reduce attrition rates.

**Approach:**
1. Load and explore the dataset (4,000+ customer records, ~20 features)
2. Visualize churn distribution and key feature correlations
3. Preprocess data (encoding, scaling, train/test split)
4. Train and compare multiple models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
5. Evaluate performance using confusion matrix, classification report, and ROC curves
6. Derive feature importance and business insights

---

## 📊 Key Visualizations & Insights from `index.ipynb`

- **Churn Distribution Bar Chart**  
  Shows percentage of churned vs non-churned customers—revealing class imbalance.

- **Feature Correlation Heatmap**  
  Highlights relationships between features and the target, turning minutes, service calls, and plan subscriptions as initial influencers.

- **Model Comparison Tables and ROC Curves**  
  Demonstrate that ensemble methods (Random Forest, XGBoost) outperform baseline Logistic Regression and Decision Tree.

- **Feature Importance Plot**  
  Shows top contributing factors such as:
  - `number_customer_service_calls`
  - `international_plan`
  - `total_intl_minutes`

These visualizations are embedded within the notebook with interpretation notes.

---

## 🛠️ How to Use This Notebooks

You can run or explore the notebook to reproduce the project's flow:

```bash
git clone https://github.com/LeoKRono/SyriaTel-Customer-Churn_Prediction-Analysis.git
cd SyriaTel-Customer-Churn_Prediction-Analysis
jupyter notebook

