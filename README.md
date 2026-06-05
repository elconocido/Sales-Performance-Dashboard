# Sales Performance Dashboard | Power BI Portfolio Project

## Project Overview
This project is a Sales Performance Dashboard built in Microsoft Power BI using a retail sales dataset.
The dashboard was designed to analyze revenue, profit, product performance, customer performance, and shipping performance across multiple years.

The project was developed to demonstrate skills in:
- Excel data preparation
- Power BI data modeling
- DAX measures
- Business insight generation

## Objectives
The main goal of this project was to:
- Analyze total revenue and total profit
- Track month-over-month and year-over-year growth
- Identify best-performing products and customers
- Evaluate shipping efficiency
- Present insights in a clean and interactive Power BI dashboard

## Dataset
The dataset used for this project was sourced from Kaggle: **Sales Order Dataset**.

The dataset includes:
- Order ID
- Customer Name
- Segement
- Product Name
- Order Date
- Ship Date
- Ship Mode
- City
- Country
- State
- Postal Code
- Region
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

## Tools Used
- Microsoft Excel
- Microsoft Power BI
- DAX

## Data Preparation Process

### 1. Excel Cleaning
The raw dataset was first reviewed in Excel to:
- check for missing values
- confirm data types
- remove any inconsistent entries
- ensure dates were properly formatted
- prepare the file for analysis

### 2. Power BI Data Modeling
The data was loaded into Power BI and transformed into a star-schema style model.

The model includes:
- a central fact table for sales
- dimension tables for product, customer, ship mode, shipping demograph and date.

Two separate date logic approaches were used:
- **Order Date** for sales performance analysis
- **Ship Date** for shipping performance analysis

### 3. Date Table
A proper date table was created to support:
- month-over-month analysis
- year-over-year analysis
- monthly trend visuals
- time intelligence measures

### 4. DAX Measures Created
Some of the key measures created include:
- Total Revenue
- Total Profit
- Total Quantity Sold
- MoM Revenue Growth %
- MoM Profit Growth %
- YoY Revenue Growth %
- YoY Profit Growth %
- Shipping Delay Days
- Average Shipping Delay
- Orders Shipped

## Dashboard Pages

### 1. Overview Insights
This page gives a high-level summary of overall business performance.

It includes:
- Total Revenue
- Total Profit
- Total Quantity Sold
- MoM Revenue Growth %
- MoM Profit Growth %
- YoY Revenue Growth %
- YoY Profit Growth %
- Revenue by Year-Month
- Profit by Year-Month
- Revenue and Profit by Quarter
- Revenue by Region

### 2. Product Insights
This page focuses on products and customers driving the business.

It includes:
- Top 10 Products by Revenue
- Top 10 Products by Profit
- Revenue and Profit by Category
- Revenue by Category
- Top 10 Customers by Revenue
- Top 10 Customers by Profit

### 3. Shipping Insights
This page focuses on shipping efficiency and delivery performance.

It includes:
- Orders Shipped
- Average Shipping Delay
- Shipping Count by Status
- Orders Shipped by Year-Month
- Average Shipping Delay Days by State
- Shipping Delay Days by Ship Mode

## Key Insights

### Overview Insights
- Total revenue reached **$1.22M** while total profit reached **$334.49K** across the reporting period.
- Revenue and profit generally increased together throughout the period.
- **Q4** generated the highest revenue and profit among all quarters.
- The **East** region generated the highest revenue, followed by the **West** region.
- Year-over-year revenue grew by **47.97%** and profit grew by **49.16%**.

### Product Insights
- **Office Supplies** generated the highest revenue while **Technology** generated the highest profit.
- A small group of products contributed a large share of total revenue and profit.
- Some products ranked highly in revenue but lower in profit contribution.
- The top customers generated a significant portion of total revenue and profit.
- Technology delivered the strongest profit relative to its revenue contribution.

### Shipping Insights
- Late shipments accounted for approximately two-thirds of all shipments.
- **Standard Class** accumulated the highest number of shipping delay days.
- Shipment volume increased significantly during peak months.
- Shipping delays varied substantially across states.
- Monthly shipment volumes fluctuated considerably throughout the reporting period.

## Business Value
This dashboard helps identify:
- growth patterns
- high-performing products
- valuable customers
- shipping inefficiencies
- regional performance differences

It can support better decisions around:
- product strategy
- customer retention
- logistics planning
- seasonal forecasting
- profitability improvement

## Dashboard Preview

### Overview Insights
<img width="1068" height="635" alt="Overview Insight" src="https://github.com/user-attachments/assets/cd52a637-5292-446a-8328-317c667249ab" />

### Product Insights
<img width="1077" height="636" alt="Product Insight" src="https://github.com/user-attachments/assets/a9d04ecb-e67c-411a-aed8-fba08773b37d" />

### Shipping Insights
<img width="1064" height="634" alt="Shipping Insight" src="https://github.com/user-attachments/assets/7c7a8943-d89b-47dd-b7fa-7d61b1b2ed3b" />

## How to Use
1. Download the `.pbix` file from the repository
2. Open it in Microsoft Power BI Desktop
3. Refresh the data if needed
4. Explore the report pages and interact with the visuals

## Future Improvements
Possible next steps for this project include:
- adding drill-through pages
- creating forecast visuals
- adding customer segmentation
- building a slicer for category and region comparison
- improving shipping delay analysis by state and ship mode
  
## Author
Victor Ayomide Adebiyi
Aspiring Data Analyst
