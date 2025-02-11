
# Project Title

A brief description of what this project does and who it's for

# HR Analytics Dashboard - Employee Attrition

### Dashboard Link : https://app.powerbi.com/groups/me/reports/3a2fd3ea-5703-4e8c-b4b4-a633b6c8cbb0/da7990c30001577e006d?experience=power-bi
## Problem Statement

This dashboard helps organizations understand employee attrition trends and key HR metrics. It provides insights into factors influencing attrition rates, employee satisfaction levels, and areas for improvement. By analyzing different metrics, HR teams can take data-driven actions to reduce attrition and enhance employee experience.
### Key Insights
The dashboard highlights the proportion of employees who have left versus those who remain.

It identifies key factors contributing to attrition, such as job role, department, salary, and work-life balance.

Provides insights into employee satisfaction through various ratings.

Displays trends in employee departures over time and across different segments.
### Steps followed 

Step 1: Loaded data into Power BI Desktop (CSV format dataset).

Step 2: Opened Power Query Editor and enabled "Column Distribution," "Column Quality," and "Column Profile" options for data validation.

Step 3: Ensured column profiling was based on the entire dataset for accuracy.

Step 4: Identified missing values, particularly in key fields, and handled null values appropriately.

Step 5: Created calculated measures to analyze average tenure, salary distribution, and satisfaction scores.

Step 6: Applied appropriate filters and slicers for key attributes such as "Department," "Job Role," "Work Experience," and "Education Level."

Step 7: Designed visuals, including:

Card visuals for displaying key metrics like attrition rate, average tenure, and job satisfaction score.

Bar charts for comparing attrition rates across departments and job roles.

Pie charts for visualizing employee distribution based on different attributes.

Line charts for tracking attrition trends over time.

Satisfaction Ratings Visual for parameters like Work Environment, Job Role Satisfaction, Career Growth, and Work-Life Balance.

Step 8: Incorporated a company logo, name, and tagline for branding.

Step 9: Created a calculated column for grouping employees into different age categories using DAX:
Age Group =
if(EmployeeData[Age] <= 25, "0-25 (25 included)",
if(EmployeeData[Age] <= 50, "25-50 (50 included)",
if(EmployeeData[Age] <= 75, "50-75 (75 included)",
"75-100 (100 included)")))

![Image](https://github.com/user-attachments/assets/527c9ad3-4d80-4db8-91e0-8d6f3c0fcff1)
