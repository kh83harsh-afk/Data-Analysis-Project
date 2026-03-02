Project Overview

This project analyses an e-commerce dataset containing Customers details, Orders details, Return details, and Monthly Sales Targets. 

Through this project you will get an Insight regarding:
- Sales and Profit performance
- Customer behaviour (new vs repeat)
- Impact of returns on profitability
- Regional performance
- Target vs Actual achievement

The dashboard and reports are built using Power BI and focuses on delivering business insights for decision-making.
________________________________________
1. Business Problem

The business wants to understand:
- Which regions and categories drive the highest revenue?
- How returns impact overall profitability?
- Whether monthly sales targets are being achieved?
- What percentage of customers are repeat buyers?
________________________________________
2. Dataset Description

The project uses four tables:

1. Orders Table
   - Order ID
   - Customer ID
   - Sales
   - Quantity
   - Discount
   - Profit
   - Region
   - Date

2. Customers Table
   - Customer ID
   - Segment
   - Location

3. Returns Table
   - Order ID
   - Return Status (Yes/No)

4. Targets Table
   - Month
   - Monthly Sales Target
________________________________________
3. Data Modelling

- Created a Calendar table for time intelligence
- Built relationships:
  - Orders → Customers (Customer ID)
  - Orders → Returns (Order ID)
  - Calendar → Orders (Order Date)
  - Calendar → Targets (Month)
  ![image alt ](https://github.com/kh83harsh-afk/Data-Analysis-Project/blob/main/Data%20Modeling%20Screenshot.png?raw=true)
 
________________________________________
4.  KPIs Created
Key Metrics & DAX Measures

- Total Sales
- Total Profit
- Profit %
- Customer Repeat Rate
- Return Rate
- Target Achieved %
- Last Month Sales & Profit
-Sales & Profit % change from Last Month 
- Total Customer
- Average Order Value
- Net Sales & Profit After Returns
- Monthly Target Missed by %
- Repeat vs Unique Customers
________________________________________
5.  Dashboard
   - Sales vs Profit
   - Profit by Region
   - Profit  after return (Category-wise)
   - Months sale which are nearest to Target.
6. Reports Created

1. Sales Performance Report
   - Sales by Category
   - Sales by Region
   - Sales by Sub-Category
   - Profit Analysis

2. Customer Analysis
   - Unique vs Repeat Customers
   - Segment-wise Analysis
   - Monthly Orders and Profit
   - Category-wise Orders and Profits
3. Return Report
   - Return by Region
   - Return by Category
   - Return by Month 

4. Target vs Actual Performance
   - Monthly Sales vs Target

5. Location Analysis
   - Map Visualization
   - Sales by State and City
   - Profit by City 
________________________________________
7.  Skills Used

- Power BI
- DAX
- Data Modelling
- Business KPI Development
- Dashboard Design
________________________________________
8.  Screenshot
 
![image alt](https://github.com/kh83harsh-afk/Data-Analysis-Project/blob/a3ac0bb7091eb897142850e684d9bf4e721d4609/E-commerce_Performance_Dashboard.png)
