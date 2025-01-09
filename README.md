# Atlas Labs HR Analytics Dashboard

## 🌐 View My Live Dashboard
[![Power BI Dashboard](https://img.shields.io/badge/PowerBI-Dashboard-blue?style=flat-square&logo=Power-BI&logoColor=white)](https://app.powerbi.com/view?r=eyJrIjoiZTc5YmNkOWEtOTVjNS00NTZhLTkzNTQtZDllYzA1MWZmNmUzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)  
*Explore dynamic insights and interactive visualizations.*

## Overview
The **Atlas Labs HR Analytics Dashboard** is a powerful tool designed to visualize and analyze employee data, including demographics, performance tracking, and attrition rates. The dashboard is built using **Power BI Desktop** to empower HR teams with actionable insights.

## Dataset Structure
### Fact Table
Contains performance review data, including:
- **PerformanceID**: Unique identifier for performance reviews.
- **EmployeeID**: Links to employee details.
- **ReviewDate**: Tracks review dates.
- **EnvironmentSatisfaction**: Employee satisfaction ratings regarding their environment.
- **Serves as the central table for performance analysis**.

### Dimension Tables
- **Employee**: Stores employee-specific details such as demographics and job information.
- **EducationLevel**: Categorizes employee education qualifications.
- **RatingLevel**: Defines performance or satisfaction rating levels.
- **SatisfiedLevel**: Describes satisfaction levels for different aspects of work.
- **Date**: Provides a calendar-based reference for filtering and trend analysis.

---

## Schema Used

- **Snowflake Schema**: The dashboard implements a **Snowflake Schema** for efficient data storage and organization. The fact table is normalized, and multiple dimension tables are used for scalability and simplified querying.

---

## Features
- **👥 Employee Demographics**: Visual representation of employee age, gender, marital status, and ethnicity.
- **📈 Performance Tracker**: Track employee performance metrics over time, including job satisfaction and manager ratings.
- **📉 Attrition Analysis**: Detailed analysis of employee attrition rates by department, job role, and other factors.
- **📊 Hiring Trends**: Insights into hiring trends across different departments.

---

## Data Insights
- **👨‍💻 Total Employees**: 1470
- **👩‍💼 Active Employees**: 1233
- **❌ Inactive Employees**: 237
- **📉 Attrition Rate**: 16.1%
- **🗓️ Age Range**: Youngest employee is 18 years old, oldest is 51 years old.

---

## Demographics Breakdown
- **⚖️ Gender Distribution**:
  - Female: 42.45%
  - Male: 37.35%
  - Non-Binary: 20.2%
  
- **💍 Marital Status**:
  - Married
  - Single
  - Divorced

- **🌍 Ethnicity and Average Salary**:
  - White: Average Salary $115.3K
  - Black or African American: Average Salary $101.7K
  - Asian or Asian American: Average Salary $106.1K

---

## Key Insights Uncovered
- **🎯 Age Distribution**: The majority of employees at Atlas Labs are between **20-29 years old**.
- **🔢 Gender Ratio**: Atlas Labs employs **2.7% more women than men**.
- **🌈 Non-Binary Representation**: Employees who identify as **non-binary** make up **8.5%** of the total workforce.
- **💰 Average Salary by Ethnicity**: White employees have the highest average salary, while those identifying as mixed or multiple ethnic groups have one of the **lowest average salaries**.

---

## 📁 Reference Reports

### 📝 Overview Report
![Overview Report](Overview.jpg)  

### 📊 Demographics Report
![Demographics Report](Demographics.jpg)

### 📈 Performance Tracker Report
![Performance Tracker Report](Performancetracker.jpg)

### 📉 Attrition Report
![Attrition Report](Attrition.jpg)

---

## Conclusion
The **Atlas Labs HR Analytics Dashboard** provides valuable insights into the organization's workforce, enabling data-driven decision-making for HR teams and leadership. Key takeaways include:

- **👥 Demographics Analysis**: The employee base is predominantly young (20-29 years), with a diverse mix of genders and ethnicities, and the representation of non-binary employees is notable.
- **📈 Performance & Satisfaction**: The dashboard allows for an in-depth understanding of employee performance, job satisfaction, and how different factors like environment and role contribute to employee success.
- **📉 Attrition & Retention**: The attrition rate of **16.1%** highlights an area for potential improvement in employee retention strategies. Further analysis can uncover specific factors leading to higher turnover in certain departments or roles.
- **💰 Compensation Trends**: Ethnicity-based salary insights reveal opportunities for further investigation into pay equity across different demographic groups.
- **🌍 Diversity & Inclusion**: The dashboard provides a deeper understanding of gender and ethnicity diversity within Atlas Labs, which can be valuable for shaping future diversity and inclusion strategies.

---

## Future Scope
- **🔍 Further Investigation**: Dive deeper into attrition trends and identify key areas where employee engagement can be improved to reduce turnover.
- **🌈 Diversity Initiatives**: Leverage the insights on gender, ethnicity, and non-binary representation to enhance inclusivity and address any pay disparities.
- **📚 Employee Development**: Use performance metrics and satisfaction levels to refine training and development programs.

By leveraging this HR dashboard, Atlas Labs can refine its workforce management strategies, improving overall employee satisfaction, retention, and organizational performance.

---

**Additional Enhancements**:
- **📣 Employee Engagement**: Add more granular data on employee engagement metrics (e.g., surveys, feedback).
- **📋 Managerial Insights**: Analyze the performance of employees based on managerial impact, which could highlight areas for managerial development.
- **⏱️ Real-Time Updates**: Implement real-time data tracking for more up-to-date performance insights and quicker decision-making.

---
