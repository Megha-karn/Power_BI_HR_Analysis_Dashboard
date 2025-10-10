# 📈 HR Analytics Dashboard: Understanding and Reducing Employee Attrition

This project features an **HR Analytics Dashboard** created using Power BI to visualize key Human Resources data, focusing on **employee attrition**. The goal is to provide HR and management teams with actionable insights to understand why employees leave and where to focus retention efforts.

## 🌟 Key Features

* **Comprehensive Overview:** Quick summary of the total number of employees, overall attrition rate, and average monthly income.
* **Deep Dive into Attrition:** Detailed analysis of attrition by various factors like Education Field, Salary Slab, Age Group, Job Role, and Years at Company.
* **Actionable Insights:** Pinpointing high-risk departments and job roles to guide targeted retention strategies.
* **Interactive Filters:** Ability to filter data by **Gender** and **Department** for granular analysis.

---
![HR Analytics](https://github.com/Megha-karn/Power_BI_HR_Analysis_Dashboard/blob/main/HR_Analytics_Dashboard.png)

## 🚀 Dashboard

### 1. HR Analytics Dashboard Overview

This is the main dashboard view, providing a high-level summary and initial breakdown of attrition across key demographics.


### 2. Attrition Trends

This view highlights the relationship between years of service and attrition, as well as the number of employees who left per department.


---

## 📊 Key Metrics and Findings

The dashboard provides critical metrics for HR analysis:

* **Total Number of Employees:** 1413
* **Overall Attrition Rate:** $16.21\%$
* **Average Monthly Income:** $\$6.52\text{K}$

### Insights from the Visuals:

* **Years at Company:** The highest count of attrition occurs in the **first few years of service**, with a significant peak around the 1-year mark. This suggests an issue with onboarding, initial job fit, or early career development.
* **Department with Highest Attrition:** The **Research & Development** department has the highest absolute number of employees who left, followed by Sales.
* **Attrition by Education Field:** Employees in **Life Sciences** make up the largest percentage ($38\%$) of attrition by education field.
* **Attrition by Salary Slab:** The highest count of attrition is in the **"Upto 5k"** salary slab, indicating that lower-paid roles may have a higher turnover risk.
* **Job Role with High Attrition:** **Sales Executive** and **Laboratory Technician** roles have the highest total number of employees, and likely contribute significantly to the attrition count (though absolute attrition counts per job role aren't explicitly shown as a visual, the high total count for these roles is a flag).
* **Age Group:** The **$26-35$** age group has the highest attrition count.

---

## 🛠️ Tools and Technologies

* **Power BI:** Used for data cleaning, transformation, and creating the interactive dashboard visuals.
* **DAX (Data Analysis Expressions):** Used to create custom measures and calculated columns (e.g., Attrition Rate, Average Monthly Income).
* **CSV/Excel:** The initial data source for the project.

---

## 💾 Data Set

The analysis is performed on a simulated HR data set containing various employee-related features.

* **Data Source:** `HR_Employee_Attrition.csv` (or replace with your file name)
* **Total Records:** 1470
* **Key Columns:**
    * `Age`
    * `Department`
    * `JobRole`
    * `EducationField`
    * `MonthlyIncome`
    * `YearsAtCompany`
    * `Attrition` (Target Variable: 'Yes' or 'No')

### ⚠️ Note for Users:

To replicate the dashboard, please ensure the data file is placed in the project directory and the data source in the Power BI file (`HR_Analytics.pbix`) is correctly mapped to it.

---

## 💡 How to Use the Dashboard (Power BI)

1.  **Download:** Clone this repository or download the `HR_Analytics.pbix` file.
2.  **Install:** Ensure you have **Power BI Desktop** installed on your machine.
3.  **Open:** Open the `HR_Analytics.pbix` file.
4.  **Interact:** Use the slicers for **"Select Gender"** and **"Department"** at the top right of the dashboard to filter the visuals and explore different employee segments.
5.  **Analyze:** Hover over the visuals for tooltips to see specific data points and counts.

---

## ✅ Future Enhancements

* **Predictive Model Integration:** Incorporate a machine learning model to predict which current employees are at high risk of attrition.
* **Cost Analysis:** Add a calculated measure to estimate the cost of attrition (e.g., hiring, training, lost productivity).
* **Time Series Analysis:** Develop visuals to track attrition rate trends over time.

---

## 🤝 Contribution

Feel free to fork the repository, contribute to the analysis, suggest new visuals, or improve the documentation!
