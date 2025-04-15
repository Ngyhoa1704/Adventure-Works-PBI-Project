# 🚴‍♂️ AdventureWorks Power BI Sales Analytics Dashboard

## 📌 Project Overview
This Power BI project analyzes three years of sales, product, and customer data from the fictional AdventureWorks bike company. The goal is to gain actionable insights into revenue trends, top products, customer segments, and regional performance, as well as evaluate return behavior and the impact of price adjustments.

## 📁 Dataset Overview
The report is built from 10 CSV files containing transactional and lookup data, including:

| Dataset Name                        | Description |
|------------------------------------|-------------|
| `Sales Data 2020–2022`             | Sales transactions over 3 years |
| `Returns Data`                     | Returned product records |
| `Product Lookup`                   | Product attributes (name, price, model) |
| `Product Categories/Subcategories` | Hierarchy of product types |
| `Customer Lookup`                  | Customer demographics and segmentation |
| `Territory Lookup`                 | Region, country, continent |
| `Calendar Lookup`                  | Date dimension table |
| `Price Adjustment %`              | Parameter table for dynamic price simulation |
| `Metric Selection Tables`          | Parameter tables for slicers (metrics, product/customer fields) |

## 🎯 Project Objectives
- Track revenue and profit performance from 2020 to 2022
- Analyze return behavior and identify most returned products
- Evaluate top-performing products and customers
- Segment customers by income and occupation
- Visualize global sales distribution by region
- Simulate profitability based on pricing changes

## 📊 Dashboard Walkthrough
The report is structured into multiple pages with slicers and interactions:

### 1. **Executive Summary**
- KPIs: Total Revenue ($24.9M), Profit ($10.5M), Orders (25.2K), Return % (2.2%)
- Revenue trend line from Jan 2020 to Jul 2022
- Top 10 selling products with revenue and return rate
- Category-level breakdown (Accessories, Bikes, Clothing)
- Monthly revenue/orders/returns trend

### 2. **Regional Sales Map**
- Bubble map by continent, country, and region
- Segments: North America, Europe, Pacific
- Shows geographic concentration of orders

### 3. **Product Profitability Simulator**
- Select a product (e.g., Mountain Tire Tube)
- Adjust price to simulate change in adjusted profit
- KPIs vs targets (Orders, Revenue, Profit)
- Trendline: Total vs Adjusted Profit

### 4. **Customer Analytics**
- Total unique customers (17,416), Avg. Revenue per Customer ($1,431)
- Orders by income level and occupation
- Top 100 customers table with revenue & orders
- Segmented analysis by income, occupation, and year

### 5. **Weekly Orders Overview**
- Mini-report showing order growth from 2020 to 2022
- Key KPIs at a glance (Revenue, Profit, Return Rate)

### 6. **Product Category Breakdown**
- Hierarchical visual (Category → Subcategory → Product)
- Order volume visualized across categories

### 7. **Performance Table (MoM, QTD, YTD)**
- Matrix view by subcategory with monthly comparisons
- Shows MoM change %, quarter-to-date, and year-to-date totals
- Measure selector (Orders, Revenue, Profit, etc.)

## 🛠️ Tools & Techniques Used
- **Power BI Desktop**: Data modeling, DAX, visuals
- **DAX**: KPI calculations, YTD, MoM %, parameterized metrics
- **Power Query**: Data cleaning and transformation
- **Bookmarks & Buttons**: For slicer control and page navigation
- **What-If Parameters**: Price simulation logic
- **Relationship Modeling**: Star schema with calendar and lookup tables

## 🔍 Key Insights
- Accessories and bikes dominate total orders.
- Top products include Water Bottle, Mountain Tire Tube, and Sport Helmets.
- Return rate remains low across top products (mostly under 3.5%).
- Customer segment "Professionals" contribute to high revenue per customer.
- US, UK, and Australia are the top-performing countries in revenue.

---

