# Customer-Shopping-Behavior-Analysis
# Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow using Python, SQL Server, Power BI, and reporting tools. The goal of the project is to analyze the dataset, clean and transform the data, run SQL queries to generate insights, build an interactive Power BI dashboard, and present the final findings through a report and presentation.

The project follows a complete analytics process from raw data loading to business insights and visualization.

## Dataset

The dataset used in this project contains customer shopping behavior data. It includes information such as customer details, products purchased, purchase amount, category, location, discounts, payment method, and other shopping-related attributes.

The dataset was used to analyze customer purchasing patterns, product performance, discount usage, and sales trends.

## Tools and Technologies Used

* Python
* Jupyter Notebook
* Pandas
* SQL Server
* SQL Server Management Studio
* Power BI
* Gamma
* Microsoft PowerPoint / PDF Report

## Project Steps

## 1. Data Loading in Python

The dataset was loaded into Python using Pandas.

Key tasks performed:

* Imported required Python libraries
* Loaded the CSV dataset
* Checked the shape of the data
* Viewed sample records
* Understood column names and data types

## 2. Exploratory Data Analysis

EDA was performed to understand the dataset and identify important patterns.

Key tasks performed:

* Checked missing values
* Checked duplicate records
* Analyzed numerical and categorical columns
* Reviewed unique values
* Identified important business metrics
* Explored product, category, customer, and discount-related trends

## 3. Data Cleaning

The dataset was cleaned before analysis and database loading.

Key cleaning steps:

* Removed duplicate records
* Handled missing values
* Renamed columns for better readability
* Checked and corrected data types
* Standardized categorical values
* Prepared the dataset for SQL Server and Power BI analysis

## 4. Loading Data into SQL Server

After cleaning the data in Python, the dataset was loaded into SQL Server.

Key tasks performed:

* Connected Python with SQL Server
* Created a SQL Server database
* Loaded the cleaned dataset into a SQL table
* Verified the data using SQL queries
* Checked row counts and sample records

## 5. SQL Analysis

SQL queries were written in SQL Server Management Studio to answer business questions.

Examples of analysis performed:

* Total number of purchases
* Total sales amount
* Top-selling products
* Category-wise sales analysis
* Discount-based purchase analysis
* Customer purchase behavior
* Payment method analysis
* Product performance comparison

## 6. Power BI Dashboard

An interactive Power BI dashboard was created to visualize the insights.

Dashboard features:

* KPI cards for key business metrics
* Sales analysis by category and product
* Customer purchase behavior insights
* Discount usage analysis
* Location-wise performance
* Interactive filters and slicers
* Clean and professional dashboard layout

## 7. Report Creation

A report was created to summarize the complete analysis.

The report includes:

* Project objective
* Dataset description
* Data cleaning summary
* SQL analysis results
* Dashboard screenshots
* Key insights
* Final recommendations

## 8. PPT Creation Using Gamma

A presentation was created using Gamma to explain the project in a professional format.

The PPT includes:

* Project introduction
* Tools used
* Workflow
* Dashboard overview
* Business insights
* Final conclusion

## Dashboard

The Power BI dashboard provides a clear view of customer shopping behavior and business performance.

It helps answer questions such as:

* Which products and categories generate the most sales?
* How do discounts affect purchases?
* Which locations have higher customer activity?
* What are the key shopping patterns?
* Which products perform better based on purchase behavior?

## Results and Insights

Key outcomes from the project:

* Identified top-performing products and categories
* Analyzed customer purchase behavior
* Found discount usage trends across products
* Generated SQL-based business insights
* Built an interactive dashboard for decision-making
* Created a professional report and presentation for project communication

## How to Run This Project

1. Clone this repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Open the Jupyter Notebook

```bash
jupyter notebook
```

3. Install required Python libraries

```bash
pip install pandas pyodbc sqlalchemy
```

4. Load the dataset in Python

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
df.head()
```

5. Clean and explore the dataset using the notebook.

6. Connect Python with SQL Server and load the cleaned data into a SQL table.

7. Run SQL queries in SQL Server Management Studio.

8. Open the Power BI file and refresh the data connection.

9. Review the dashboard, report, and presentation.

## Project Folder Structure

```text
Data-Analytics-Project/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── data_cleaning_eda.ipynb
│
├── SQL/
│   └── sql_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
├── PPT/
│   └── project_presentation.pdf
│
└── README.md
```

## Conclusion

This project shows a complete data analytics workflow from data loading and cleaning to SQL analysis, dashboard creation, reporting, and presentation. It demonstrates practical skills in Python, SQL Server, Power BI, and business data storytelling.

## Author

**Your Name**
Data Analytics Enthusiast
GitHub: https://github.com/your-username
LinkedIn: https://www.linkedin.com/in/your-linkedin-profile
