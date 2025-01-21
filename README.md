# HR_SQL_Server_Analytics

These project focuses on using employee data to promote a healthy lifestyle through a bonus program and compensation analysis.
- HR department requests a list of healthy individuals with low absenteeism       for a $1,000 bonus program and a calculation of wage increases for non-smokers

## Steps of Data Analysis
### Step 1. Database Creation and Data Import
- The project begins with the creation of a database in Microsoft SQL Server Studio.

- A new database named "work" is created, and data is imported from flat CSV files into tables.

#### Table Structure
- The first table includes columns such as reasons for absence, month of absence, age, workload, and absenteeism.
- A second table is created to define the reasons for absence, and a third table for employee salary.

### Step 2. SQL Queries and Analysis
- SQL queries are developed to join the tables and analyze the data.
- The main table is the absenteeism table, which is joined with the compensation and reasons tables.
The analysis aims to identify the healthiest employees based on criteria such as non-smoking status, body mass index (BMI), and absenteeism


