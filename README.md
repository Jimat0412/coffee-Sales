# Coffee Shop Sales & Order Performance Analysis

### Table of contents 

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Summary](#summary)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
- [References](#references)

### project Overview

The objective of this project is to analyze sales and order data for a coffee shop on a monthly basis, identify trends, and provide insights into sales performance and customer ordering behavior. This analysis will help the business understand its revenue patterns, identify growth opportunities, and make informed decisions for future strategies.

### Data Sources

the primary dataset used for this analysis is the "Coffee Shop Sales .xlsx" file, containing detailed information about sales and customer ordering trends on a monthly and years basis.
(Source: Maven Analytics)

(License: Public Domain)

### Tools
- Excel - Data Cleaning
   - [Download Here](https://app.mavenanalytics.io/datasets?search=cof)
- MYSQL - Data Analysis
- PowerBI - Data Visualization/ Creating a Report

### Data Cleaning

 in the initial data preparation phase, I performed the following tasks:
 1. data loading and inseption
 2. data cleaning and formatting

### Exploratory Data Analysis

Here are the steps and insights gained from performing EDA on the Coffee Shop Sales & Order Performance Analysis:

1. How have Maven Roasters sales trended over time?

2. Which days of the week tend to be busiest, and why do you think that's the case?

3. Which products are sold most and least often? Which drive the most revenue for the business?


### Data Analysis

include some interesting code/features worked with

```MYSQL

SELECT ROUND(SUM(unit_price * transaction_qty)) as Total_Sales 
FROM coffee_shop_sales 
WHERE MONTH(transaction_date) = 5 -- for month of (CM-May);
;
```

### Results

The analysis results are summarized as follows:
Coffee sales likely show growth over time, with weekends and certain weekdays being the busiest. Regular coffee sells the most, while premium items contribute significantly to revenue. Use these insights to optimize staffing, inventory, and promotions.

### Recommendation 

Based on the analysis, We recommend the following actions:
1. Increase staff and inventory on busy days.
2. Promote popular items like regular coffee.
3. Highlight high-revenue premium products.
4. Boost sales during slow periods with targeted promotions.
5. Optimize inventory based on sales trends.

### Limitations 

1. The dataset has limitations, including missing data, lack of customer information, a short time frame, no cost details, and not accounting for external factors.

### References

[Link Here](https://www.linkedin.com/in/datatutorials/)

