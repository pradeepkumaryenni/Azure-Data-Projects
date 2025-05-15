# IMDB Movie Data Pipeline – Azure Data Factory

This project showcases a high-end, production-grade **ETL pipeline** built with **Azure Data Factory (ADF)** to ingest, transform, and curate ~1GB of IMDB movie data for advanced analytics.

## 🔧 Key Features

- **CDC (Change Data Capture)** implementation to track and process only new or modified data.
- **SCD Type-2** handling for tracking historical changes in movie and cast metadata.
- **Multi-layered ETL design**: Raw → Filtered → Foundation → Enriched → Curated
- **Trigger monitoring and failure logging** with automated logs stored in **Azure SQL Warehouse**
- End-to-end **metadata-driven architecture**
- Dynamic pipeline parameterization and robust error handling
- Git-integrated ADF development for version control

## 📂 Folder Structure

- `/pipelines`: ADF pipeline JSONs (CDC, SCD, Main ETL)
- `/datasets`: Source and sink dataset definitions
- `/linkedServices`: Azure services connection configs
- `/logs`: Sample logs and monitoring queries
- `/diagrams`: Architecture and pipeline flow diagrams

## 🧱 Tech Stack

- Azure Data Factory
- Azure Blob Storage
- Azure SQL Data Warehouse (Synapse)
- Git Integration
- Azure Monitor (optional)

## 📊 Objective

To build a robust data pipeline capable of processing IMDB movie metadata with **historical tracking**, **audit logs**, and **CDC mechanisms** for scalable enterprise analytics.

## 👤 Author

**Pradeep Kumar**  
📧 Email: Pradeepyenni.Global@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yenni-pradeep-kumar/)
