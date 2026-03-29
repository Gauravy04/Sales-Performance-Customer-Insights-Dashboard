Sales & Profit Analysis Dashboard (Excel, Power BI & Power Query)

## Project Overview

This project is a **Sales & Profit Analysis Dashboard** built using **Microsoft Excel, Power BI, and Power Query**.
The purpose of this project is to analyze sales performance, profit, customer behavior, discount impact, and shipping performance using interactive visualizations.

---

## Tools & Technologies Used

* **Microsoft Excel** – Data cleaning and preprocessing
* **Power Query** – Data transformation and data cleaning
* **Power BI** – Data modeling, visualization, and dashboard creation

---

## Data Cleaning (Excel & Power Query)

The following data cleaning steps were performed:

* Removed duplicate values
* Handled missing values
* Corrected data types (Date, Number, Text)
* Created new columns:

  * **Delivery Time** = Ship Date - Order Date
  * **Profit Ratio** = Profit / Sales
* Checked and filtered:

  * Ship Date < Order Date errors
  * Loss-making products (Profit < 0)
* Cleaned column names and formatted data

---

## Data Analysis & Dashboard Insights

The dashboard provides the following insights:

### Sales & Profit Analysis

* Total Sales, Profit, and Quantity
* Sales by Category
* Profit by Sub-Category
* Top 10 Products by Sales
* Sales & Profit by Region
* Sales by Segment
* Top Revenue Generating States

### Time Analysis

* Monthly Sales Trend
* Monthly Profit Trend
* Month with Highest Profit

### Profitability Analysis

* Profit Ratio by Category
* Loss-Making Products
* Discount vs Profit Relationship

### Shipping Analysis

* Shipping Mode Usage
* Average Delivery Time

### Customer Analysis

* Top Customers by Revenue

---

## Dashboard Pages

The Power BI dashboard contains **3 pages**:

1. **Executive Sales Overview** – KPI cards, Sales by Category, Sales by Segment, Sales by Region, Monthly Sales Trend
2. **Profit & Product Analysis** – Profit by Sub-Category, Top 10 Products, Profit Ratio, Loss-Making Products, Discount vs Profit
3. **Shipping & Customer Insights** – Shipping Mode, Average Delivery Time, Top Customers

---

## Key KPIs

* Total Sales
* Total Profit
* Total Quantity
* Profit Ratio
* Average Delivery Time

---

## How to Use the Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Use slicers to filter data by:

   * Region
   * Category
   * Segment
   * Ship Mode
   * Order Date
3. Navigate between pages for different insights.
4. Hover over visuals to see detailed information.

---

## Files Included in Repository

* `Orders.xlsx` → Raw and Cleaned Data
* `Sales.pbix` → Power BI Dashboard
* `README.md` → Project Documentation

---

## Conclusion

This project helps in understanding:

* Sales and profit performance
* Product performance
* Customer contribution to revenue
* Shipping performance
* Impact of discount on profit

This dashboard can help businesses make **data-driven decisions** to improve profitability and sales performance.

---

## Author

Gaurav Yadav
