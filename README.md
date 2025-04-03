# SQL-quaries-Data-cleaning
A collection of SQL queries for cleaning, standardizing, and validating data, ensuring consistency and quality in datasets.

# SQL Queries for Data Cleaning, Standardization, and Validation

This repository contains a collection of SQL queries designed to help with data cleaning, standardization, and validation. These queries are useful for preparing data for analysis, ensuring consistency, and improving data quality. The queries cover various scenarios including:

- **Phone Number Standardization**: Removes non-numeric characters from phone numbers, ensuring a consistent format.
- **Outlier Detection and Removal**: Identifies and removes outliers in numerical data using Z-scores to avoid skewed analysis results.
- **Text Standardization**: Standardizes text data by trimming extra spaces and converting text to lowercase.
- **Category Correction**: Corrects inconsistent category names to a uniform format (e.g., grouping similar terms like "cat", "cats" into a single category "Cat").
- **Data Range Validation**: Checks for data values that fall outside of a valid range, such as negative values or out-of-bound numbers.
- **Data Integrity Checks**: Ensures referential integrity by identifying records that do not match in linked tables, such as orders with non-existent customer IDs.

### Purpose:
These SQL queries serve as templates for common data cleaning tasks, helping data analysts and engineers automate the preparation process and maintain clean, reliable datasets for analysis or reporting.

### Usage:
- Copy the relevant SQL query and modify it according to your database schema and requirements.
- Use these queries as part of your ETL (Extract, Transform, Load) pipeline or data preprocessing workflow.

### How to Contribute:
Feel free to fork this repository and submit pull requests with any improvements or additional SQL queries.

