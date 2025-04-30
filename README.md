# azure-superstore-etl
ETL project using Azure Databricks, Data Factory, and Data Lake Gen2 with Global Superstore dataset
# Azure Global Superstore Project

## Overview
This project demonstrates an end-to-end **Data Engineering pipeline** using Azure Databricks, Azure Data Factory (ADF), and Azure Data Lake Storage (ADLS). The goal is to process the **Global Superstore** dataset by performing transformations using Databricks and orchestrating the entire workflow with ADF.

## Architecture

- **Azure Data Lake Storage (ADLS)**: Data storage for raw and curated datasets.
- **Azure Databricks**: Notebook for transforming raw data.
- **Azure Data Factory**: Orchestrates the ETL pipeline and runs Databricks notebook.

## Dataset

The **Global Superstore** dataset used in this project is available in the `data/` folder as `sample_Global_Superstore.csv`.

## How to Run

1. Clone the repository.
2. Set up your **Azure Databricks** workspace and **Azure Data Factory**.
3. Import and run the **Databricks notebook** for data transformation.
4. Orchestrate the pipeline using **Azure Data Factory**.
