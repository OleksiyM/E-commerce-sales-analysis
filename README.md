- [E-commerce Sales Analysis](#e-commerce-sales-analysis)
  - [Project Overview](#project-overview)
  - [Project Objectives](#project-objectives)
  - [Dataset](#dataset)
  - [Key Findings](#key-findings)
  - [Key Recommendations](#key-recommendations)
  - [Project Structure](#project-structure)
  - [Tools and Libraries](#tools-and-libraries)
  - [How to Run](#how-to-run)
  - [Summary](#summary)
  - [Solution](#solution)
  - [Approach](#approach)
  - [License](#license)

# E-commerce Sales Analysis

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on a transactional dataset from a UK-based online retail store.  The analysis uncovers valuable insights into customer behavior, sales trends, product performance, and price sensitivity, leading to data-driven recommendations for improving business performance.  The project utilizes Python with libraries like Pandas, Matplotlib, and Seaborn.

## Project Objectives

*   Describe data to answer key questions and uncover insights.
*   Gain valuable insights to improve online retail performance.
*   Provide analytic insights and data-driven recommendations.

## Dataset

The dataset used is the "Online Retail" dataset, which contains transactional data from 2010 to 2011. It includes information such as:

*   `InvoiceNo`: Invoice number
*   `StockCode`: Product code
*   `Description`: Product description
*   `Quantity`: Quantity of the product
*   `InvoiceDate`: Transaction date and time
*   `UnitPrice`: Product price
*   `CustomerID`: Customer ID
*   `Country`: Customer country

The dataset can be found in UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/352/online+retail

## Key Findings

*   **Customer Segmentation (RFM):**  Identified four distinct customer segments (Top, High-Value, Mid-Value, Low-Value) based on Recency, Frequency, and Monetary value, with the Top segment showing significantly higher average spending.
*   **Seasonal Sales Trends:**  Strong seasonality, with sales peaking in Q4 (pre-holiday season) and a significant drop in Q1.  November is the highest sales month.
*   **Day-of-Week and Hourly Trends:**  Thursdays and Tuesdays see the highest sales, with a peak in sales around noon (12 PM).  Sunday sales are notably lower.
*   **Top Products:** Identified the top 10 best-selling products by quantity.
*   **Geographic Focus:**  The vast majority of sales originate from the United Kingdom.
*   **Product Associations:**  Discovered strong relationships between products frequently purchased together (e.g., color variations, themed items).
*   **Price Sensitivity:**  Demonstrated a strong inverse relationship between price and quantity sold, indicating high price elasticity.
*   **Extremely Short Purchase Cycle:**  The median time between customer purchases is only 1.1 days, highlighting high customer engagement and opportunities for real-time marketing.

## Key Recommendations

*   **Customer-Centric:** Implement a tiered loyalty program to retain high-value customers and incentivize others.
*   **Seasonal Planning:** Align inventory and marketing with the Q4 peak and develop promotions for Q1.
*   **Pricing Strategy:** Balance low-priced (high-volume) and high-priced (high-margin) items.
*   **Product Bundling:**  Offer bundled promotions based on frequently purchased product pairs.
*   **Real-Time Marketing:** Leverage the short purchase cycle with immediate follow-up marketing and limited-time offers.

## Project Structure

*   `Online Retail.xlsx`: The dataset.
*   `online_retail.ipynb`:  The Jupyter Notebook containing the complete analysis, code, visualizations, and findings.

## Tools and Libraries

*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   `itertools` (for combinations in market basket analysis)
*   `collections` (for `Counter` in market basket analysis)

## How to Run

1.  Clone the repository
2.  Install the required libraries
3.  Open and run the `online_retail.ipynb` notebook using Jupyter Notebook or JupyterLab.

## Summary

This project utilized EDA techniques, including data cleaning, visualization, RFM analysis, and market basket analysis, to provide actionable insights. The impact is improved targeting, optimized pricing, and increased sales.

## Solution

The solution achieved project objectives by identifying key customer segments, sales trends, and product affinities. This enables data-driven decisions for marketing, inventory, and pricing, fulfilling the EDA goals.

## Approach

1.  **Data Loading and Cleaning:** Loaded the data, handled missing values, removed duplicates, and validated data types.
2.  **Exploratory Analysis:** Calculated descriptive statistics and created visualizations (histograms, boxplots, bar plots, line plots).
3.  **Trend Analysis:** Analyzed sales trends over time (monthly, daily, hourly).
4.  **Top Performers:** Identified top-selling products and countries.
5.  **Advanced Analysis:** Performed RFM analysis for customer segmentation, market basket analysis for product associations, and price sensitivity analysis.
6. **Findings and report:** Made Findings and Conclusions report.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file included in this repository for details.
