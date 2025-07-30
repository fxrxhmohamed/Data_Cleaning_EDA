# 🧹 Data Cleaning & 📊 Exploratory Data Analysis (EDA) in SQL

This project showcases a comprehensive data cleaning and exploratory data analysis (EDA) workflow using SQL. It uses a dataset on global tech layoffs and demonstrates how to transform raw data into meaningful insights.

---

## 📁 Project Structure

- 📄 `layoffs.csv`  
  Raw dataset containing records of tech company layoffs.

- 🧹 `Data_Cleaning_Project.sql`  
  SQL script for cleaning the dataset: handling nulls, standardizing formats, removing duplicates, and transforming columns for analysis.

- 📊 `EDA_Project.sql`  
  SQL script that performs EDA, uncovering trends, aggregations, and statistical summaries using SQL queries.

---

## 🔍 Key Cleaning Tasks

- Removed blank rows and duplicates
- Standardized date formats and company names
- Handled NULL values
- Extracted year and month from date for time-based analysis
- Normalized categorical values

---

## 📈 Key EDA Insights

- Total layoffs by company and year
- Layoff trends over time (monthly/yearly)
- Impacted countries and industries
- Largest layoff events and cumulative analysis

---

## 🛠️ Technologies Used

- SQL (compatible with MySQL / PostgreSQL)
- DB tools: MySQL Workbench 
- Data source: `layoffs.csv` (loaded as a SQL table)

---

## 🚀 How to Run

1. Load the `layoffs.csv` dataset into a SQL database table
2. Run `Data_Cleaning_Project.sql` to clean and transform the data into a new table 
3. Run `EDA_Project.sql` to explore and analyze trends from the cleaned data

---

## 📌 Author

Created by [Farah Mohamed Abdallah] — as part of a data analytics and SQL practice module.


