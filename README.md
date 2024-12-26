# Dynamic Retail Dashboard
This repository contains a Dynamic Retail Dashboard built using data from three key tables: **Orders**, **People**, and **Returns**. The dashboard provides insightful analyses and critical Key Performance Indicators (KPIs) to aid in understanding retail performance and making informed business decisions.  

---

## **Objective**  
The primary goal of this project is to design an interactive and dynamic dashboard that allows users to:  

- Monitor key metrics such as total sales, profits, and order statistics.  
- Analyze sales trends based on categories, segments, and regions.  
- Use data-driven insights to make informed business decisions.  

---

## **Data Overview**  

The dashboard is built on the following datasets:  

| **Table**   | **Description**                                                                                 | **Sample Data**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Orders**  | Contains transaction details like customer and product information.                             | **Row ID**: 32298 <br> **Order ID**: CA-2012-124891 <br> **Order Date**: 31-07-2020 <br> **Customer Name**: Rick Hansen <br> **Segment**: Consumer <br> **Category**: Technology <br> **Sales**: 2309.65 <br> **Profit**: 762.18                                                                                           |
| **People**  | Provides regional information about customers for segmentation analysis.                        | **Person**: Anna Andreadi <br> **Region**: Central                                                                                                                                                                                                                                                                                                                                                                   |
| **Returns** | Tracks orders that have been returned.                                                          | **Order ID**: US-2011-165316 <br> **Returned**: Yes <br> **Market**: LATAM                                                                                                                                                                                                                                                                                                                                                           |

---

## **Key Analyses**  

The following insights have been derived using the dashboard:  

1. **KPI Overview**:  
   - Total sales, total profit, total quantity, number of orders, and profit margin.  

2. **Profit and Sales Analysis**:  
   - Analyzed the relationship between sales and profits to identify trends.
   - ![image](https://github.com/user-attachments/assets/6755f517-f529-4f31-9b6c-cec72770cd93)

3. **Category-wise Performance**:  
   - Evaluated profit contributions from different product categories.  
     ![image](https://github.com/user-attachments/assets/c67a79d4-41c7-4d4e-949e-06666286e305)

4. **Segment Analysis**:  
   - Analyzed sales share across customer segments.  
     ![image](https://github.com/user-attachments/assets/047ea96c-18ab-4f26-9554-1a1883aec1fc)

5. **Geographic Insights**:  
   - Performed country-wise and region-wise sales performance analysis.  
      ![image](https://github.com/user-attachments/assets/547807a1-ba91-4c35-ae2a-63fe25a61140)

6. **Top & Bottom Subcategories**:  
   - Identified the top 5 best-performing and bottom 5 underperforming subcategories.  
      ![image](https://github.com/user-attachments/assets/16e22f6f-f525-4c8d-bd70-9bcdfe20f830)

7. **Yearly Trends**:  
   - Visualized yearly sales performance to spot growth or decline patterns.  
      ![image](https://github.com/user-attachments/assets/a52cfe4f-5e64-4fa0-9615-7af0dac2a313)

---

## **Dynamic KPI Table**  

| **Metric**           | **Description**            | **Symbol** |  
|-----------------------|----------------------------|------------|  
| **Total Sales**       | Sum of Sales              | 💰         |  
| **Total Profit**      | Sum of Profit             | 📈         |  
| **Total Quantity**    | Sum of Quantity           | 📦         |  
| **Number of Orders**  | Count of Order IDs        | 🛒         |  
| **Profitability**     | Sum of Profit Margin (%)  | 💹         |  
| **Average Discount**  | Average of Discounts      | 🔍         |  

---

## **Implementation Steps**  

### **Step 1: Data Preparation**  
- Import and clean the datasets (Orders, People, Returns).  
- Handle missing values and ensure correct data types.  

### **Step 2: Data Integration**  
- Merge the Orders and Returns tables using `Order ID` for return analysis.  
- Link the People table to Orders based on `Region`.  

### **Step 3: Create KPIs**  
- Design a KPI table to dynamically calculate essential metrics like sales, profit, and more.  

### **Step 4: Build the Dashboard**  
- **KPI Display**: Highlight total sales, profits, and other metrics.  
- **Interactive Filters**: Add slicers for category, region, and segment.  
- **Visualizations**:  
  - Bar charts for category performance.  
  - Line graphs for yearly trends.  
  - Top & bottom subcategories with comparative metrics.  

### **Step 5: Insights Generation**  
- Use the dashboard to identify trends and answer key business questions.  

---

## **Next Steps**  

To enhance the dashboard, future developments will focus on:  
- **Return Analysis**: Understanding return rates and their impact on profitability.  
- **Customer Insights**: Identifying the most and least profitable customers.  
- **Market Analysis**: Analyzing performance across various markets.  
- **Product Performance**: Diving deeper into product-specific metrics.  

---

## **Conclusion**  

The Dynamic Retail Dashboard offers a powerful solution for analyzing retail performance. By leveraging KPIs and interactive visualizations, it empowers users to make data-driven decisions and optimize business strategies. As enhancements are implemented, this tool will continue to deliver deeper insights and value for retail management.  

![image](https://github.com/user-attachments/assets/3d1de9b8-1d3c-45a2-8c56-8171080e70e5)





