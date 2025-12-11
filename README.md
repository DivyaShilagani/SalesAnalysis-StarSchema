This Power BI project focuses on analyzing sales performance data for a retail business using a complete end-to-end BI workflow. Built using Power BI Desktop and a Star Schema data model, the dashboard delivers actionable insights on product performance, sales trends, profit behavior, discounts, and geographical sales distribution. The goal is to enable business users and analysts to understand sales patterns, compare metrics across periods, and make informed decisions backed by interactive visual analytics.

Objectives are:

- Data Integration: Import sales, product, customer, date, and promotion data into Power BI Desktop.
- Data Cleaning: Perform data profiling and transformation using Power Query (data type corrections, removing duplicates, trimming text, handling nulls, and preparing dimension tables).
- Data Modeling: Design a Star Schema with a central Fact table and multiple Dimension tables.
Define relationships using primary and foreign keys with correct cardinality.
- DAX Calculations: Create DAX measures for Total Sales, Profit, Quantity Sold, Net Sales, Average Discount, and Time-Intelligence metrics for period-over-period comparison.
- Visual Analytics: Build interactive visuals including bar charts, line charts, scatter plots, maps, and comparison visuals to analyze trends and relationships.
- Sales Performance Analysis: Identify Top/Bottom 5 products by Sales, Profit, and Quantity Sold, and analyze sales variations across time intervals (daily, monthly, quarterly, annually).
- Custom Requirements Implementation: Display detailed per-order metrics with slicers for Product, Date, Customer ID, and Promotion Category, and showcase total orders and city-level sales insights.
- Interactivity & UX Enhancements: Use Edit Interactions, slicers, and custom filter behaviors for dimension tables to improve user navigation and analytical flexibility.

📊 Project Overview

- Data Source: Sales dataset used in the Udemy course, containing product, customer, discount, promotion, and order-level data.
- Data Preparation:
  - Loaded raw data into Power BI Desktop.
  - Cleaned and transformed data using Power Query.
  - Standardized columns, formatted date fields, and built dimension tables.
- Modeling:
  - Designed a Star Schema with a Sales Fact table linked to Product, Customer, Date, and Promotion dimensions.
  - Created DAX measures to support the eight analytical requirements.
  - Configured many-to-one relationships and ensured referential integrity.
- Visualizations:
  - Top/Bottom 5 Products: Bar charts for Sales, Profit, and Quantity Sold.
  - Sales Trends: Line chart showing daily, monthly, quarterly, and yearly variations.
  - Sales vs Profit Relationship: Scatter chart to analyze correlation.
  - Period Comparison: Visuals comparing product metrics between any two user-selected periods.
  - Discount Analysis: Category-wise average discount visuals.
  - Order-level Analysis: Table visual showing Sales, Profit, Discount, Net Sales, and other metrics.
  - Sales by City: Map showing city-level sales distribution.
- Interactivity:
  - Slicers for Product, Date, Customer ID, and Promotion Categories.
  - Customized interactions among visuals to avoid unwanted filtering.
  - Enhanced user experience with clear navigation and filter behaviors between dimension tables.
