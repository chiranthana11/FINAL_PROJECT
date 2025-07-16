# HR Analytics – Predict Employee Attrition

## Project Overview

This project aims to analyze HR data to identify the key drivers of employee attrition and predict which employees are at risk of leaving. The outcome helps HR professionals and business users make informed, data-driven decisions to improve employee retention.

The solution combines Exploratory Data Analysis (EDA), Machine Learning classification, SHAP value interpretation, and a Power BI dashboard for interactive insights.


## Dataset

**Source:** IBM HR Analytics Employee Attrition Dataset  
**Features include:**  
- Demographics (Age, Gender, Marital Status)  
- Job Details (Job Role, Department, Monthly Income, Distance From Home)  
- Work Environment (Overtime, Job Satisfaction, Work-Life Balance)  
- Performance Ratings and Attrition status (Yes/No)

## Tools & Technologies

- **Python** (Pandas, Seaborn, Matplotlib, Scikit-learn, SHAP)
- **Power BI** (Dashboard Creation)
- **Jupyter Notebook** (Code Execution & Analysis)

## Key Steps

1. **Data Preparation and EDA**  
   - Cleaned the dataset, removed constant columns, encoded categorical variables, and visualized attrition trends by age, income, job role, department, and overtime status.

2. **Model Building**  
   - Trained a Random Forest Classifier to predict employee attrition.
   - Evaluated performance using confusion matrix and classification report.

3. **Model Explainability with SHAP**  
   - Used SHAP to interpret feature impact on model predictions.
   - Identified overtime, monthly income, job role, and distance from home as major drivers.

4. **Power BI Dashboard**  
   - Created an interactive dashboard with visualizations like:
     - Attrition by Department and Job Role
     - Overtime vs Attrition
     - Age and Income impact
     - Gender distribution
   - Included slicers for dynamic filtering.

## Results & Insights

- Employees with overtime, low salaries, and certain job roles (e.g., Sales Executive, Lab Technician) are more likely to leave.
- The model offers solid accuracy and clear feature importance using SHAP.
- The dashboard provides HR teams with actionable, easy-to-read insights.
