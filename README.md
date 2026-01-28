# Data Analyst Internship Tasks
Author: Anisha 

# Task 1: Excel Basics – Data Cleaning & Formatting
# Objective
To clean and format a raw dataset using Excel/Google Sheets by handling missing values, duplicates, inconsistent text, and incorrect data formats.

---
# Tools Used
- Microsoft Excel / Google Sheets

---
# Dataset
- CSV dataset downloaded from Kaggle  
- Example: Netflix Movies and TV Shows dataset

---
# Steps Performed
- Opened and verified the dataset in Excel
- Applied filters and froze header rows
- Identified and handled missing values
- Removed duplicate records
- Cleaned text using TRIM, PROPER, and UPPER functions
- Corrected date and numeric formats
- Created a separate `Cleaned_Data` sheet
- Added a `Data_Quality_Notes` column for observations
- Exported the cleaned data as Excel and CSV files

---
# Files Included
- `Cleaned_dataset.xlsx`
- `cleaned_dataset.csv`

---
# Outcome
The dataset is cleaned, standardized, and ready for further analysis.

---

# Task 2: Pivot Table Analysis – Sample Superstore
This project contains an Excel pivot table analysis created using the Sample Superstore dataset.
The analysis includes:
- Total Sales
- Total Profit
- Average Profit Margin
- Analysis by Region, Segment, and Category
- Interactive slicers for easy filtering

---
# Files Included
- Pivot_Report.xlsx
- (Optional) Pivot_Report.pdf

---
# Tool Used
- Microsoft Excel

---

# Task 3: Superstore MySQL Task
# Description
This task demonstrates basic usage of MySQL, including database creation, table import, and data verification using SQL queries.
The Superstore dataset was imported into MySQL, and the total number of records was verified.

---
# Result
Total number of rows in the `superstore` table: **9,694**

---
# Tools Used
- MySQL 8.0
- MySQL Workbench

---
# Files Included
- superstore.sql
- row_count.png (proof screenshot)

---

# Task 4 – SQL JOIN Operations
# Description
This task demonstrates the use of SQL JOIN operations on the Superstore dataset.
It includes INNER JOIN, LEFT JOIN, and basic business analysis queries.

---
# Files Included
- joins_queries.sql – SQL queries using JOINs
- joined_output.csv – Exported result of JOIN query
- insights.txt – Business insights derived from the data

---
# Concepts Used
- INNER JOIN
- LEFT JOIN
- Aggregate functions (SUM)
- GROUP BY and ORDER BY

---

# Task 5 – Titanic Dataset Data Cleaning
# Overview
This project contains basic data cleaning performed on the Titanic dataset using Python
and Pandas in a Jupyter Notebook.

---
# Files Included
- Task5_Titanic_cleaning.ipynb – Jupyter Notebook with data cleaning steps
- cleaned_data.csv – Cleaned Titanic dataset
- README.md – Project description

---
# What Was Done
- Loaded the Titanic dataset
- Checked and handled missing values
- Filled missing Age values using median
- Filled missing Embarked values using mode
- Removed the Cabin column
- Removed duplicate rows
- Created a new column called Age_Group
- Saved the cleaned dataset as a CSV file

---
# Tools Used
- Python
- Pandas
- Jupyter Notebook

---

# Task 6: Data Visualization
# Description
This task involves creating data visualizations using Python to analyze and interpret
data patterns and trends.

---
# Dataset Used
- World Happiness Report 2024

---
# Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---
# Visualizations
- Bar chart
- Line chart
- Histogram
- Scatter plot

---
# Outcome
Developed practical skills in data visualization and insight generation using Python.

#  Task 7:Power BI Dashboard Task
# Overview

This dashboard shows total sales by category and sales performance by region. It uses interactive visuals like cards, bar charts, and a region slicer.

---

# Insights

Technology category has the highest sales.

Office Supplies and Furniture have similar sales.

Sales vary across regions, showing regional differences in performance.


---
# File

dashboard.pdf – Exported Power BI visuals

---

# Task 8: SQL Window Functions – Ranking & Running Totals
# Description

This task focuses on using SQL Window Functions to perform advanced analysis such as ranking, running totals, and month-over-month growth. The analysis is done using a sales dataset imported into SQL.

Tools Used

PostgreSQL / MySQL Workbench

SQL (Window Functions)

---

# Dataset

Global Superstore Dataset (CSV imported into SQL)

Key Operations Performed

Calculated total sales per customer

Ranked customers by sales using ROW_NUMBER, RANK, and DENSE_RANK

Calculated running total of sales

Calculated month-over-month (MoM) growth using LAG()

Found top 3 products per category

Exported results to CSV files

Saved all queries in a single .sql file

---

# Files Included

task8_window.sql

ranked_customers.csv

mom_growth.csv

insights_task8.txt

# Outcome

Gained hands-on experience with SQL window functions for analytical reporting and business insights.
