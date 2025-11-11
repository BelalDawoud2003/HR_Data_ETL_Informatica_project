#HR_Data_ETL_Informatica_project
HR Data ETL Project

Employee Performance ETL Pipeline (Informatica PowerCenter)

📌 Project Overview

This project demonstrates an ETL pipeline using Informatica PowerCenter that processes HR data to generate employee performance insights.

📝 Task Description
Task 1 – Employee Detail Load

Objective: Join HR tables, apply business rules, and load detailed employee data into TGT_EMPLOYEE_DETAIL.

Steps Implemented:

Join 4 source tables: EMPLOYEES, DEPARTMENTS, JOBS, LOCATIONS.

Filter employees hired in the last 25 years (300 months).

Exclude departments related to Sales.

Calculate new fields:

FULL_NAME

TOTAL_INCOME = Salary + Salary * Commission

YEARS_OF_SERVICE

SALARY_GRADE (HIGH / MEDIUM / LOW)

Sort by Department ID ASC and Salary DESC.

Load approximately 72 records.

Task 2 – Department Summary

Objective: Aggregate from Task 1 output into department-level performance insights.

Steps Implemented:

Aggregate by Department.

Calculate:

Employee count

AVG salary, AVG total income

MIN/MAX salary

Count of HIGH salary employees

Derive department performance level:

Top: AVG > 12,000

Average: 8,000 – 12,000

Low: < 8,000

Load 10–12 summarized department records.

🛠 Technologies Used

Informatica PowerCenter: Mappings, Sessions, Workflows

Oracle SQL

ETL Best Practices: Layering, Transformations, Validation

لو تح
