# Retail Sales Data Analysis with Python

Introduction

This project explores a retail sales dataset using Python to uncover key customer and product insights.  
Through exploratory data analysis (EDA), we investigate patterns in sales across product categories, time trends, customer demographics, and purchase behavior.

The goal is to extract actionable insights for data-driven decisions — from category performance to consumer behavior trends.

The analysis includes:
- Data cleaning and preparation
- Visualizations (bar charts, line plots, heatmaps)
- Correlation analysis
- Time-based sales trends
- Category breakdowns by gender

 Key Insights

1. Electronics Dominate Sales
   - Electronics is the top-selling product category, followed by Clothing and Beauty.
   - Revenue differences between categories are moderate, suggesting a balanced product portfolio.

2. Gender Doesn't Drive Product Preference
   - Sales are nearly evenly distributed between male and female customers across all categories.
   - No clear gender-based bias exists in product choice.

3. Time-Based Trends Matter
   - Electronics consistently leads in monthly sales, with noticeable spikes.
   - All categories follow similar seasonal trends — likely driven by promotions or holidays.

4. Price > Quantity
   - Strong correlation between `Price per Unit` and `Total Amount` (`0.85`) vs. weaker correlation with quantity (`0.37`).
   - Revenue is more affected by item price than how many items are bought.

5. Age is a Non-Factor
   - Age has minimal correlation with quantity, price sensitivity, or spend.
   - Indicates age-neutral purchase behavior.

6. Sales by Weekday & Month
   - Sales are fairly consistent across weekdays with minor variation.
   - Monthly trends reveal repeatable peaks — useful for forecasting.

# Project Structure
retail-sales-analysis/
├── retail_sales_eda.ipynb             # Full notebook with code & plots
├── visuals/                           # All saved chart PNGs
│   ├── sales_trend_over_time.png
│   ├── monthly_sales_by_category.png
│   ├── daily_total_sales.png
│   ├── correlation_matrix.png
│   ├── gender_sales_by_category.png
│   ├── gender_total_spend.png
│   ├── quantity_purchase_per_gender.png
│   ├── products_popular_to_gender.png
│   ├── product_category_vs_total_sales.png
│   └── total_monthly_sales.png
└── README.md

└── README.md

# How to Run

Clone this repository:
```bash
git clone https://github.com/yourusername/retail-sales-analysis.git
cd retail-sales-analysis


