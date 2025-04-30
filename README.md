## Overview
This project involves analyzing pizza sales data using Power BI. The goal is to create interactive reports and dashboards that visualize key metrics, identify trends, and provide insights into pizza sales performance. By leveraging Power BI, the project enables easy-to-understand visualizations that assist decision-makers in evaluating sales trends, popular pizza types, promotions, and more.

## Project Scope
Dataset Overview: The dataset contains pizza sales transactions including customer demographics, order details, promotions, and sales information.

## Key Objectives:

Visualize overall sales trends over time (daily, weekly, monthly).

Highlight top-selling pizza types.

Analyze the impact of promotions on sales.

Segment customers by purchase behavior.

Provide actionable insights using interactive Power BI dashboards.

Tools & Technologies Used
Power BI Desktop: Main tool for creating interactive reports and dashboards.

Power BI Service: (Optional) If deploying the reports to the cloud.

Data Source: Excel/CSV/SQL (depending on how data is stored).

Dataset
The dataset contains the following columns:

OrderID: Unique identifier for each order.

CustomerID: Unique identifier for each customer.

PizzaType: Type of pizza ordered.

OrderDate: Date of the order.

Quantity: Number of pizzas ordered.

Price: Price per pizza.

Data Preprocessing Steps in Power BI
Data Import: Imported the dataset into Power BI using the Get Data feature (CSV, Excel, or SQL connection).

Data Transformation: Used Power Query Editor for:

Removing unnecessary columns.

Handling missing values.

Changing data types (e.g., DateTime for OrderDate).

Creating Calculated Columns: Added new columns such as:

DayOfWeek to determine if the sale occurred on a weekday or weekend.

Year and Month for time-based analysis.

Creating Measures: Defined key metrics such as:

Total Sales (sum of TotalSales column).

Average Order Value (average of TotalSales).

Sales Growth (comparison of current sales with previous periods).

## Key Insights & Visualizations
Sales Trends: Visualized sales trends using line charts to show daily, weekly, and monthly sales.

Top-Selling Pizzas: Created a bar chart to show the top 5 best-selling pizzas based on quantity and total revenue.

Impact of Promotions: Used a stacked column chart to show sales with and without promotions, and a DAX measure to compare the effectiveness of promotions.

Customer Segmentation: Created pie charts and bar charts to analyze customer demographics and their purchasing behaviors.

Sales by Region: Created a map visualization to display sales data based on geographic regions (if location data is available).

# License
This project is licensed under the MIT License - see the LICENSE file for details.


Dashboard Features
Interactivity: Users can interact with the dashboard by filtering sales data based on:

Date range (Month, Week, Year).

Pizza type.

Region.

Promotion status.

Key Metrics: The dashboard highlights:

Total sales revenue.

Number of orders.

Average order value.

Customer segmentation insights.
