# 📉 NaijaTel — Customer Churn Analysis

## 📌 Project Overview
An end-to-end customer churn analysis for NaijaTel, a fictional 
Nigerian telecom company. The project combines exploratory data 
analysis, machine learning (Logistic Regression), and an 
interactive Power BI dashboard to identify and predict churning 
customers.

## 🛠️ Tools & Technologies
- *Python* — Pandas, Matplotlib, Seaborn, Scikit-learn
- *Jupyter Notebook* — EDA and ML pipeline
- *Power BI Desktop* — Interactive churn dashboard
- *Git & GitHub* — Version control

## 🤖 Machine Learning Model
- *Algorithm:* Logistic Regression
- *Accuracy:* 86.0%
- *ROC-AUC Score:* 0.884
- *Training samples:* 800 | *Test samples:* 200

## 🔍 Key Findings
- Month-to-Month customers churn at 49.4% vs 10.8% for 12-Month
- Contract Type is the #1 churn predictor
- Network complaints are the #2 churn driver
- Basic plan customers churn at 35.6%
- 238 of 1,000 customers churned (23.8% churn rate)

## 📁 Files
File and Description 

-Churn_Analysis.ipynb | Full ML pipeline notebook 
-naijatel_churn.csv | Raw dataset (1000 customers)
-naijatel_churn_clean.csv | Cleaned dataset 
-NaijaTel_Churn_Dashboard.pbix | Power BI dashboard 
-chart1_churn_eda.png | EDA visualisations 
-chart2_confusion_matrix.png | Model evaluation charts 

## 💡 Business Recommendations
1. Offer incentives to move Month-to-Month customers to 12-Month contracts
2. Fix network quality issues urgently — top churn predictor
3. Create early intervention for customers with 3+ support calls
4. Introduce loyalty rewards for long-tenure customers
5. Upgrade Basic plan customers with better value offers

## 🚀 How to Run
1. Clone the repository
2. Open Churn_Analysis.ipynb in Jupyter Notebook
3. Run all cells sequentially
4. Open NaijaTel_Churn_Dashboard.pbix in Power BI Desktop
