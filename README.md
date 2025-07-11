# IBM HR Analytics Employee Attrition EDA

## Overview

This project provides a comprehensive Exploratory Data Analysis (EDA) of the IBM HR Analytics Employee Attrition & Performance dataset. The goal is to uncover the factors that lead to employee attrition and explore key questions using data-driven insights and visualizations.

## Dataset

- **Source:** [Kaggle - IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Description:** Fictional dataset created by IBM data scientists to analyze employee attrition.

## Features

- **Data Cleaning:** Handling missing and duplicate values, dropping irrelevant columns.
- **Data Transformation:** Mapping numerical codes to categorical labels for better interpretability.
- **Visualization:** Using Matplotlib, Seaborn, and Plotly for insightful visualizations.
- **Analysis:** Answers to key HR questions about attrition rates by department, job role, job satisfaction, and gender.

## Columns Description

- **Employee Demographics:** Age, Gender, MaritalStatus, Education, EducationField, DistanceFromHome
- **Job & Company Info:** Department, JobRole, JobLevel, BusinessTravel, OverTime, NumCompaniesWorked, TotalWorkingYears, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, YearsWithCurrentManager
- **Performance & Satisfaction:** JobInvolvement, JobSatisfaction, PerformanceRating, EnvironmentSatisfaction, RelationshipSatisfaction, WorkLifeBalance
- **Compensation:** DailyRate, HourlyRate, MonthlyIncome, MonthlyRate, PercentSalaryHike, StockOptionLevel
- **Identifiers & Target:** EmployeeCount, EmployeeNumber, StandardHours, Attrition

## Key Questions Explored

1. What is the overall attrition rate in the company?
2. How does attrition rate vary by department?
3. Which job roles have the highest and lowest attrition rates?
4. How does job satisfaction relate to attrition?
5. Is there a difference in attrition rates between genders?

## How to Run

1. Clone the repository.
2. Ensure you have the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.
3. Place `Employee_Attrition.csv` in the project directory.
4. Open and run [eda.ipynb](d:/M_Developer/DSCondanics/edaproj1/eda.ipynb) in Jupyter Notebook or VS Code.

## Results & Insights

- No missing or duplicate values in the dataset.
- Certain columns were dropped or transformed for better analysis.
- Visualizations reveal patterns in attrition by department, job role, satisfaction, and gender.
- Insights can guide further predictive modeling or HR interventions.
---
Contributions to this project are welcome.
*For more details, see the full analysis in eda.ipynb.*
