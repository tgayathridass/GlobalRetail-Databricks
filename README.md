# GlobalRetail-Databricks

Project Overview

This project implements a complete data pipeline using the Bronze → Silver → Gold lakehouse architecture on Databricks Free Edition, ending with Power BI dashboards.
The pipeline handles incremental ingestion, SCD Type 2 dimensions, data enrichment, and aggregation for analytics, using Delta Lake and PySpark.

This project provides a practical, hands-on approach to mastering Databricks for data engineering.

Tech Stack
Platform: Databricks Free Edition
Data Format: CSV (can support JSON/Parquet too)
Languages: PySpark, SQL
Storage: Delta Lake Tables (Bronze, Silver, Gold)
Visualization: Power BI Desktop

Data Flow
Raw files (CSV/JSON/Parquet) → Bronze Delta Tables → Silver Cleaned/SCD2 Tables → Gold Aggregated Tables → Power BI


Databases
bronze_db: Raw ingested Delta tables (products, customers, sales)
silver_db: Cleaned, enriched, SCD Type 2 tables
gold_db: Aggregated reporting tables (e.g., category_sales, total_sales)
