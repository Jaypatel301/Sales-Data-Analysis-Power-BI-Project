📊 Sales Data Analysis Dashboard — Power BI
📌 Project Overview
This project is an interactive Sales Data Analysis Dashboard built using Microsoft Power BI.
The project uses store sales data to analyze sales performance, profit, quantity sold, discounts, orders, products, customers, promotions, and cities.
The project was developed based on the provided project requirements and the supplied Store Data.xlsx dataset.
🎯 Project Requirements
The dashboard was designed to address the following business requirements:
1. Identify Top 5 and Bottom 5 products by:
   - Sales
   - Profit
   - Quantity Sold
2. Analyze sales trends over:
   - Daily
   - Monthly
   - Quarterly
   - Annually
3. Show the relationship between Sales and Profit.
4. Compare Sales, Profit, and Quantity Sold between any two periods selected by the user.
5. Analyze the average discount offered in each discount category.
6. Show the total number of orders.
7. Provide order-level details including:
   - Sales
   - Profit
   - Quantity Sold
   - Discount
   - Net Sales
   - Other relevant order fields
   with filtering options for:
   - Product
   - Date
   - Customer
   - Promotion Category
8. Analyze Sales by City.
📂 Dataset
The project uses the provided Store Data.xlsx file.
The workbook contains dimension and transaction data used to build the Power BI data model.
Dimension Tables
Dim Customers
Contains customer-related information such as:
- Customer ID
- Customer Name
- City
Dim Product
Contains product-related information such as:
- Product ID
- Product Name
- Product Line
Dim Promotion
Contains promotion-related information such as:
- Promotion ID
- Promotion Name
- Ad Type
Sales / Transaction Data
The transaction data contains fields including:
- Date
- Customer ID
- Promotion ID
- Product ID
- Units Sold
- Price Per Unit
- Total Sales
- Discount Percentage
- Discount Value
- Net Sales
🧹 Data Preparation & Transformation
The source data was prepared in Power BI before creating the dashboard.
The project separates the sales transaction data from supporting dimension tables such as Customers, Products, and Promotions.
The model also uses date tables for time-based analysis and comparison.

🏗️ Data Model
The Power BI project contains the following major tables/components:
                 Dim Customers
                       │
                       │
Dim Product ─── Sales / Fact Data ─── Dim Promotion
                       │
                       │
                 Date Tables
The model allows sales data to be analyzed from different business dimensions such as:
- Customer
- Product
- Promotion
- Date
- City
📊 Dashboard Pages
The Power BI report contains multiple report pages designed for different analysis requirements.
1️⃣ Overview
The Overview page provides a high-level view of the business performance.
Visuals included:
- Sales vs Profit relationship
- Discount analysis by Promotion Category
- Total Number of Orders
- Sales by City
- Sales Trends by Period
The sales trend supports time-based analysis using the date hierarchy.
2️⃣ Top / Bottom 5 Products
This page provides product performance analysis.
Top 5 Products
Products are analyzed by:
- Top 5 by Sales
- Top 5 by Profit
- Top 5 by Quantity Sold
Bottom 5 Products
Products are analyzed by:
- Bottom 5 by Sales
- Bottom 5 by Profit
- Bottom 5 by Quantity Sold
This page helps identify products with different levels of sales, profitability, and quantity performance.
3️⃣ Sales / Profit / Quantity Comparison
This page allows users to compare two selected periods.
The comparison includes:
- Total Sales
- Total Profit
- Total Quantity Sold
Two separate date-selection tables/slicers are used so that users can select two periods and compare their performance.
Example analysis
Selected Period 1
        VS
Selected Period 2

Sales
Profit
Quantity Sold
This makes the dashboard useful for period-over-period analysis.
4️⃣ Edit Interactions
This page contains the visual interaction configuration used for the report.
The interactions are related to:
- Total Sales
- Total Profit
- Total Quantity Sold
- Date selections
This supports interactive filtering between report visuals.
5️⃣ Order Details
The report also contains a detailed table for order-level analysis.
Fields included:
- Customer ID
- Order ID
- Product ID
- Promotion ID
- Date
- Discount Percentage
- Discount Value
- Net Sales
- Price Per Unit
- Profit
- Total Sales
- Units Sold
Available filters include:
- Date
- Product Name
- Promotion Name
- Customer Name
This allows users to drill into individual transaction/order records instead of only viewing aggregated KPIs.
🛠️ Tools & Technologies
- Microsoft Power BI
- Power Query / Data Preparation
- DAX
- Data Modeling
- Interactive Visualizations
- Date Hierarchies
- Slicers & Filters
- Visual Interactions
📈 Key Analysis Areas
The dashboard provides analysis across:
Sales
- Total Sales
- Sales trends
- Sales by product
- Sales by city
- Sales by promotion
- Sales by time period
Profit
- Total Profit
- Profit by product
- Sales vs Profit relationship
- Profit comparison between selected periods
Quantity
- Total Quantity Sold
- Top/Bottom products by quantity
- Quantity comparison between periods
Discount
- Discount percentage
- Discount value
- Average discount by promotion category
Orders
- Total number of orders
- Detailed order-level information
📁 Recommended GitHub Repository Structure
Sales-Data-Analysis-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── Sales Data Analysis power BI project.pbix
│
├── Dataset/
│   └── Store Data.xlsx
│
├── Screenshots/
│   ├── Overview.png
│   ├── Top-Bottom-5-Products.png
│   ├── Period-Comparison.png
│   ├── Edit-Interactions.png
│   └── Order-Details.png
│
└── Documentation/
    └── Power BI Project Requirements.pptx
🎯 Project Objective
The objective of this project is to transform store sales data into an interactive Power BI dashboard that enables users to analyze:
- Sales
- Profit
- Quantity Sold
- Discounts
- Orders
- Products
- Customers
- Promotions
- Cities
- Time-based performance
The dashboard combines high-level business KPIs with detailed transaction-level analysis and interactive filtering.
💡 Key Features
✅ Interactive Power BI dashboard
✅ Sales, Profit & Quantity analysis
✅ Top 5 / Bottom 5 product analysis
✅ Daily, Monthly, Quarterly & Annual trend analysis
✅ Sales vs Profit relationship
✅ Two-period comparison
✅ Discount category analysis
✅ Total order analysis
✅ City-wise sales analysis
✅ Order-level detailed table
✅ Product, Customer, Promotion and Date filters
✅ Interactive visual filtering  
📌 Project Files
Power BI Report
Sales Data Analysis power BI project.pbix
Dataset
Store Data.xlsx
Requirements
Power BI Project 1 Requirements.pptx
👤 Author
Jay Prakash Patel
