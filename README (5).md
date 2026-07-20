# TASK-2-DATA-ANALYST
Project Overview

This project showcases an interactive Sales & Profit Insights Dashboard developed using Power BI.
The main goal of this project is to analyze business performance across multiple dimensions such as sales, profit, regions, product categories, customers, and time periods.

The dashboard provides dynamic filtering and actionable insights to support strategic business decisions.

<> Project Objectives

Evaluate overall sales and profit performance

Calculate and monitor Profit Margin percentage

Identify high-performing regions and product categories

Analyze yearly sales growth trends

Recognize top revenue-generating customers

Create an interactive and user-friendly dashboard

<> Key Performance Indicators (KPIs)

Total Sales: 718K

Total Profit: 47.74K

Profit Margin: 6.6%

Total Orders: 1462

<> Dashboard Highlights
<> Sales Growth Analysis

Sales trend analyzed from 2011 to 2014

Consistent year-over-year growth observed

Clear visualization of performance trends

<> Category Performance Analysis

Comparison across Furniture, Technology, and Office Supplies

Identification of top-selling product category

Profit contribution analysis by category

<> Regional Profit Insights

Strong profitability observed in North Asia and Central Asia

Identification of low-performing regions

Regional comparison using visual charts

<> Customer Contribution Analysis

Top customers ranked based on total sales

Helps in targeting loyal and high-value customers

Supports retention and marketing strategy

<> Interactive Dashboard Features

Filters available for:

Segment (Consumer, Corporate, Home Office)

Year (2011–2014)

Category

Region

Real-time visual updates based on user selection

<> Tools & Technologies Used

Power BI Desktop

DAX (Data Analysis Expressions)

Data Modeling

Interactive Visualizations

Slicers & Filters

<> DAX Measures Implemented
Total Sales = SUM(SuperStoreOrders[sales])

Total Profit = SUM(SuperStoreOrders[profit])

Total Orders = DISTINCTCOUNT(SuperStoreOrders[order_id])

Profit Margin % = DIVIDE([Total Profit], [Total Sales])

<> Business Impact

Enables data-driven decision-making

Identifies growth opportunities

Improves regional and category performance tracking

Supports strategic planning and performance monitoring
