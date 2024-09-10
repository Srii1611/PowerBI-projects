# Power BI Sales Analysis Dashboard

## Overview

This repository contains a **Power BI Sales Analysis Dashboard** developed to provide key insights into sales performance through various analytical lenses. The dashboard is designed to help businesses make informed decisions by analyzing key metrics such as sales, orders, and quantities across different dimensions like time, location, and product category.

## Problem Statement

The dashboard addresses the following Key Performance Indicators (KPIs):

1. **Total Sales Analysis**:
   - Calculate total sales for each month.
   - Determine the month-on-month (MoM) increase or decrease in sales.
   - Compare sales between the selected month and the previous month.

2. **Total Orders Analysis**:
   - Calculate the total number of orders for each month.
   - Determine MoM changes in the number of orders.
   - Compare orders between the selected month and the previous month.

3. **Total Quantity Sold Analysis**:
   - Calculate the total quantity sold for each month.
   - Analyze the MoM increase or decrease in total quantity sold.
   - Compare the quantity sold between the selected month and the previous month.

## Charts & Visualizations

The dashboard includes various charts that offer a detailed analysis of sales performance:

1. **Calendar Heat Map**:
   - Dynamically adjusts based on the selected month.
   - Color-coded by sales volume (darker shades indicate higher sales).
   - Includes tooltips to display metrics like sales, orders, and quantity when hovering over specific days.

2. **Sales Analysis by Weekdays and Weekends**:
   - Segments sales data into weekdays and weekends for performance comparison.
   - Highlights patterns to determine whether there are significant differences between weekday and weekend sales.

3. **Sales Analysis by Store Location**:
   - Visualizes sales data by different store locations.
   - Includes MoM difference metrics for each store.
   - Highlights store-wise sales increases or decreases to identify trends.

4. **Daily Sales Analysis with Average Line**:
   - Displays daily sales for the selected month in a line chart.
   - Includes an average sales line to identify exceptional days.
   - Highlights bars for days with sales exceeding or falling below average.

5. **Sales Analysis by Product Category**:
   - Analyzes sales performance across different product categories.
   - Provides insights into which product categories contribute the most to overall sales.

6. **Top 10 Products by Sales**:
   - Displays the top 10 products based on sales volume.
   - Allows for quick identification of best-performing products.

7. **Sales Analysis by Days and Hours**:
   - Utilizes a heat map to visualize sales patterns by days and hours.
   - Includes tooltips to display detailed metrics when hovering over specific day-hour cells.

## Key Features

- **Dynamic Visualizations**: The dashboard is interactive, allowing users to drill down into data for deeper insights. Slicers are used for filtering data by month, store, and other key metrics.
- **Performance Tracking**: MoM performance is analyzed, helping stakeholders track growth or decline in various areas like sales, orders, and quantities.
- **Exceptional Days**: The analysis highlights exceptional sales days, providing a clear picture of performance anomalies.
- **Custom Tooltips**: Detailed tooltips provide additional metrics when hovering over different sections, improving the user experience.

## Usage

This dashboard is ideal for retail managers, business analysts, and decision-makers who want to monitor sales trends, identify top-performing products, and make data-driven decisions to boost performance.

## Technologies Used

- **Power BI**: Used to create all visualizations, dynamic filtering, and interactive charts.
- **Excel/CSV**: Dataset containing sales, orders, and product information.
- **DAX (Data Analysis Expressions)**: Utilized for creating calculated measures and advanced analytics.

## How to Run the Project

1. Download the `.pbix` file from this repository.
2. Open the file in Power BI Desktop.
3. Adjust filters and slicers based on your desired view, such as selecting different months, store locations, or product categories.
4. Explore the dashboard to gain insights into sales performance across different metrics.

## Conclusion

The **Power BI Sales Analysis Dashboard** offers a comprehensive view of sales data, enabling users to track key performance indicators and make informed business decisions. With dynamic visualizations, customizable tooltips, and detailed analysis, this dashboard is a powerful tool for any retail or sales-driven business.
