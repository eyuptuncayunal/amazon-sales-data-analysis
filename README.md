# amazon-sales-data-analysis
End-to-end data analysis of Amazon e-commerce sales using PostgreSQL and Power BI to detect operational losses.

# E-Commerce Operational Profitability & Logistics Analysis 📊

## 🎯 Project Objective
This project analyzes a comprehensive e-commerce dataset to identify operational bottlenecks and profitability leaks. Instead of focusing solely on vanity metrics (like top-selling products), this analysis targets **logistical failures** and **unrealized B2B potential** to provide actionable business intelligence.

## 💡 Key Business Insights
* **Operational Loss Detected:** Identified a **6.92M Rupee** revenue leakage due to canceled orders, primarily clustered in the 'Set' and 'Kurta' clothing categories.
* **Sales Channel Imbalance:** Discovered that **99.28%** of the 50.32M total revenue is driven by B2C retail, highlighting a completely underutilized B2B market.
* **Executive Dashboard:** Built an interactive Power BI dashboard to help decision-makers instantly track revenue versus logistical losses.

## 🛠️ Tech Stack & Methodology
* **Data Cleaning (ETL):** Power Query (Resolved locale/formatting conflicts and handled null values).
* **Database Management:** PostgreSQL & DBeaver (Data modeling and running initial validation queries to detect specific warehouse losses).
* **Data Visualization:** Power BI (Designed a self-explanatory Executive Dashboard focusing on critical KPIs).

## 📂 Repository Contents
* `queries.sql`: Contains the SQL scripts used in PostgreSQL for data extraction and targeted loss calculation.
* `Executive_Dashboard.pdf`: The final Power BI dashboard exported for quick viewing.
