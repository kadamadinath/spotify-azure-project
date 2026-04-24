# 🎧 Spotify Azure Data Engineering Project

Building a scalable, incremental data pipeline on Azure using ADF, Databricks, and Medallion Architecture.

Welcome to spotify_azure_data_engineering_project. This project demonstrates the design and implementation of an end-to-end data engineering pipeline using Azure services. It focuses on incremental data ingestion, dynamic pipeline design, streaming-based processing, and dimensional data modeling for analytics.

## 🔍 Specifications

-**Data Source:** Azure SQL Database (Spotify-like structured data)
-**Data Ingestion:** Build dynamic pipelines in Azure Data Factory (ADF) to ingest multiple tables
-**Incremental Load:** Implement watermark-based incremental loading
-**Backdate Support:** Enable reprocessing of historical data using parameterized backdate logic
-**Data Storage:** Load raw data into ADLS Gen2 (Bronze layer)
-**Data Processing:** Use Databricks Autoloader with Spark Streaming for incremental processing
-**Data Transformation:** Clean and transform data in Silver layer
-**Data Modeling:** Design Gold layer using Fact and Dimension tables
-**Data Governance:** Use Unity Catalog for secure data access and metadata management
-**Monitoring:** Send pipeline status notifications using Logic Apps (email alerts)

## 👨‍💻 About Me

Hi there, I'm Adinath Kadam.
I'm an IT professional and a passionate Data Engineer, focused on building scalable, efficient, and production-ready data platforms that drive analytics and decision-making.
