![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-teal)

# HR Attrition Analysis (EDA)

Exploratory Data Analysis of the IBM HR Employee Attrition dataset to identify key factors influencing employee turnover.

### Dataset

IBM HR Analytics Employee Attrition Dataset containing employee demographic, job role, salary, and performance information used to analyze attrition patterns.

### Tools Used
Python | Pandas | NumPy | Matplotlib | Seaborn

---

## Project Overview
This project analyzes employee attrition data to uncover patterns and insights that may help organizations improve employee retention strategies.

## Business Questions
1. What is the overall employee attrition rate?
2. Which departments experience the highest attrition?
3. Does employee age influence attrition?
4. Is monthly income related to employee turnover?
5. Do employees with fewer years at the company leave more often?
6. Which job roles show higher attrition patterns?

## Key Insights
- Sales department shows the highest attrition.
- Employees aged 25–35 leave more frequently.
- Lower monthly income is associated with higher attrition.
- Employees with fewer years at the company are more likely to leave.

## Visualizations

### Attrition Distribution
![Attrition Distribution](images/attrition_distribution.png)

### Attrition by Department
![Attrition by Department](images/attrition_by_department.png)

### Attrition by Age
![Attrition by Age](images/attrition_by_age.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

## Project Structure

```
HR-Attrition-Analysis
│
├── data
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── images
│   ├── attrition_by_age.png
│   ├── attrition_by_department.png
│   ├── attrition_distribution.png
│   └── correlation_heatmap.png
│
├── notebook
│   └── HR_Attrition_Analysis.ipynb
│
└── README.md
```

## How to Run

1. Clone the repository
2. Install required libraries (pandas, numpy, matplotlib, seaborn)
3. Open the notebook in Jupyter
4. Run all cells to reproduce the analysis
