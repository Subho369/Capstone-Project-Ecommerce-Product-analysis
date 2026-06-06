# Capstone-Project-Ecommerce-Product-analysis

📝 Project Introduction
This project focuses on data engineering and analysis of an ecommerce dataset using Databricks. The dataset contains detailed transactional and product attributes such as orders, customers, brands, categories, pricing, discounts, and ratings.

A. The workflow is designed around the medallion architecture:

* Bronze layer → raw ingestion of order and product data.
* Silver layer → cleaned and transformed tables (e.g., denormalised order items, product attributes).
* Gold layer → aggregated metrics for business analysis, such as Total Revenue, MoM Growth %, Active Customers, and Category‑wise Revenue.

B. On top of this, interactive dashboards were built to visualize:

* Revenue trends over time (monthly, weekly, cumulative).
* Brand and category performance with MoM growth.
* Product attribute analysis (quantity vs revenue, ratings vs revenue).
* Distribution charts (donut, scatter, stacked bar) to highlight drivers of revenue.

The goal of the project is to enable actionable insights for ecommerce decision‑making — identifying growth opportunities, tracking declining brands, and understanding how product attributes (category, brand, color, size, material) influence revenue.
