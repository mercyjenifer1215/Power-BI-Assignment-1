# Power BI Project 1 – Data Transformation & Data Modeling

## About the Project

This is my first Power BI project as an aspiring Data Analyst. This project focuses on importing, cleaning, transforming, combining, and modelling sales data using Power BI Desktop and Power Query Editor.

The main objective is to prepare raw data for analysis and create a structured data model.

## Dataset

This project uses three CSV files:

- **List of Orders.csv** – Contains order, customer, date, city, and state information.
- **Order Details.csv** – Contains category, sub-category, amount, profit, and quantity information.
- **Sales Target.csv** – Contains monthly sales target information.

## Tools Used

- Microsoft Power BI Desktop
- Power Query Editor
- CSV Files

## Project Tasks & Implementation

### 1. Data Import
- Imported List of Orders.csv into Power BI.
- Opened Power Query Editor using Transform Data.
- Imported Order Details.csv and Sales Target.csv.

### 2. Row Limiting & Data Types
- Restricted the List of Orders table to the first 500 rows.
- Changed Order Date to Date data type.
- Changed Amount and Target columns to Fixed Decimal Number.

### 3. Text Formatting
- Applied Proper Case formatting to the CustomerName column.
- Used Capitalize Each Word to maintain consistent capitalization.

### 4. Column Creation
- Merged City and State columns into a new column named Location.
- Created a custom column named Profit Margin using Profit / Amount.
- Changed Profit Margin to Percentage format.

### 5. Conditional Column
Created a new column named Profit Status using the following conditions:

- Profit < 0 → Loss
- Profit = 0 → Break-Even
- Profit > 0 → Profit

### 6. Merging Data (Joins)
- Merged List of Orders and Order Details using Order ID.
- Created a merged output table named Orders Data.

### 7. Handling Missing Data & Duplicate Data
- Checked all tables for missing and blank values.
- No null or blank values were found during the check.
- Checked duplicate records and applied duplicate removal based on business requirements.

### 8. Sorting and Filtering Data
- Sorted Orders Data by Order Date in descending order.
- Applied filters to analyse orders from Tamil Nadu.

### 9. Grouping and Aggregating Data

Created summary tables by duplicating the original tables.

Performed the following aggregations:

- Count of Order ID.
- Average Profit by Category.
- Total Amount by Sub-Category.
- Total Target by Month.

### 10. Data Modeling
- Established a relationship between List of Orders and Order Details using Order ID.
- Established the requested relationship between Order Details and Sales Target using Category.
- Used Manage Relationships to check relationship settings and active status.

## Skills Demonstrated

- Data Import and Transformation
- Data Cleaning using Power Query
- Data Type Conversion
- Text Formatting
- Custom Column Creation
- Conditional Column Creation
- Data Merging and Joins
- Handling Missing and Duplicate Data
- Sorting and Filtering
- Grouping and Aggregation
- Data Modeling and Relationships

## Project Files

- Power BI project 1.pbix – Power BI project file.
- Power BI Assignment 1.pdf – Project assignment and documentation.

## Learning Outcome

Through this project, I gained practical experience in data importing, data cleaning, transformation, aggregation, and data modelling using Power BI.

This project helped me understand how raw data can be transformed into structured data ready for business analysis.

---

**Project Name:** Power BI Project 1 – Data Transformation & Data Modeling

**Role:** Aspiring Data Analyst

**Tool:** Microsoft Power BI Desktop
