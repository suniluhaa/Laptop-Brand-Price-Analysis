# Laptop-Brand-Price-Analysis

📊 Product Brand Analysis Using Databricks

📌 Project Overview

This project focuses on analyzing product data using Databricks and SQL to gain insights into product pricing, brand performance, and product distribution. The dataset contains product details such as brand, device, model, country of origin, release date, and price.

🛠️ Tools & Technologies

- Databricks
- SQL
- Data Analytics
- Data Visualization
- CSV Dataset

📂 Dataset Details

The dataset includes the following columns:

- "brand"
- "device"
- "model"
- "country_of_origin"
- "release_date"
- "price_usd"

🔍 Project Workflow

1. Imported the CSV dataset into Databricks.
2. Explored and analyzed the dataset.
3. Performed SQL queries to extract meaningful insights.
4. Grouped products by brand.
5. Calculated total products for each brand.
6. Analyzed average, minimum, and maximum product prices.
7. Sorted and compared brands based on product pricing.
8. Used Databricks Visual Data Preparation to explore and prepare data.

📈 Key Analysis

- Brand-wise product count
- Average product price by brand
- Minimum product price by brand
- Maximum product price by brand
- Comparison of pricing across brands
- Product distribution and pricing trends

💻 SQL Analysis

SELECT
    brand,
    COUNT(*) AS total_products,
    AVG(price_usd) AS avg_price,
    MIN(price_usd) AS minimum_price,
    MAX(price_usd) AS maximum_price
FROM workspace.default.gold_brand_analysis
GROUP BY brand
ORDER BY avg_price DESC;

🎯 Project Objective

The objective of this project is to understand product pricing patterns, compare different brands, and develop practical data analytics skills using Databricks and SQL.

🚀 Skills Gained

- Data exploration
- SQL querying
- Data aggregation
- Data analysis
- Working with Databricks
- Data preparation
- Extracting business insights
