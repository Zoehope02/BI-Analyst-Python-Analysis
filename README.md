# Project Overview: Superstore Data Analysis

This project uses Python and Jupyter Notebook to explore analysis of Superstore’s sales data, with a focus on uncovering actionable insights across product performance, customer behavior, 
and regional trends. 

# Requirements
This notebook requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
You can install them using pip
# Visualisation Preview

![Dashboard](./overview2.0.png)

# Cleaning The Dataset

1.  **Removed the dollar sign ($)** from both the 'Profit' and 'Sales' columns.
   - This step was crucial to enable proper numerical conversion and prevent the symbol from being misinterpreted as a text character.
2.  **Converted the data type from string to numeric** for both the 'Profit' and 'Sales' columns.
   - This allows for accurate mathematical operations and aggregations, such as calculating Total Sales and Average Profit.

# EDA - Exploratory Data Analysis

Below are the questions that guided my analysis of this dataset, organized into the following categories:

1.  🛍️ Sales & Profitability
2.  🌎 Geographical Performance
3.  🕐 Time & Trends
4.  🚚 Shipping & Logistics
5.  📦 Discounts, Promotions & Customers

## Sales & Profitability: 
1. Which product categories generate the highest and lowest total sales?
2. Which Top 5 sub-categories have the highest average profit margins?
3. What is the overall profit-to-sales ratio for the business?
4. Which products are frequently sold at a loss?
5. Which customers have contributed the most to overall profit?

## Geographical Performance
1. Which states or regions generate the most revenue?
2. Are there any cities consistently generating negative profit?
3. How does sales and profit vary across different manufacturers?
4. Which cities have the highest average order quantity?

## Time & Trends
1. How do sales vary by day of the week?
2. Which months have the highest average sales?
3. Are there seasonal patterns in shipping times?
4. Has the average profit ratio improved or declined over time?
5.  What is the trend in discount usage over time?

## Shipping & Logistics
1. Which shipping mode has the fastest shipping time?
2. Does shipping mode impact overall profitability?

## Discounts, Promotions & Customers
1. Do higher discounts improve total profit?
2. What is the average discount applied by product category and sub-category?
3. Who are the Top 5 Customers generating the most Sales?
