# LITA_PROJECT

### Project Title: Sales Performance Analysis for A Retail Store

### Project Overview 

This project aims to analyze sales data for retail store to identify trends, patterns, and areas for improvement. The analysis will provide insights into sales performance, customer behavior, and product preferences, enabling data-driven decisions to drive business growth.

### Data Source

The primary source of data used is Data Sale.csv and this is an open source data that can be freely downloaded from an open source online such ad Kaggle or any other data repository site.

### Tools Used

- Microsoft Excel [Download here] (https://www.microsoft.com)
  1. For Data Cleaning
  2. For Data Analysis
  3. Data Visualization
- SQL (Structured Query Language) for query of Data
- PowerBi
  1. For Data VIsualization
  2. Data Modelling
  3. Data Analysis
  4. Data Reporting
  5. Business Intelligence
- GitHub for Potfolio Building

### Data Cleaning and Preparation

  In the inital phase of the Dat Cleaning and Preparation, we perform the following action
  - Data loading and inspection.
  - Handling missing values.
  - Removing duplicates.
  - Data Transformation.
  - Data Quality checks.
  - Data Cleaning and formatting.

### Exploratory Data Analysis

  EDA involved the exploring of the data to answer some questions about the Data such as
  - Retrieve the total sales for each category.
  - Find the number of sales transactions in each region.
  - FInd the highest selling product by total sales value.
  - Calculate total revenue per product.
  - Calculate monthly sales totals for the current year.
  - Find the top 5 customers by total purchase amount.
  - To calculate the percentage of total sales contributed by each region.
  -Identify products with no sales in the last quarter.

### Data Analysis
  This is where we include some basics lines of codes or queries or even some DAX functions during our analysis.

  ```SQL
     Select  region, count(distinct Customerid) as total_customers 
from [dbo]
Group by region;

SELECT product, sum([Total_Sales]) AS Total_Sales
FROM [dbo].[LITA PROJECT SALES DATA]
GROUP BY product
ORDER BY SUM([Total_Sales]) DESC;

SELECT TOP 1 PRODUCT, SUM(quantity*[UnitPrice]) AS Total_Revenue
FROM [dbo].[LITA PROJECT SALES DATA]
GROUP BY product
```


### Data Visualization



![Sales Data](https://github.com/user-attachments/assets/f2a0c763-f0e5-433e-950f-a36179e38147)

