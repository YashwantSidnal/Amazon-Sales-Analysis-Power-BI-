📊 Amazon Sales Analysis Dashboard (Power BI)

📌 Overview

The Amazon Sales Analysis Dashboard is built using Power BI, providing interactive insights into sales performance, product engagement, and regional trends.

Key insights include:

Sales Performance: Revenue, Units Sold, Returns
Product Insights: Engagement, Ratings, Performance
Regional Analysis: Sales by City & State
Interactive Filtering & Drill-Throughs for deeper analysis

🛠 Built with:

Power BI for Data Visualization,
Power Query for Data Transformation,
DAX (Data Analysis Expressions) for Advanced Metrics,
Star Schema Data Modeling for Performance Optimization

🔹 Key Features

🛍 Product Analysis:-
Product Name, Image, Sales, Units Sold, Returns, Reviews
Drill-through Analysis to view individual product performance

📈 Sales & Trend Analysis:-
Sales Performance Over Time (Daily, Weekly, Monthly)
Customer Engagement: Views vs Purchases
Return Rate & Refund Analysis

🌍 Regional Sales Insights:-
Sales Breakdown by City & State
Order Status Tracking (Shipped, Cancelled, Pending)
Sales Trend Analysis & Forecasting

🛠 DAX & Power Query in Action:-
Total Sales: SUM(Sales[Sales_Amount])
Return Rate: DIVIDE(SUM(Sales[Returns]), SUM(Sales[Units_Sold]), 0)
Sales Growth: (Current Sales - Previous Month) / Previous Month
Custom Date Hierarchies for filtering & trends

🚀 How to Use

1️⃣ Open in Power BI Desktop: Load the .pbix file
2️⃣ Use Filters & Slicers: Explore sales trends & regional performance
3️⃣ Drill-Through Analysis: Click on products for deep insights
4️⃣ Publish to Power BI Service: Share reports with stakeholders
5️⃣ Access on Power BI Mobile: View insights anytime
