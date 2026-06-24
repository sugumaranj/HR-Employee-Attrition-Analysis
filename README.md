# HR Employee Attrition Analysis

## Project Overview

This project analyzes employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset. The goal is to identify key factors associated with employee turnover and generate actionable business insights using Python-based data analytics techniques.

The project covers the complete data analysis workflow, including data understanding, data cleaning, exploratory data analysis (EDA), visualization, and business recommendations.

---

## Problem Statement

Employee attrition is a major challenge for organizations as it leads to increased recruitment costs, training expenses, and productivity loss. This project aims to analyze employee data to identify the factors associated with attrition and help organizations improve employee retention strategies.

---

## Objectives

- Understand the employee attrition dataset.
- Clean and preprocess HR data.
- Perform Exploratory Data Analysis (EDA).
- Identify factors associated with employee turnover.
- Visualize attrition trends and patterns.
- Generate data-driven business recommendations.

---

## Dataset Information

- **Dataset:** IBM HR Analytics Employee Attrition & Performance
- **Records:** 1470 Employees
- **Original Features:** 35
- **Cleaned Features:** 31

### Dataset Source

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Project Structure

```text
HR-Employee-Attrition-Analysis/
│
├── data/
│   ├── employee_attrition.csv
│   └── CleanedDataset/
│       └── employee_cleaned.csv
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_EDA_and_Insights.ipynb
│   └── 04_Visualizations.ipynb
│
├── charts/
│
├── results/
│
├── requirements.txt
│
└── README.md
```

---

## Project Workflow

### 1. Data Understanding

- Loaded the dataset using Pandas.
- Explored dataset dimensions and structure.
- Identified numerical and categorical features.
- Examined data types and summary statistics.

### 2. Data Cleaning

Removed columns with no analytical value:

- EmployeeCount
- EmployeeNumber
- Over18
- StandardHours

Verified:

- Missing values
- Duplicate records
- Data consistency

Generated a cleaned dataset for further analysis.

### 3. Exploratory Data Analysis (EDA)

Analyzed:

- Overall Attrition Rate
- Department-wise Attrition
- Job Role-wise Attrition
- Overtime vs Attrition
- Business Travel vs Attrition
- Job Satisfaction vs Attrition
- Work-Life Balance vs Attrition
- Salary vs Attrition
- Experience vs Attrition
- Years at Company vs Attrition
- Correlation Analysis

### 4. Data Visualization

Created visualizations using Matplotlib to communicate key insights and attrition trends effectively.

---

## Key Findings

### Overall Attrition

- Overall employee attrition rate: **16.1%**

### Department Analysis

- Sales department showed the highest attrition rate.

### Job Role Analysis

- Sales Representatives experienced the highest attrition rate (**39.8%**).

### Overtime Analysis

- Employees working overtime showed significantly higher attrition than those not working overtime.

### Business Travel Analysis

- Employees who travel frequently had higher attrition compared to employees who travel rarely or do not travel.

### Salary Analysis

- Employees who left the company had lower average monthly income compared to retained employees.

### Experience Analysis

- Employees who left generally had fewer total working years and shorter company tenure.

### Satisfaction Analysis

- Lower job satisfaction and poor work-life balance were associated with higher attrition.

### Correlation Analysis

Strongest negative correlations with attrition:

| Feature | Correlation |
|----------|------------|
| TotalWorkingYears | -0.171 |
| JobLevel | -0.169 |
| YearsInCurrentRole | -0.161 |
| MonthlyIncome | -0.160 |
| Age | -0.159 |

These findings suggest that experienced, higher-paid, and senior employees are generally less likely to leave the organization.

---

## Visualizations Created

- Employee Attrition Distribution
- Department Attrition Rate
- Job Role Attrition Rate
- Overtime vs Attrition
- Business Travel vs Attrition
- Job Satisfaction vs Attrition
- Work-Life Balance vs Attrition
- Average Monthly Income by Attrition
- Average Total Working Years by Attrition
- Average Years at Company by Attrition

---

## Business Recommendations

Based on the analysis:

1. Reduce excessive overtime to minimize employee burnout.
2. Focus retention efforts on Sales employees and Sales Representatives.
3. Improve employee work-life balance initiatives.
4. Review compensation strategies for lower-income employees.
5. Provide career growth opportunities for less experienced employees.

---

## Challenges Faced

- Understanding the dataset structure and identifying relevant features.
- Learning Pandas GroupBy operations for attrition analysis.
- Calculating attrition percentages correctly.
- Selecting appropriate visualizations.
- Converting analytical findings into business insights.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation
- Pandas & Matplotlib
- Git & GitHub Version Control
- Data Analytics Workflow

---

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/sugumaranj/HR-Employee-Attrition-Analysis.git
```

### Navigate to the Project

```bash
cd HR-Employee-Attrition-Analysis
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run Notebooks

Execute notebooks in the following order:

1. 01_Data_Understanding.ipynb
2. 02_Data_Cleaning.ipynb
3. 03_EDA_and_Insights.ipynb
4. 04_Visualizations.ipynb

---

## Results

The analysis successfully identified the major factors associated with employee attrition, including overtime, salary, experience, work-life balance, business travel, and job satisfaction. The findings can support HR teams in developing targeted employee retention strategies.

---

## Author

**Sugumaran J**

Bachelor of Computer Applications (BCA)  
Government Arts and Science College, Veerapandi, Theni

GitHub: https://github.com/sugumaranj

LinkedIn: https://www.linkedin.com/in/sugumaranj

---
