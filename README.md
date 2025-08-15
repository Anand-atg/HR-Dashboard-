
# 📊 HR Analytics Dashboard – Power BI Project

## 📌 Introduction
This project uses an **HR dataset from Kaggle** as part of my personal upskilling journey in **Power BI**.  
The goal was to simulate a real-world HR analytics scenario — cleaning raw data, performing exploratory data analysis, and building an interactive dashboard to help HR teams make data-driven decisions.

---

## 🏢 Business Questions (as requested by the HR Department)
1. How many employees are due for promotion and how many are not?  
2. What is the distribution of employees by gender, job level, and department?  
3. How does employee performance (High vs Low) vary across departments?  
4. Which departments have the highest number of employees due for retrenchment?  
5. What is the age-wise and salary-wise distribution of employees?  
6. How does job satisfaction relate to distance from the office?  
7. What is the education background of employees across roles?  

---

## 🧹 Data Cleaning & Preparation
To ensure accurate reporting:  
- **Removed duplicates** to avoid double counting.  
- **Handled missing values** in department, job role, and gender using HR assumptions.  
- **Standardized formats** (date fields, department names, education categories).  
- **Normalized text fields** for job roles and departments.  
- **Corrected data types** (numeric for salary & years of service, categorical for gender & department).  
- **Validated outliers** in salary and years of service with set thresholds.  

---

## 🔍 Exploratory Data Analysis (EDA)
Performed EDA to uncover trends before visualization:  
- **Promotion Analysis** – Calculated % of employees due vs not due for promotion.  
- **Workforce Composition** – Gender split (60% Male, 40% Female), age group trends, service years.  
- **Performance Insights** – 84.7% high rating vs 15.3% low rating.  
- **Salary Distribution** – Most employees earn under 10K.  
- **Job Satisfaction & Commute** – Notable trends between satisfaction levels and office distance.  

---

## 📈 Key Insights from Dashboard
- **72 employees (4.9%)** are due for promotion; majority (95.1%) are not.  
- **117 employees** are due for retrenchment, highest in **Research & Development**.  
- Age group **26-35 years** has the highest employee count (566 employees).  
- Majority of employees have **Life Sciences** or **Medical** backgrounds.  
- Job roles like **Laboratory Technician** and **Sales Executive** have the largest workforce.  

---

## 🛠 Tools Used
- **Power BI** – Data modeling, DAX calculations, interactive dashboard design.  
- **Excel** – Initial data cleaning and preprocessing.  
- **ETL Concepts** – Extract, Transform, Load workflow simulation.  

---

## 💡 Outcome
This HR Dashboard provides a **360° view of workforce performance, promotions, retrenchment risks, and employee demographics**, enabling HR to make **faster, data-driven decisions**.
"""

