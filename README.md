# Retail Inventory Intelligence Dashboard | Power BI & Python

## 1. Project Overview

The Retail Inventory Intelligence Dashboard is a data analytics project focused on inventory and sales management for a women’s fashion and maternity retail business, Preethi Wear.

The project uses Python for data cleaning and Microsoft Power BI for data modeling, DAX calculations, and interactive visualization. It analyzes sales trends, stock movements, product performance, and location-wise inventory to identify overstocking, stockout risks, and replenishment opportunities.

**Project Domain:** Retail Analytics
**Business Function:** Inventory Management
**Tools:** Python, Pandas, NumPy, Microsoft Power BI, DAX
**Data Period:** September 2023 – September 2026

**Note:** The dataset is synthetically generated for this project and does not represent verified company operational records.

## 2. Business Questions

This project addresses the following nine business questions:

1. Which products are fast-moving and slow-moving?
2. Which product categories and subcategories generate the highest and lowest sales?
3. Which locations have the highest and lowest sales?
4. Which products are overstocked?
5. Which products have high demand but low stock?
6. What are the historical sales trends and seasonal patterns?
7. Which locations experience overstock and stockout issues?
8. How much inventory value is tied up in each category and location?
9. How much stock is received, transferred, sold, returned, or damaged over time?

These questions help stakeholders improve inventory planning, optimize stock allocation, and make data-driven business decisions.

## 3. Tools Used

- **Python:** Data cleaning, preprocessing, calculations, and validation.
- **Pandas:** Data manipulation, missing-value checks, duplicate removal, and data transformation.
- **NumPy:** Stock issue identification and conditional calculations.
- **Microsoft Power BI Desktop:** Dashboard creation and interactive data visualization.
- **DAX:** Measures, calculated columns, date table creation, sales analysis, inventory valuation, and replenishment prioritization.
- **Data Modeling:** Star schema connecting the fact table with product, location, and date dimensions.
- **CSV:** Storage and transfer of raw and cleaned datasets.

## 4. Workflow

### Step 1: Business Understanding

Identified retail inventory challenges, including overstocking, stockouts, inefficient stock allocation, and limited visibility into sales and stock movements.

### Step 2: Dataset Preparation

Created three datasets representing inventory transactions, product details, and inventory locations.

### Step 3: Data Cleaning Using Python

- Standardized column names and text values.
- Checked missing values, duplicates, and data types.
- Converted date and numeric columns into appropriate formats.
- Validated product and inventory IDs.
- Calculated closing stock using inventory movement data.
- Identified negative stock records.
- Exported cleaned datasets to CSV files.

### Step 4: Data Modeling in Power BI

Designed a star schema with one fact table and three dimensions: Product Details, Inventory Locations, and Date.

### Step 5: DAX Calculations

Created measures to calculate total sales, units sold, current stock, inventory value, stock movements, damage rate, return rate, and replenishment priorities.

### Step 6: Dashboard Development

Built a five-page interactive dashboard with synchronized slicers for Year, Channel, City, and Category.

### Step 7: Insights and Recommendations

Analyzed product performance, inventory risks, location-wise sales, seasonal trends, and stock movement to develop actionable business recommendations.

## 5. Key Findings

The following findings are based on the project's synthetic dataset for the analyzed period.

- **Total Sales:** Approximately ₹2.03 crore.
- **Units Sold:** 18,974 units.
- **Current Stock:** 327,915 units.
- **Inventory Value:** Approximately ₹21.54 crore.
- **Product Catalogue:** 85 products across two categories.
- **Location Coverage:** 12 locations across Chennai, Coimbatore, and Madurai.
- **Category Performance:** Maternity Clothing contributed approximately 62% of total sales and inventory value.
- **Top-Selling Subcategory:** Kurtis generated approximately ₹70 lakh in sales.
- **Inventory Risk:** 681 overstock records compared with 27 stockout records.
- **Stock Movement:** 87,270 units were received, compared with 18,974 units sold.
- **Seasonality:** Sales showed recurring peaks around November to January.
- **Data Quality:** 26 records had negative closing stock, requiring further investigation.

### Business Recommendations

- Prioritize replenishment for high-demand products with relatively low stock.
- Reduce or pause purchasing for overstocked products.
- Use historical sales trends to plan seasonal inventory.
- Rebalance inventory across locations based on demand.
- Investigate negative stock records and improve stock update accuracy.
- Review slow-moving products and consider targeted promotions.

## 6. Project Files (GitHub Files)

The repository can be organized as follows. Include only the files that you have actually uploaded.

```text
retail-inventory-intelligence-dashboard/
│
├── README.md
├── data/
│   ├── Inventory_Transactions_Cleaned.csv
│   ├── Product_Details_Cleaned.csv
│   └── Inventory_Locations_Cleaned.csv
│
├── python/
│   └── Retailinventorycleaningscript.py
│
├── powerbi/
│   └── Retail_Inventory_Intelligence_Dashboard.pbix
│
└── Dashboard IMG/
    ├── inventory_overview.png
    ├── product_sales_analysis.png
    ├── location_performance.png
    ├── stock_movement_risk.png
    └── inventory_risk.png
```

**File descriptions:**

- `README.md` – Project overview, workflow, findings, and instructions.
- `Inventory_Transactions_Cleaned.csv` – Inventory movements, sales, and stock balances.
- `Product_Details_Cleaned.csv` – Product attributes and category information.
- `Inventory_Locations_Cleaned.csv` – Inventory locations, cities, and sales channels.
- `data_cleaning.py` – Python script used for data cleaning and validation.
- `Retail_Inventory_Intelligence_Dashboard.pbix` – Power BI report containing the data model, DAX measures, and dashboard pages.
- `screenshots/` – Dashboard screenshots for quick preview.


## 8. Author

**Ishwarya RB**
Aspiring Data Analyst | Technical Recruiter transitioning into Data Analytics

**Skills:** Python | SQL | Excel | Power BI | Tableau | Data Cleaning | Data Visualization | Business Intelligence


This project demonstrates practical skills in data preparation, data modeling, dashboard development, analytical problem-solving, and translating business questions into actionable insights.
