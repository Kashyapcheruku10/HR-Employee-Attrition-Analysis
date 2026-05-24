HR Employee Attrition Analysis
Python + Power BI  End-to-End Data Analysis Project

Overview

An end-to-end HR analytics project analyzing "employee attrition patterns" across 1,470 employees using the IBM HR Analytics dataset. Python was used for data cleaning and exploratory data analysis, and Power BI was used to build an interactive executive dashboard.

Problem Statement

-> Why are employees leaving, and which departments, age groups, and behavioral factors are driving attrition the most?

Tools & Technologies

 Tool                                       Purpose 

 Python (Pandas, NumPy)           Data cleaning and transformation 
 Matplotlib & Seaborn             Statistical visualizations 
 Scikit-learn (Random Forest)     Feature importance analysis
 Power BI Desktop                 Interactive dashboard
 Jupyter Notebook                 Analysis environment


Dataset

- Source: IBM HR Analytics Employee Attrition & Performance (Kaggle)
- 1,470 employees | 35 features
- Link: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset


Key Analyses

- "Overall attrition rate" — company-wide employee turnover measurement
- "Department-wise attrition" — identifying the highest-risk departments
- "Age group analysis" — which age brackets are most likely to leave
- "Overtime impact" — behavioral signal for attrition risk
- "Salary vs attrition" — income gap between employees who left vs stayed
- "Correlation heatmap" — which factors are most linked to attrition
- "Feature importance (Random Forest)" — ML-based ranking of attrition drivers
- "Power BI dashboard" — interactive report with 5 slicers and 7 visuals

Key Findings

| # |                    Insight

| 1 | Overall attrition rate is 16.12% above the healthy industry benchmark of 10–12% 
| 2 | Sales had the highest attrition at 20.63%, followed by HR at 19.05% 
| 3 | Employees aged 18–25 had the highest attrition rate of 34.78% 1 in 3 young employees left 
| 4 | Overtime employees left at 30.53% vs 10.44% for non-overtime, nearly 3x higher 
| 5 | Employees who left earned $2,046/month less than those who stayed ($4,787 vs $6,833) 
| 6 | Monthly Income was the single most important predictor of attrition (importance score: 0.070) 
| 7 | High-risk profile: young + Sales department + low income + overtime = attrition probability above 50% 

Power BI Dashboard Features

- 5 KPI cards: Total Employees, Employees Left, Attrition Rate, Avg Income, Avg Tenure
- 7 interactive visuals: donut chart, bar charts, line chart, column charts
- 5 slicers: Department, Gender, AgeGroup, OverTime, MaritalStatus
- DAX measures for dynamic attrition rate calculation

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/hr-attrition-analysis.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn

# 3. Run the notebook
jupyter notebook notebooks/hr_attrition_analysis.ipynb

# 4. Open the Power BI dashboard
# Open powerbi/hr_dashboard.pbix in Power BI Desktop
```


Connect With Me

LinkedIn: [www.linkedin.com/in/kashyap-cheruku-071012342]
