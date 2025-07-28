# sql-hr-attrition-analysis

# 🧑‍💼 Employee Attrition Analysis Using SQL

This project performs an exploratory analysis on employee HR data to uncover patterns and risk factors related to attrition. Using raw SQL, it identifies how factors like income, satisfaction, promotion, and demographics impact employee turnover.

---

## 📌 Objectives

- Understand attrition rate and risk factors across departments and job roles
- Explore how monthly income, satisfaction levels, promotions, and distance affect attrition
- Analyze demographic patterns (gender, marital status) in relation to turnover
- Deliver business recommendations for reducing attrition

---

## 🛠️ Tools & Technologies

- SQL (Window Functions, CTEs, Aggregations)
- Relational HR dataset (~1,470 employee records)
- GitHub for documentation and version control

---

# 📊 Key Insights – Employee Attrition SQL Analysis

### 1. Attrition Overview
- Total attrition rate: **16.12%**
- Highest attrition: **Sales department**, especially **Sales Representatives**

### 2. Income & Attrition
- Employees with **below-average income** for their role have a **17.2% attrition rate**
- Low income is a strong predictor of turnover

### 3. Distance & Commute
- Employees who live **closer to work** have **higher attrition**, possibly due to higher job options nearby

### 4. Salary Hike & Promotion
- Employees with **less-than-average salary hikes** showed slightly higher attrition
- Most leavers had **no recent promotions**

### 5. Satisfaction Factors
- Employees rate **job satisfaction, work-life balance, and environment** fairly high
- Least satisfied employees (rating 1) are a small group but more likely to leave

### 6. Tenure & Performance
- **Most attrition happens in Year 1**
- **Performance rating** is not strongly correlated with attrition — leavers are mostly average-rated

### 7. Demographic Factors
- **Male** employees show more attrition than females
- **Single** employees have the highest turnover rate

### 8. High-Risk Segments
- **Sales Representatives** in the **Sales department** are the most attrition-prone group
- **HR Managers** have **0% attrition**

---

### Summary

This SQL project highlights that income, tenure, role, and promotion delays are leading attrition drivers. Targeted retention programs can significantly reduce employee churn.


