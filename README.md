# AdventureWorks-Power-BI-Project

AdventureWorks Business Intelligence Project
Objective
The goal of this project is to develop an interactive dashboard using Power BI Desktop for AdventureWorks, a global manufacturing company producing cycling equipment and accessories. The dashboard helps the management team track Key Performance Indicators (KPIs) such as sales, revenue, profit, and returns, compare regional performance, analyze product-level trends, and identify high-value customers.

Process
1. Connect and Transform Data
Data Sources: Raw CSV files containing information about transactions, returns, products, customers, and sales territories.
Data Import: Imported all CSV files into Power BI Desktop.
Data Cleaning: Cleaned and transformed the data using Power Query Editor.
Removed duplicates and irrelevant columns.
Standardized date formats.
Handled missing values.
2. Build a Relational Data Model
Data Relationships: Established relationships between different tables (transactions, products, customers, etc.) to create a cohesive data model.
Created primary and foreign key relationships.
Ensured referential integrity.
Schema Design: Organized tables into a star schema to optimize query performance.
3. Create Calculated Columns and Measures with DAX
Calculated Columns: Added columns to enhance data analysis.
Example: Total Sales = Quantity * Unit Price
Measures: Created measures to calculate KPIs.
Example: Total Revenue = SUM(Sales[Total Sales])
Example: Profit = [Total Revenue] - SUM(Sales[Total Cost])
Example: Return Rate = DIVIDE(SUM(Returns[Return Quantity]), SUM(Sales[Quantity]))
4. Design an Interactive Dashboard
Dashboard Elements: Designed various visuals and charts to represent the data.
Sales and Revenue Trends
Profit Analysis
Regional Performance Comparison
Product-Level Insights
High-Value Customer Identification
Interactivity: Added slicers and filters to allow dynamic data exploration.
Example: Date range slicer, product category filter, regional filter.
User Experience: Ensured the dashboard is user-friendly and provides actionable insights.
5. Publish and Share
Publishing: Published the Power BI report to the Power BI Service for easy sharing and collaboration.
GitHub Repository: Uploaded the .pbix file and related documentation to GitHub.
Dashboard Overview
Key Metrics
Revenue: $24.9M
Profit: $10.5M
Orders: 25.2K
Return Rate: 2.2%
Sales and Revenue Trends
Line charts showing monthly and yearly trends in sales and revenue.
Insights into peak sales periods and seasonal trends.
Profit Analysis
Bar charts and KPI cards highlighting total profit, profit margins, and cost breakdown.
Comparison of actual profit vs. target profit.
Regional Performance Comparison
Maps and bar charts comparing sales, revenue, and profit across different regions.
Identification of high and low performing regions.
Product-Level Insights
Detailed analysis of product performance including top-selling products, revenue by product category, and product return rates.
Example: The top product "Water Bottle - 30 oz." had 3,983 orders with a revenue of $39,755 and a return rate of 1.95%.
High-Value Customer Identification
Customer segmentation based on purchase history and lifetime value.
Identification of top customers contributing the most to the revenue.
Example: The top customer "Mr. Maurice Shan" made 6 orders totaling $12,408 in revenue.
