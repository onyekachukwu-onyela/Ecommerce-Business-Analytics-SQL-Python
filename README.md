# E-Commerce Product Performance Analytics (SQL + Python)

An end-to-end analytics project exploring revenue growth, customer behavior, and operational efficiency using SQL (DuckDB) and Python (Pandas/Seaborn).

## Executive Summary

This analysis reveals a rapidly scaling e-commerce platform with strong seasonal effects, clear product-category winners, and a measurable link between delivery performance and customer satisfaction.

## Key Business Insights

### Revenue Growth & Seasonality

* The platform experienced **rapid hyper-growth in 2017**, scaling from **$111.8K (Jan)** to **$987.8K (Nov)** — an **8.8x increase within 11 months**.
* A significant **November spike (~$987.8K, 7,289 orders)** aligns strongly with **Black Friday seasonal demand**, indicating heavy retail-driven seasonality rather than linear organic growth.
* In 2018, revenue stabilized within a **$830K–$970K monthly range**, suggesting maturation into a steady-state operation.

### Delivery Performance vs Customer Satisfaction

* Orders delivered in ~**10 days correlate with 5-star reviews**, establishing an operational benchmark for high satisfaction.
* Once delivery exceeds **~14 days**, ratings decline to ~3 stars.
* At **~21 days**, customer feedback deteriorates to **1-star reviews**, showing a strong negative nonlinear relationship between delay and satisfaction.
* Conclusion: **Logistics speed is a primary driver of customer experience quality**, not random dissatisfaction.

### Product Category Performance

* **Health & Beauty** and **Watches & Gifts** are the strongest revenue drivers, contributing **$2.3M+ combined revenue** with strong satisfaction (>4.0★).
* These categories show strong **product-market fit** and are ideal for expansion and marketing investment.
* **Bed, Bath & Table** presents a structural risk:
  * $1.02M revenue (3rd highest)
  * Highest order volume (9,177 orders)
  * Lowest satisfaction (3.92★)
* This suggests potential issues in **product quality, supplier consistency, or fulfillment speed**.

## Business Recommendations

* Improve logistics efficiency to maintain delivery times within ~10 days to sustain high customer satisfaction.
* Investigate quality and fulfillment issues in the Bed, Bath & Table category to reduce churn risk.
* Scale marketing investment in Health & Beauty and Watches & Gifts due to strong profitability and satisfaction alignment.

## Tools & Techniques

* SQL (DuckDB): multi-table joins, aggregation, and exploratory querying
* Python (Pandas, Seaborn): data cleaning, analysis, and visualization
* Business analytics: metric analysis, performance evaluation, and executive storytelling
