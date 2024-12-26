# Dynamic_Retail_dashboard
Dynamic Retail Dashboard
This repository contains a Dynamic Retail Dashboard built using data from three key tables: Orders, People, and Returns. The dashboard provides insightful analyses and critical Key Performance Indicators (KPIs) to aid in understanding retail performance and making informed business decisions.

Objective
The primary goal of this project is to design an interactive and dynamic dashboard that allows users to:

Monitor key metrics such as total sales, profits, and order statistics.
Analyze sales trends based on categories, segments, and regions.
Use data-driven insights to make informed business decisions.
Data Overview
The dashboard is built on the following datasets:

Table	Description	Sample Data
Orders	Contains transaction details like customer and product information.	Row ID: 32298
Order ID: CA-2012-124891
Order Date: 31-07-2020
Customer Name: Rick Hansen
Segment: Consumer
Category: Technology
Sales: 2309.65
Profit: 762.18
People	Provides regional information about customers for segmentation analysis.	Person: Anna Andreadi
Region: Central
Returns	Tracks orders that have been returned.	Order ID: US-2011-165316
Returned: Yes
Market: LATAM
Key Analyses
The following insights have been derived using the dashboard:

KPI Overview:

Total sales, total profit, total quantity, number of orders, and profit margin.
Profit and Sales Analysis:
       ![image](https://github.com/user-attachments/assets/de09d42c-04c0-4cb3-a67c-852b2d56e4ea)

Analyzed the relationship between sales and profits to identify trends.
Category-wise Performance:
      ![image](https://github.com/user-attachments/assets/da505bd7-5ced-47ef-b073-2b74de31706e)


Evaluated profit contributions from different product categories.
Segment Analysis:
      ![image](https://github.com/user-attachments/assets/40034b9c-be0f-4ad3-873c-e4113356b016)

Analyzed sales share across customer segments.
Geographic Insights:
       ![image](https://github.com/user-attachments/assets/f72cbd22-bdd4-44f2-91b4-62a6beac6d39)
 
Performed country-wise and region-wise sales performance analysis.
Top & Bottom Subcategories:
      ![image](https://github.com/user-attachments/assets/c0bbeb86-870b-46eb-85a5-35df912fe8a4)

Identified the top 5 best-performing and bottom 5 underperforming subcategories.
Yearly Trends:
       ![image](https://github.com/user-attachments/assets/ca2a815a-e66f-4182-932b-55dee32eaab2)

Visualized yearly sales performance to spot growth or decline patterns.
Dynamic KPI Table
Metric	Description	Symbol
Total Sales	Sum of Sales	💰
Total Profit	Sum of Profit	📈
Total Quantity	Sum of Quantity	📦
Number of Orders	Count of Order IDs	🛒
Profitability	Sum of Profit Margin (%)	💹
Average Discount	Average of Discounts	🔍
Implementation Steps
Step 1: Data Preparation
Import and clean the datasets (Orders, People, Returns).
Handle missing values and ensure correct data types.
Step 2: Data Integration
Merge the Orders and Returns tables using Order ID for return analysis.
Link the People table to Orders based on Region.
Step 3: Create KPIs
Design a KPI table to dynamically calculate essential metrics like sales, profit, and more.
Step 4: Build the Dashboard
KPI Display: Highlight total sales, profits, and other metrics.
Interactive Filters: Add slicers for category, region, and segment.
Visualizations:
Bar charts for category performance.
Line graphs for yearly trends.
Top & bottom subcategories with comparative metrics.
Step 5: Insights Generation
Use the dashboard to identify trends and answer key business questions.
Next Steps
To enhance the dashboard, future developments will focus on:

Return Analysis: Understanding return rates and their impact on profitability.
Customer Insights: Identifying the most and least profitable customers.
Market Analysis: Analyzing performance across various markets.
Product Performance: Diving deeper into product-specific metrics.
Conclusion
The Dynamic Retail Dashboard offers a powerful solution for analyzing retail performance. By leveraging KPIs and interactive visualizations, it empowers users to make data-driven decisions and optimize business strategies. As enhancements are implemented, this tool will continue to deliver deeper insights and value for retail management.

      
![image](https://github.com/user-attachments/assets/8a0c263b-0293-4310-8f68-6b5242ba9d0a)

