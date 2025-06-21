
# SaaS Churn Dashboard & ML Model Analysis

This repository contains an end-to-end Power BI dashboard and Machine Learning model focused on predicting customer churn in a SaaS business. It includes user behavior analysis, churn insights across regions and plans, and a churn prediction model using XGBoost.

## 🔍 Project Overview

**Objective**:  
To build a data-driven dashboard and machine learning model to identify churn patterns and help stakeholders take proactive retention actions.

**Tools Used**:
- Power BI for data visualization
- Python (XGBoost, SMOTE) for ML modeling
- Excel/CSV for dataset cleaning

---

## 📁 Folder Structure

```
churn_dashboard/
│
├── 01_Dashboard/                        # Power BI files (.pbix)
│
├── 02_Cleaned_Saas_Churn_Dataset/      # Cleaned dataset used for dashboard and ML
│
├── 03_churn_prediction_model/          # Jupyter Notebooks / Python scripts
│
├── 04_Screenshots/                     # Project screenshots
│   ├── 01_Overview.png                 # Dashboard Overview
│   ├── 02_Insights.png                 # User & Feature Analysis
│   └── 03_ML_Report.png                # Churn Prediction Report
```

---

## 📈 Dashboard Highlights

- **Total Users**: 500 | **Churn Rate**: 76.8%
- **Plan Type Breakdown**: Enterprise, Pro, Basic
- **Regional Churn Rate**: Highest in Asia (85.2%)
- **Engagement Metrics**: Avg. login frequency, feature usage, feedback scores
- **User Signup & Activity Trends** over 12 months

---

## 🤖 ML Model Summary

- **Model**: XGBoost Classifier
- **Accuracy**: 81.9% | **F1 Score**: 0.80
- **Top Features**: Region, Plan Type, Tenure, Feature Usage
- **Workflow**: Preprocessing → SMOTE → Model Training → Evaluation → Feature Importance

---

## 📌 How to Use

1. Open the Power BI dashboard from the `01_Dashboard/` folder.
2. View cleaned dataset in `02_Cleaned_Saas_Churn_Dataset/`.
3. Explore ML model scripts or notebook in `03_churn_prediction_model/`.
4. Refer `04_Screenshots/` for project visuals and summaries.

---

## 📸 Screenshots

![Overview](/saas_churn_Dashboard_ML/04_screenshots/01_overview.png)  
![Insights](/saas_churn_Dashboard_ML/04_screenshots/02_Insights.png)  
![ML Report](/saas_churn_Dashboard_ML/04_screenshots/03_ML_report.png)

---

## 🔗 Author

**Jaishree Gandhi**  
Connect on [LinkedIn](https://www.linkedin.com/in/jaishree-gandhi-ab5498357/)

---



