# Week 1 Internship Task: Data Acquisition, Cleaning, and Exploratory Data Analysis

## Author

**Kora Ahalya**  
B.Tech Artificial Intelligence and Data Science  
Jansons Institute of Technology

## Project Overview

This project was completed as part of my Week 1 internship task. The main objective was to perform the basic data science workflow of data acquisition, data cleaning, preprocessing, and exploratory data analysis (EDA) using Python.

For this project, the IBM HR Analytics Employee Attrition & Performance dataset was used. The dataset contains employee-related information that can be used to understand patterns associated with employee attrition.

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance

**Domain:** Human Resources / Employee Attrition

**Original Dataset Size:** 1,470 rows and 35 columns

The dataset contains information related to:

- Age
- Attrition
- Business Travel
- Department
- Distance From Home
- Education
- Education Field
- Gender
- Job Involvement
- Job Level
- Job Role
- Job Satisfaction
- Monthly Income
- Overtime
- Performance Rating
- Relationship Satisfaction
- Total Working Years
- Training Times Last Year
- Work-Life Balance
- Years at Company
- Years in Current Role
- Years Since Last Promotion
- Years With Current Manager

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning and Preprocessing

The following data-cleaning steps were performed:

1. Inspected the dataset structure using Pandas.
2. Checked the number of rows and columns.
3. Checked column names and data types.
4. Checked for missing values.
5. Checked for duplicate records.
6. Identified columns containing constant values.
7. Removed `EmployeeCount` because it contains only one unique value.
8. Removed `Over18` because it contains only one unique value.
9. Removed `StandardHours` because it contains only one unique value.
10. Removed `EmployeeNumber` because it is an identifier and does not provide useful analytical information.
11. Performed final validation after cleaning.
12. Saved the cleaned dataset as `cleaned_employee_attrition.csv`.

The final cleaned dataset contains 1,470 rows and 31 columns.

## Exploratory Data Analysis

Seven visualizations were created during the exploratory analysis.

### 1. Employee Attrition Distribution

This visualization shows the distribution of employees who stayed with the organization and employees who left.

### 2. Employee Attrition by Department

This visualization compares employee attrition across different departments.

### 3. Overtime vs Attrition

This visualization examines the relationship between overtime status and employee attrition.

### 4. Monthly Income vs Attrition

This visualization compares the monthly-income distributions of employees who stayed and employees who left.

### 5. Correlation Heatmap

The correlation heatmap shows relationships between numerical variables in the dataset.

### 6. Job Satisfaction vs Attrition

This visualization compares employee attrition across different job-satisfaction levels.

### 7. Work-Life Balance vs Attrition

This visualization compares employee attrition across different work-life-balance levels.

## Key Insights

- The Attrition variable is imbalanced, with more employees staying than leaving.
- Employees who work overtime show a higher attrition proportion than employees who do not work overtime.
- Monthly income distributions differ between employees who left and employees who stayed.
- Attrition proportions vary across different job-satisfaction levels.
- Attrition proportions also vary across different work-life-balance levels.
- The correlation heatmap shows relationships between several numerical employee characteristics.

These findings represent associations observed in the dataset and do not prove causal relationships.

## Repository Contents

```text
week-1-employee-attrition-eda/
│
├── README.md
├── cleaned_employee_attrition.csv
├── Week_1_Internship_Report_Kora_Ahalya.docx
│
├── 01_attrition_distribution.png
├── 02_attrition_by_department.png
├── 03_overtime_vs_attrition.png
├── 04_monthly_income_vs_attrition.png
├── 05_correlation_heatmap.png
├── 06_job_satisfaction_vs_attrition.png
└── 07_worklife_balance_vs_attrition.png
