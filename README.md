Blinkit Grocery Data Analysis Dashboard - Power BI Project

Overview
This repository showcases a comprehensive Power BI dashboard designed to analyze Blinkit's grocery business data. The dashboard provides actionable insights into sales performance, customer preferences, outlet operations, and product trends. It empowers stakeholders to make data-driven decisions with a visually intuitive layout.

Key Features
The dashboard includes:

Total Sales: Displays overall revenue generated.
Average Sales: Tracks the average sales per transaction.
Number of Items: Indicates the total quantity of items sold.
Average Rating: Provides customer satisfaction scores.
Detailed Insights

Outlet Establishment:
Analysis of sales by outlet establishment year.
Identification of revenue trends over time.

Outlet Size and Location:
Total sales distribution by outlet size (Medium, Small, High).
Sales performance segmented by location tiers (Tier 1, Tier 2, Tier 3).

Product Analysis:
Breakdown of sales by item type (e.g., Fruits, Snacks, Frozen items).
Fat content sales comparison (Low Fat vs. Regular).

Outlet Type:
Comparison of total sales, number of items sold, average sales, and customer ratings across different outlet types.

Visuals
The dashboard employs:

Cards for KPIs like Total Sales, Average Sales, and Average Rating.
Line Chart for sales trends by outlet establishment year.
Donut Charts for outlet size and fat content analysis.
Bar Charts for sales by item type, fat content, and location tiers.
Tables for outlet performance, combining metrics like total sales, average sales, and item visibility.

Dataset
The dataset contains the following columns:

Outlet Details: Size, location, establishment year, and type.
Product Details: Item type, fat content, and visibility.
Sales Metrics: Total sales, number of items, and average sales.
Customer Feedback: Average rating.
Tools and Techniques
Data Cleaning: Used Power Query for transforming raw data.
Data Modeling: Established relationships between tables for efficient analysis.


DAX Measures: Created custom calculations for KPIs.
Average Sales:
DAX
Avg Sales = DIVIDE(SUM(Sales[Total Sales]), COUNT(Sales[Transactions]))

Fat Content Analysis:
DAX
Low Fat % = DIVIDE(SUM(Sales[Low Fat Sales]), SUM(Sales[Total Sales]))



Contact
For any questions or suggestions, feel free to contact:

Name: Anshumaan Tiwari
Email: [tiwarianshumaan.meet@gmail.com]
LinkedIn: www.linkedin.com/in/tiwari-anshumaan
