# Azure Data Migration Pipeline with Medallion Architecture

#### End-to-End Data Migration & Transformation Pipeline with Medallion Architecture using Azure Data Factory, ADLS, and Synapse

![cover](pics/fullPipe.png)

## 🚀 Project Overview
This project showcases a data migration and transformation pipeline integrated with **Medallion Architecture (Bronze → Silver → Gold)** built on the Azure Synapse, for scalable and structured data processing.
It demonstrates how data can be migrated from Azure SQL Database, stored in Azure Data Lake Storage (ADLS) with **sanity check** (count check), and then transformed into **Medallion Architecture** — ensuring data quality, validation, and parallel processing.

## 🏗️ Architecture Overview
1.🥉 Bronze Layer — Raw data migrated directly from source (Azure SQL Database).

2.🥈 Silver Layer — Data transformation and cleaning.

3.🥇 Gold Layer — Business-ready data containing fact, dimension, and aggregated tables.

