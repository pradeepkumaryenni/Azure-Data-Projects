# IMDB Data Engineering – Azure Databricks

This module includes **Azure Databricks notebooks** designed to enrich and transform IMDB movie data, supporting downstream analytics and historical tracking.

## 🔧 Key Features

- PySpark-based transformations for cleaning and enriching raw data
- Enrichment of cast, crew, genres, runtime, and ratings
- Logic to assist **SCD Type-2 population** in SQL Warehouse
- Notebook-logged execution flow with auto-error tracking
- Partitioned outputs for efficient querying in Power BI
- CDC-prepared outputs based on pipeline timestamps

## 📂 Folder Structure

- `/ETL-Notebooks`: Step-wise enrichment and transformation logic
- `/Exploratory-Analysis`: Data profiling and validation
- `/Helpers`: Utility functions for logging, date parsing, etc.

## 🧱 Tech Stack

- Azure Databricks
- PySpark / Spark SQL
- Delta Lake
- Azure Blob → Synapse (SQL DW)

## 📊 Objective

To prepare a highly optimized and reliable data mart from raw IMDB metadata, supporting analytical queries and change tracking.

## 👤 Author

**Pradeep Kumar**  
📧 Email: Pradeepyenni.Global@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yenni-pradeep-kumar/)
