Scalable Media Analytics Data Pipeline

This project showcases a production-style, end-to-end Azure Data Engineering pipeline built using a Netflix dataset. It demonstrates strong cloud data engineering fundamentals, including ingestion, transformation, orchestration, metadata management, and analytics-ready data delivery using modern Azure services.

- Overview

The pipeline implements the Medallion Architecture (Bronze → Silver → Gold) using Azure Databricks and Delta Lake. Data is ingested with Autoloader, transformed with PySpark, enriched through lookup tables, and finalized into Gold-level curated tables. Azure Data Factory orchestrates the workflow, while Delta Live Tables ensures quality and declarative transformations.

This project reflects industry-aligned patterns used in large-scale streaming and batch data platforms.

- Technologies Used

Azure Data Factory
Azure Databricks (PySpark, Autoloader, DLT)
Azure Data Lake Storage Gen2
Delta Lake
Databricks Workflows
Medallion Architecture

- Key Highlights

Incremental ingestion using Databricks Autoloader
End-to-end pipeline following Bronze, Silver, Gold layers
Data cleansing, validation, normalization, and lookup enrichment
Delta Live Tables for continuous, quality-checked transformations
Orchestrated execution with ADF pipelines and linked services
Modular Databricks notebooks for ingestion, transformation, and enrichment
Designed to support scalable, cloud-native data engineering workflows

📁 Repository Contents
dataset/                 
factory/                 
linkedService/           
pipeline/                
1_Autoloader.dbc         
2_silver.dbc             
4_silver.dbc             
5_lookupnotebook.dbc     
7_DLT_Notebook.dbc  
untitled notebook
publish_config.json      

⭐ Skills Demonstrated

Cloud data ingestion & orchestration
PySpark ETL development
Delta Lake & ACID data pipelines
Streaming and incremental load design
Lookup/dimension modeling
Declarative ETL with Delta Live Tables

Production-style pipeline architecture
