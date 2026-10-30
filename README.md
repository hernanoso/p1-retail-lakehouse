# Retail Sales Lakehouse on Azure

End-to-end ELT pipeline on Azure built with public data: ingestion with Azure Data Factory, a Bronze / Silver / Gold medallion layout in Azure Data Lake Storage Gen2, data-quality checks, a star schema exposed through Azure Synapse serverless SQL, and secrets handled with Azure Key Vault and managed identities.

> Work in progress. Architecture, setup and results will be documented here as each step is completed.

## Stack

Azure Data Factory · Azure Data Lake Storage Gen2 · Azure Key Vault · Azure Synapse Analytics (serverless SQL) · Parquet · Python · SQL

## Data

Public data only (Fake Store API and a small CSV). No employer code or data.
