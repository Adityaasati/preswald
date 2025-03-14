# 📊 E-Commerce & Warehouse Overview Dashboard

## 🚀 Introduction

Welcome to the **E-Commerce & Warehouse Overview Dashboard**! This interactive dashboard helps you analyze sales, stock, and pricing data across various marketplaces, ensuring efficient inventory management and strategic decision-making.

This analysis uses the "E-Commerce Sales Dataset" dataset from Kaggle, available at: https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data

## 🔥 Key Features

- **Sales Analysis**: Gain insights into top-selling products and categories.
- **Stock Management**: Visualize stock availability across categories and sizes.
- **Pricing Insights**: Compare pricing strategies across different marketplaces.
- **Geographical Sales Trends**: Track revenue distribution across regions.
- **Order Status Overview**: Monitor completed, pending, and canceled orders.
- **Interactive Filters**: Filter data by state, category, or marketplace for a tailored view.

## 📁 Dataset Requirements

Ensure the following datasets are available in the `data/` directory:

1. `Amazon_Sale_Report.csv`
2. `Cloud_Warehouse_Compersion_Chart.csv`
3. `P_L_March_2021.csv`
4. `Sale_Report.csv`

These files should contain:

- **Amazon Sales Data**: Order details, amounts, shipping state, category, and SKU.
- **Warehouse Data**: Stock comparisons across different cloud platforms.
- **P&L Data**: Product pricing details across multiple marketplaces.
- **Sales Report Data**: Stock levels and inventory details.


## 📊 Data Cleaning & Processing

The dashboard ensures data accuracy through:

- **Date Formatting**: Converts dates into a consistent format.
- **Numeric Conversion**: Ensures numerical columns are correctly parsed.
- **Handling Missing Data**: Drops invalid entries while preserving essential information.
- **Column Renaming**: Standardizes column names for seamless integration.

## 📌 Interactive Visualizations

The dashboard provides:

- **🏆 Top Product Categories by Sales** *(Bar Chart)*
- **📦 Stock Levels per Category** *(Sunburst Chart)*
- **📅 Sales Trends Over Time** *(Line Chart)*
- **💰 Sales by State** *(Bar & Line Combo Chart)*
- **📊 Order Status Distribution** *(Horizontal Bar Chart)*
- **🛒 Price Comparisons Across Marketplaces** *(Box Plot)*
- **📏 Stock Distribution by Size** *(Funnel Chart)*
- **🏷️ Stock by Design Number** *(Treemap)*

## 🛠 Customization & Filters

The dashboard allows users to:

- **Select a Primary Dataset** (Amazon Sales, P&L, or Sales Report).
- **Filter by State and Category** for granular insights.
- **Analyze Orders by Status** to track fulfillment performance.

## 🚨 Error Handling

The script includes built-in error handling:

- Displays an alert if CSV files are missing.
- Handles incorrect data formats gracefully.
- Ensures missing values do not break the dashboard.



## 🙌 Acknowledgments

Special thanks to:

- **Pandas & Plotly** for data manipulation and visualization.
- **Preswald Team (pw)** for building a seamless platform that eliminates frontend concerns, allowing me to focus on insights.
- **Kaggle** for providing free datasets that power data-driven decisions.




