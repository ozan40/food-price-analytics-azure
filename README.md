<img src="/files/tables/Azure_Architecture.jpg" alt="Azure Architecture" width="900"/>


# Cloud project using Azure, Azure Databricks & Power BI

This repository contains the full Azure-based project developed for comparing national food prices between Kazakhstan and Afghanistan.  
The solution integrates **Azure Data Factory**, **Databricks**, **Data Lake Gen2**, and **Power BI**.

## Repository Structure
- `/databricks_notebooks`: Spark-based ETL and enrichment notebooks
- `/powerbi`: PBIX dashboard
- `/docs`: SLA, and possible Pricing List

## Key Features
- Automated ingestion from WFP datasets
- Bronze/Silver/Gold architecture using Delta Lake Gen2
- Interactive dashboards in Power BI
- SLA definitions for availability and performance

## How to Reproduce
1. Deploy Azure services using templates in `/azure_pipelines`.
2. Import notebooks into Databricks from `/databricks_notebooks`.
3. Connect processed data to Power BI via Lakehouse.
