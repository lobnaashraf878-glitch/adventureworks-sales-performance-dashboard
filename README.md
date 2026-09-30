AdventureWorks Sales Performance Dashboard

An interactive Power BI dashboard for analyzing sales performance, revenue, profit, orders, returns, products, customers, and geographic distribution using the AdventureWorks business dataset.

Repository Name

adventureworks-sales-performance-dashboard

Repository Description


Interactive Power BI dashboard for analyzing AdventureWorks sales, revenue, profit, orders, returns, products, customers, and regional performance.

Overview

This project presents a comprehensive sales and business-performance dashboard built with Microsoft Power BI. It provides executive-level KPIs as well as detailed product, customer, and geographic analysis.

The report is designed to help business users monitor performance, identify profitable products, understand customer behavior, evaluate return rates, and compare order activity across countries and continents.

Report Pages

1. Executive Dashboard

The executive page provides a high-level overview of business performance, including:

•
Total revenue

•
Total profit

•
Total orders

•
Return rate

•
Revenue trend over time

•
Four-week moving average

•
Month-over-month revenue, orders, and returns KPIs

•
Orders by product category

•
Product-level performance table

•
Selected subcategory metrics

2. Map

The map page shows the geographic distribution of orders by country and supports filtering by:

•
Continent

•
Country

•
Total orders

This page helps identify the strongest and weakest regional markets.

3. Product Details

The product details page evaluates a selected product against performance targets:

•
Orders compared with the order target

•
Revenue compared with the revenue target

•
Profit compared with the profit target

•
Profit trends by product

•
Returns trends by product

•
Selected product name and product-level context

4. Customer Detail

The customer detail page analyzes customer volume, value, and segmentation:

•
Total customers

•
Average revenue per customer

•
Customer growth over time

•
Orders by income level

•
Orders by occupation

•
Customer-level order and revenue table

•
Selected customer KPIs

•
Year filter

5. Custom Tooltip

The custom tooltip provides additional context when users hover over relevant visuals, including:

•
Total profit

•
Total orders

•
Total revenue

•
Total returns

•
Return rate

•
Order trends over time

Key KPIs

KPI
Description
Total Revenue
Total sales revenue within the selected report context
Total Profit
Total profit generated from sales
Total Orders
Total number of orders
Return Rate
Percentage of orders or products returned
Total Returns
Total return activity
Total Customers
Number of customers in the selected context
Average Revenue Per Customer
Average revenue generated per customer
4W Moving Average
Four-week moving average used to smooth revenue trends
Previous Month Revenue
Revenue from the previous month for period comparison
Previous Month Orders
Orders from the previous month
Previous Month Returns
Returns from the previous month




Main Analyses

Sales and Financial Performance

Track revenue, profit, and order volume to understand overall business performance and identify changes over time.

Trend Analysis

Analyze revenue and order trends using time-based visuals, including the four-week moving average and comparison with previous months.

Product Performance

Compare product categories, subcategories, and individual products by orders, revenue, profit, and return rate.

Return Analysis

Monitor total returns and return rates to identify products or categories that may require quality, pricing, or customer-experience review.

Customer Analysis

Understand customer volume and value through average revenue per customer, customer-level revenue, order activity, income-level segmentation, and occupation analysis.

Geographic Analysis

Use the map page to identify order concentration by country and continent and support regional sales planning.

Data Model

The report contains a star-schema-style model with lookup and fact tables, including:

•
Sales Data — transactional sales and order-level data

•
Product Lookup — product attributes and product names

•
Subcategories Lookup — product subcategory information

•
Categories Lookup — product category information

•
Customer Lookup — customer identity and segmentation attributes

•
Territory Lookup — country, continent, and geographic attributes

•
Calendar Lookup — date and time intelligence fields

•
Measure Table — centralized DAX measures used throughout the report

Key Measures

The dashboard uses measures including:

•
Total Revenue

•
Total Profit

•
Total Orders

•
Total Returns

•
Return Rate

•
Total Customers

•
Average Revenue Per Customer

•
4W Moving Average

•
Previous Month Revenue

•
Previous Month Orders

•
Previous Month Returns

•
Order Target

•
Revenue Target

•
Profit Target

Report Interactions

The report includes:

•
Page navigation between executive, map, product, and customer views

•
Drill-through or selected-product context on product details

•
Selected-customer context on customer details

•
Geographic filtering by continent

•
Time filtering by year and calendar context

•
Dynamic custom tooltips

•
KPI comparisons against previous periods and targets

Tools and Technologies

•
Microsoft Power BI Desktop

•
Power Query

•
DAX

•
Data modeling and star-schema concepts

•
Time intelligence

•
Interactive geographic visualization

•
Custom tooltips and page navigation

Getting Started

1.
Download or clone this repository.

2.
Open the .pbix file using Power BI Desktop.

3.
Review the data source and update credentials or file paths if required.

4.
Refresh the data model.

5.
Start from the Executive Dashboard page.

6.
Use page navigation, filters, product selections, and customer selections to explore the report.

Bash


git clone https://github.com/<your-username>/adventureworks-sales-performance-dashboard.git



Suggested Repository Structure

Plain Text


adventureworks-sales-performance-dashboard/
├── README.md
├── AdventureWorks_Dashboard.pbix
├── assets/
│   └── dashboard-preview.png
└── docs/
    └── data-dictionary.md



Business Questions Answered

•
What are the current revenue, profit, order, and return-rate levels?

•
How is revenue trending over time?

•
How does current performance compare with the previous month?

•
Which product categories generate the most orders?

•
Which products generate the highest revenue and profit?

•
Which products or categories have the highest return rates?

•
Are products meeting their order, revenue, and profit targets?

•
Which countries and continents generate the most orders?

•
How many customers are active in the selected context?

•
What is the average revenue per customer?

•
How do orders differ by income level and occupation?

•
How does customer activity change over time?

Recommended Uses

•
Executive sales reporting

•
Monthly and weekly performance reviews

•
Product portfolio analysis

•
Regional sales analysis

•
Customer segmentation

•
Profitability monitoring

•
Return-rate and product-quality analysis

•
Sales target tracking

Notes

•
KPI values update dynamically based on the current filter and selection context.

•
Validate the definitions of profit, return rate, targets, and previous-period calculations before using the report for official business reporting.

•
Review data refresh settings and source credentials before publishing to Power BI Service.

•
Do not commit confidential or personally identifiable customer information to a public repository.

License

Add the license that matches your organization or project requirements. For educational or internal dashboards, document the permitted use of the AdventureWorks dataset and keep any proprietary extensions private.

