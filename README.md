# BlinkIT Grocery Sales Dashboard 📊

This interactive Power BI dashboard project showcases a comprehensive analysis of BlinkIT’s grocery sales data, highlighting customer behavior, product categories, sales performance, and delivery efficiency. The aim is to derive meaningful business insights and help decision-makers track KPIs effectively.

## 🔍 Project Overview

The dashboard was built using Power BI and supports interactive exploration of grocery retail data extracted from BlinkIT. It enables stakeholders to:
- Monitor category-wise and product-wise sales.
- Analyze delivery performance across cities.
- Understand customer purchase behavior.
- Track top-selling SKUs and underperforming areas.

## 🧾 Dataset Description

The primary dataset used in this project is:

📁 **BlinkIT Grocery Data.xlsx**
- Contains data related to product details, order volumes, delivery times, cities, quantities sold, and revenue metrics.

Columns in the dataset include:
- `Order ID`
- `Product Category`
- `Product Name`
- `City`
- `Delivery Time (in mins)`
- `Quantity`
- `Price`
- `Total Sales`
- `Order Date`

## 🧰 Tools and Technologies Used

- **Power BI**: For data visualization and dashboard creation.
- **Microsoft Excel**: As the source dataset.
- **DAX (Data Analysis Expressions)**: For calculated columns and KPIs.
- **Power Query Editor**: For data transformation and cleaning.

## 📌 Key Features in the Dashboard

- 🚚 **Delivery Time Analysis**: Average delivery time per city and product category.
- 🏙️ **City-wise Sales Comparison**: Identify cities with highest and lowest revenue.
- 📦 **Top-Selling Products**: Breakdown of best-performing SKUs.
- 🧾 **Revenue Insights**: Total revenue over time with filters on city and product type.
- ⏳ **Date Filters**: Dynamic filters to analyze performance over custom date ranges.
- 🔍 **Drill-down Capabilities**: Interactive visuals that allow deeper exploration into specific categories and products.

## 🧹 Data Cleaning Steps

- Removed null or missing values.
- Converted delivery time to numeric format.
- Normalized city names and product categories.
- Derived `Total Sales` using calculated columns:  
  `Total Sales = Quantity * Price`
- Extracted year and month from the `Order Date` column for time-series analysis.

## 📈 KPIs Tracked

- Total Revenue
- Average Delivery Time
- Total Orders
- Top 5 Product Categories by Sales
- City with Fastest Delivery
- Slowest Performing City

## 📂 Project Files

| File Name                   | Description                                     |
|----------------------------|-------------------------------------------------|
| `blinkit.pbix`             | Power BI dashboard file                         |
| `BlinkIT Grocery Data.xlsx`| Raw dataset used for visualization              |

## 🧠 Insights Derived

- Delivery time significantly affects customer satisfaction in metro cities.
- Packaged and daily essential categories generate the highest revenue.
- Tier-1 cities show faster delivery times compared to Tier-2 cities.
- Seasonal patterns affect the sales of certain product categories.

## 🚀 How to Use

1. Clone/download this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Refresh the data or load your own updated `BlinkIT Grocery Data.xlsx` to re-run the visuals.
4. Use filters and slicers to explore the data across cities, dates, categories, and more.

## 📌 Note

This dashboard is built for educational and demonstration purposes using mock/representative grocery data. It showcases how modern BI tools can be applied in the retail industry for operational and strategic decisions.

---

## 📬 Contact

For feedback or collaboration, feel free to reach out:

**Name**: Ahad Alyani  
**Email**: [your-email@example.com]  
**LinkedIn**: [linkedin.com/in/your-profile]  

---

## 📸 Screenshot

![Screenshot 2025-03-20 155449](https://github.com/user-attachments/assets/5f67d981-3fa5-4ca0-b30f-08ec12467901)

