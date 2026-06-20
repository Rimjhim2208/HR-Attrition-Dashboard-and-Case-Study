# 👥 IBM HR Attrition Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Excel](https://img.shields.io/badge/Excel-Analysis-green)
![SQL](https://img.shields.io/badge/SQL-Queries-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# 📌 Project Overview

This project presents a comprehensive HR Analytics case study using the IBM HR Analytics Employee Attrition Dataset. The objective is to identify the key factors driving employee turnover and provide actionable business recommendations to improve employee retention and workforce stability.

An interactive Power BI dashboard was developed to analyze attrition trends across departments, job roles, compensation levels, overtime, job satisfaction, work-life balance, and career growth opportunities.

---

# 🎯 Business Problem

Employee attrition is a critical challenge for organizations as it increases recruitment costs, lowers productivity, and impacts workforce stability.

This analysis aims to answer the following business questions:

- Why are employees leaving the organization?
- Which departments and job roles have the highest attrition?
- How does overtime impact employee turnover?
- What role do salary and job satisfaction play in attrition?
- Which employee groups are at the highest risk of leaving?
- What strategies can HR implement to improve retention?

---

# 📊 Dataset Description

| Property | Details |
|-----------|-----------|
| Source | IBM HR Analytics Dataset |
| Total Employees | 1470 |
| Total Columns | 35 |
| Employees Left | 237 |
| Attrition Rate | 16.12% |

### Key Columns

- Attrition
- Department
- Job Role
- Monthly Income
- Overtime
- Job Satisfaction
- Environment Satisfaction
- Work Life Balance
- Years At Company
- Years Since Last Promotion
- Age
- Education Field

---

# 📈 Key Metrics

| Metric | Value |
|---------|---------|
| Total Employees | 1470 |
| Employees Left | 237 |
| Attrition Rate | 16.12% |
| Average Age | 37 Years |
| Average Monthly Income | ₹6,500+ |
| Overtime Employees | Significant Contributor to Attrition |

---

# 💡 Key Insights

## 1. Overtime is a Major Attrition Driver

- Employees working overtime are significantly more likely to leave.
- Overtime employees contribute a major share of total attrition.

## 2. Sales Department Has Highest Attrition

- The Sales department records the highest employee turnover.
- Sales Executives represent one of the most affected job roles.

## 3. Low Salary Employees Leave More Frequently

- Employees in lower income bands show higher attrition rates.
- Compensation appears to be a strong factor influencing employee decisions.

## 4. Job Satisfaction Influences Retention

- Employees with lower job satisfaction scores are more likely to leave.
- Attrition decreases as satisfaction levels improve.

## 5. Promotion Delays Increase Attrition Risk

- Employees who have not received promotions for extended periods show higher attrition tendencies.

---

# 🚨 High-Risk Employee Profile

| Attribute | Profile |
|------------|---------|
| Age Group | 26–35 Years |
| Department | Sales |
| Job Role | Sales Executive |
| Income Band | Low |
| Overtime | Yes |
| Job Satisfaction | Low |
| Promotion Gap | High |

---

# 📊 Dashboard pages
## Page 1 – Risk Analysis

- KPI Cards
- Attrition Rate
- Department Analysis
- Attrition by Gender
- Attrition by Age Group

## Page 2 – Attrition Drivers Analysis

- Job Satisfaction Analysis
- Work-Life Balance Analysis
- Overtime Impact
- Monthly Income Analysis
- Job Role Analysis


---
## 📖 Business Case Study

### What I Did

- Analyzed the IBM HR Attrition dataset to identify factors contributing to employee turnover.
- Performed data cleaning and transformation using Excel, SQL, and Power Query.
- Created KPIs such as Attrition Rate, Attrition Count, and Department-wise Attrition.
- Built an interactive Power BI dashboard to analyze attrition by department, job role, salary, overtime, job satisfaction, and work-life balance.
- Identified high-risk employee profiles and key attrition drivers.
- Provided data-driven recommendations to improve employee retention and workforce stability
- 

# 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| Microsoft Excel | Data Understanding & Validation |
| SQL | Data Analysis & Querying |
| Power Query | Data Cleaning & Transformation |
| Power BI | Dashboard Development |
| DAX | KPI Measures & Calculations |

---

# 🧹 Data Cleaning Steps

1. Checked and validated data quality.
2. Removed duplicate records.
3. Standardized column names.
4. Created Age Group categories.
5. Created Salary Band categories.
6. Verified attrition labels and employee records.
7. Created calculated columns for analysis.
8. Built KPI measures using DAX.

---

# 📐 DAX Measures Created

DAX
Total Employees =
COUNTROWS(Employee)

Attrition Count =
CALCULATE(
    COUNTROWS(Employee),
    Employee[Attrition] = "Yes"
)

Attrition Rate =
DIVIDE(
    [Attrition Count],
    [Total Employees]
)

Average Income =
AVERAGE(Employee[MonthlyIncome])


# ✅ Business Recommendations

### 1. Reduce Overtime Dependency

Balance employee workloads and improve workforce planning.

### 2. Improve Career Growth Opportunities

Implement transparent promotion and development programs.

### 3. Strengthen Employee Engagement

Conduct regular employee feedback and satisfaction surveys.

### 4. Review Compensation Policies

Benchmark salaries against industry standards to improve retention.

### 5. Focus on High-Risk Employee Groups

Create targeted retention strategies for employees in Sales and lower income bands.

---

---

# 🎯 Business Impact

- Identified key drivers of employee attrition.
- Highlighted high-risk employee segments.
- Enabled data-driven HR decision making.
- Improved workforce planning and retention strategies.
- Provided actionable recommendations to reduce employee turnover.

---

## 👩‍💻 Author

Rimjhim Chawla

Aspiring Business Analyst | Data Analyst

Skills: Power BI | SQL | Excel | Business Analytics | Data Visualization


