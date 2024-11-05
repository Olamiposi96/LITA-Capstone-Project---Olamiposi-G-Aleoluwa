# LITA-Capstone-Project---Olamiposi-G-Aleoluwa
In this project, I was tasked with analyzing the sales performance of a retail store and analyzing customer data for a subscription service to identify  segments and trends. The goal is to produce an interactive Power BI  dashboard that highlights these findings

## Project 1 Title - Sales Performance Analysis

### Table of Content
[Project Overview](#project-overview)

[Data Sources](data-sources)

[Data Cleaning and Preparations](data-cleaning-and-preparation)

[Data Analysis](data-analysis) 

### Project Overview
In this project, I was tasked with analyzing the sales performance of a retail store. 
I am expected to explore sales data to uncover key insights such as top-selling products, regional 
performance, and monthly sales trends. The goal is to produce an interactive Power BI 
dashboard that highlights these findings.

### Data Sources
The primary source of data used is Sales Data.csv which was provided as part of the instruction

### Tools Used 
- Microsoft Excel for
   1. Data Cleaning
   2. Analysis.
- Structured Query Language (SQL) for Quring of Data.
- Power BI for Visualization
- GitHub for Portfolio Building

### Data Cleaning and Preparations
I performed the following actions in the cleaning phase
   1. Data Loading and Inspection
   2. Handling missing variables
   3. Data Cleaning and formatting

### Exploratory Data Analysis 
This involved exploring the data to answer some questions about the Data such as;
 - Summarizing the sales data to show total sales by product, region, and month using pivot tables 
 - Use Excel formulas to calculate metrics such as average sales per product and total revenue by region.

### Data Analysis 
This is where I queried my data 

```SQL
SELECT *
FROM [dbo].[Customer Data]
```
To Retrieve the total sales for each product category

```SQL
SELECT Product,SUM(Quantity) as Total_Sales
FROM [Sale Data]
GROUP BY Product
```

### Data Visualization



