# Azure End-to-End Data Engineering Project

## Overview
This project implements an end-to-end data engineering pipeline using Microsoft Azure to process car sales data. It uses incremental data ingestion, data transformation, and dimensional modeling to build analytics-ready datasets.

## Technologies Used
- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2 (ADLS Gen2)
- Azure Databricks
- PySpark and SQL
- Delta Lake
- Unity Catalog
- GitHub

## Architecture
The project follows the **Medallion Architecture** with three layers:

- **Bronze:** Ingest raw data into Azure Data Lake Storage using Azure Data Factory.
- **Silver:** Clean, transform, and prepare data using PySpark in Azure Databricks.
- **Gold:** Build fact and dimension tables for analytical reporting.

## Key Features
- Incremental data ingestion using watermark-based processing.
- Data cleansing and transformation using PySpark.
- Delta Lake MERGE operations for incremental inserts and updates.
- Surrogate key generation for dimension tables.
- Fact and dimension modeling for analytical workloads.
- Data organization and governance using Unity Catalog.
- Pipeline orchestration using Azure Data Factory and Databricks.

## Key Learnings
Gained hands-on experience in building scalable ETL pipelines, implementing incremental data processing, applying Medallion Architecture, and developing dimensional models using Azure data engineering services.

## Author
**Sai Charan**