# Pharmaceutical Sales Analysis & Insights: Analyzing Trends, Performance and Market Dynamics

For this project, we’ve been tasked with analyzing a global pharmaceutical manufacturing company's raw sales data and drawing meaningful insights. This project addresses the needs of key stakeholders (Executive Committee, Sales Managers, and Head of Sales) through detailed visualizations and reports.

📌 Project Objectives:
# 1. Executive Committee Dashboard
High-level overview of sales performance by:
Year & Month
Customer Cities
Sales Channels & Sub-Channels
Identify:
Top Drug Class by Sales
Top Drug by Sales
Top Customer City by Sales

# 2. Sales Manager/Sales Rep Dashboard 
Detailed breakdown of:
Sales by Distributors & Products
Top 5 Products, Customers, and Cities
Channel & Sub-Channel Sales

# 3. Head of Sales Dashboard 
In-depth analysis of:
Sales by Sales-Team & Product
Sales by Sales-Team & Product Class
Top Sales Managers & Reps
Top Products by Sales-Team Contribution
Interactive Filters/Slicers by Year and Month

📈 Deliverables:
✅ Executive Summary Dashboard for High-Level Insights
✅ Sales Manager Dashboard for Product & Customer-Level Analysis
✅ Head of Sales Dashboard with Team & Performance Breakdown
✅ Dynamic Filters for Customized Time-Based Analysis


🔍 Exploratory Data Analysis (EDA) [pandas]
Initial data exploration was performed using the pandas Python package for faster and more efficient handling of large datasets. Key checks included:

Identifying missing, unusual, and incorrect values (e.g., negative sales).
Differentiating between categorical and numeric columns.
Understanding the range and distribution of values.

EDA steps are documented in the data-exploration.ipynb notebook.

🧹 Data Cleaning & Transformation [Power Query Editor]
Minimal cleaning was required as the dataset was well-structured. Key actions included:

Standardizing column names.
Assigning correct data types.


📊 Data Model Creation [Power BI Desktop]
A star schema was built by separating dimensions (categorical) and facts (numeric), enabling efficient data relationships and better performance.


📊 Report Descriptions
✔ Executive Summary Report (Sales Overview) 
Provides a high-level overview of overall sales performance, offering key insights by year, month, customer city, channel, and sub-channel.

✔ Distributor & Customer Analysis Report 
Delivers a detailed breakdown of sales from the distributor and customer perspectives. Includes drill-down capabilities to analyze sales by product.

✔ Sales Team Performance Report 
Analyzes the sales team’s performance, with insights on sales by product class and specific products. Includes drill-downs and time-based filters (year/month).

