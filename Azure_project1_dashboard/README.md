# 📌 Sales Data Modernization Pipeline using ADF & Azure Synapse

A cloud-based end-to-end ETL/ELT pipeline built using Azure Data Factory, Azure Data Lake, Azure Databricks, Azure SQL, Azure Synapse, and Power BI to automate sales data ingestion, transformation, and analytics.

## 🚀 Project Overview

This project modernizes sales analytics by building a scalable Bronze–Silver–Gold data lake architecture and enabling automated reporting through Power BI.
It demonstrates real-world data engineering practices: ingestion, transformation, orchestration, optimization, and reporting.

## 🧱 Architecture
Source Files  
    ↓  
Azure Data Factory (ADF)  
    ↓  
Bronze Layer – Raw Data (ADLS Gen2)  
    ↓  
Databricks PySpark Transformations  
    ↓  
Silver Layer – Cleaned Data (ADLS)  
    ↓  
Business Aggregations / Metrics  
    ↓  
Gold Layer – Curated Data (ADLS)  
    ↓  
Azure SQL / Azure Synapse  
    ↓  
Power BI Dashboard  

## 📊 Interactive Project Flow

Ingest Sales Data → Load raw files into Bronze Layer using ADF

Transform with PySpark → Clean, validate, and normalize data in Databricks

Store Clean Output → Write transformed data to Silver Layer

Business-Level Aggregation → Create KPIs and metrics in Gold Layer

Load to Azure SQL & Synapse → Create tables and views

Build Dashboards → Visualize sales performance in Power BI

Schedule & Monitor → Use ADF triggers, logs, and pipeline monitoring

Publish Insights → Export reports or integrate with business apps

## 🛠️ Tech Stack

Azure Data Factory (ADF) – Orchestration & ETL

Azure Data Lake Storage Gen2 – Storage (Bronze/Silver/Gold)

Azure Databricks (PySpark) – Data transformation

Azure SQL Database – Curated data storage

Azure Synapse Analytics – Analytical queries & reporting layer

Power BI – Data visualization

PySpark, SQL, ADF Pipelines – Code & logic

