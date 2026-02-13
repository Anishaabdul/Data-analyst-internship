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

---
# Tools Used

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

---
# Outcome

Gained hands-on experience with SQL window functions for analytical reporting and business insights.

---
# Task 9: SQL Data Modeling – Star Schema
# Description

This task involves designing and implementing a Star Schema using SQL for analytical reporting. A fact table and multiple dimension tables were created from a sales dataset.

---
# Tools Used

PostgreSQL / MySQL
SQL
dbdiagram.io / draw.io (for schema diagram)

---
# Dataset

Global Superstore / Retail Sales Dataset

---
# Work Done

Identified fact and dimension tables
Created dimension tables with primary keys
Created fact table with foreign keys
Loaded data into dimensions and fact table
Created indexes on join keys
Ran analytical queries using star schema joins
Exported schema diagram and query outputs

---
# Files Included

task9_star_schema.sql
star_schema_diagram.png / pdf

---
# Task 10: Python EDA – Summary & Outlier Detection
# Description

This task focuses on performing Exploratory Data Analysis (EDA) using Python.
The analysis includes summary statistics, missing value checks, data visualization, outlier detection using the IQR method, and correlation analysis.

---
# Tools Used

Jupyter Notebook
Python
pandas, numpy, matplotlib

---
# Dataset

Students Performance in Exams dataset
Numeric column analyzed: Math Score

---
# Steps Performed

Loaded and explored the dataset
Generated descriptive statistics
Checked missing values
Visualized data using histogram and boxplot
Detected outliers using IQR method
Created outlier flag column
Removed outliers
Generated correlation matrix
Exported cleaned dataset

---
# Files Included

task10_eda.ipynb – Jupyter Notebook with full analysis
cleaned_dataset.csv – Cleaned dataset after outlier removal
eda_findings.txt – Summary of insights
analysis_outputs.csv

---
# Outcome

Understood data warehouse modeling concepts and how star schemas support BI reporting.

---
# Task 11 – A/B Testing (Hypothesis Testing)
# Objective

To perform A/B testing using Python and determine whether there is a statistically significant difference between two variants based on conversions.

---
# Dataset
The dataset was downloaded from Kaggle and contains user-level data with the following columns:
User_ID
Variant (A / B)
Clicks
Conversions

---
# Tools & Libraries Used
Python
Jupyter Notebook
pandas
numpy
scipy
matplotlib
seaborn

---
# Steps Performed
Loaded and explored the dataset
Split data into Control (Variant A) and Test (Variant B) groups
Defined null and alternative hypotheses
Calculated conversion rates
Performed a two-sample t-test
Interpreted p-value and results
Visualized conversions using a bar chart
Provided a final recommendation

---
# Result
Based on the p-value at a 5% significance level, a decision was made on whether Variant B performs better than Variant A.

---
# Files Included
task11_abtest.ipynb
ab_test_summary.csv
final_recommendation.txt
README.md

---

# Task12 - Customer Churn Analysis – Power BI
# Project Description
This project analyzes a Customer Churn dataset using Power BI.
The data is cleaned and transformed using Power Query, and basic visuals are created to understand customer churn patterns.

---
# Tools Used
Power BI Desktop
Power Query
Kaggle Customer Churn Dataset

---
# Data Transformation Steps
Removed unnecessary columns
Renamed column headers
Handled missing values
Changed correct data types
Created conditional columns (Churn Status, Tenure Group)

---
# Visualizations Created
Bar chart: Customers by Tenure Group
Pie chart: Churn vs Retained customers
Card: Total customers

---
# Files Included
customer_churn.pbix – Power BI file
README.md – Project documentation

---
# Outcome
The dashboard provides a clear overview of customer churn and retention trends.

---
# Task 13: BI Dashboard Storytelling – KPI Report
# Objective
Create an executive-level BI dashboard that highlights key business performance metrics and insights using a retail sales dataset.

---
# Tools Used
Power BI Desktop
(Alternative: Tableau Public)

---
# Dataset
Global Superstore Dataset / Retail Sales Dataset

---
# KPIs Created
Total Sales
Total Profit
Profit Margin

---
# Dashboard Features
KPI cards for Sales, Profit, and Margin
Sales trend over time
Category-wise sales breakdown
Region-wise performance analysis
Top 10 products by sales
Interactive slicers (Region, Date, Category)
Insights section with key findings

---
# Deliverables
dashboard.pbix (Power BI file)
dashboard_export.pdf
insights_task13.txt

---
# Insights Summary
Sales show a clear trend over time with seasonal peaks
Certain regions contribute higher profit despite lower sales
Top products drive a significant portion of total revenue

---
# Outcome
An executive-ready BI dashboard that enables quick decision-making using clear KPIs and visual storytelling.

---
# Task 14: ETL Mini Pipeline (Extract → Transform → Load)
# Overview
This task demonstrates a simple ETL (Extract, Transform, Load) pipeline using Python.
The goal is to load raw data, clean and transform it, and then store the processed data for analysis.

---
# Tools & Technologies
Python
pandas
Jupyter Notebook / Google Colab
CSV files
SQLite database

---
# Dataset
Retail Sales Dataset
Customer Churn Dataset
E-commerce Dataset

---
# ETL Steps
Load raw CSV dataset from Kaggle
Create folders: raw, processed, output
Handle missing values and remove duplicates
Standardize column names and data types
Create derived columns (e.g., profit margin, segments)
Split data into separate tables (customers, orders, products)
Load processed data into CSV files and SQLite database
Validate row counts before and after transformation
Document the complete ETL process

---
# Deliverables
task14_etl.ipynb
Processed CSV file(s)
database.sqlite
README.md

---
# Task 15: Customer Segmentation (RFM Analysis)
# Objective
To perform Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis in Python and identify different customer groups for business targeting.

---
# Tools Used
Python
Google Colab / Jupyter Notebook
Libraries: pandas, numpy, matplotlib

---
# Dataset
Online Retail / E-Commerce Dataset
Contains customer purchase transaction details

---
# Steps Performed
Loaded and cleaned the dataset (removed null and cancelled invoices).
Converted Invoice Date to datetime format.

---
# Calculated:
Recency – Days since last purchase
Frequency – Number of purchases
Monetary – Total spending
Created RFM score using quantiles.
Assigned customer segments (Champions, Loyal, At Risk, etc.).
Visualized segment distribution using bar chart.
Exported results to CSV file.

---
# Deliverables
task15_rfm.ipynb
rfm_segments.csv
segment_actions.txt

---
# Outcome
Successfully segmented customers based on purchasing behavior and provided business recommendations for each segment.

---
# Final Outcome
Understanding of how ETL pipelines work in real-world analytics
Hands-on experience with data extraction, transformation, and loading
Improved data organization for analysis and reporting

---
# Task 16: Walmart Sales Forecasting Project
# Project Overview
This project performs time series forecasting on Walmart weekly sales data.
The objective is to analyze historical sales trends and predict future sales using forecasting models.

---
# Dataset Used
Dataset: Walmart Store Sales (train.csv)
Columns Used:
  - Store
  - Dept
  - Date
  - Weekly_Sales
  - IsHoliday
The dataset contains historical weekly sales data across multiple stores and departments.

---
# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels (Exponential Smoothing)

---
# Project Steps
1. Data Loading
2. Date Conversion and Sorting
3. Monthly Aggregation of Weekly Sales
4. Train-Test Split (80%-20%)
5. Model Building using Exponential Smoothing
6. Forecast Generation
7. Model Evaluation using:
   - MAE (Mean Absolute Error)
   - MAPE (Mean Absolute Percentage Error)
8. Export Forecast Results to CSV
9. Generate Forecast Report (.txt)

---
# Model Used
Exponential Smoothing (Additive Trend)
This model captures trend patterns in time series data and is suitable for sales forecasting.

---
# Evaluation Metrics
 MAE: Measures average absolute prediction error.
 MAPE: Measures percentage error between actual and predicted values.
Lower values indicate better model performance.

---
# Output Files
 task16.ipynb (Jupyter Notebook)
 forecast_output.csv (Predicted vs Actual Sales)
 forecast_report.txt (Model summary and performance report)

---
# Conclusion
The forecasting model successfully predicts future sales trends based on historical data.
The results can help in demand planning and business decision-making.

---

