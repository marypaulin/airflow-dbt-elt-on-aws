# GCP Data Engineering Project: Building an ELT Pipeline for Inventory Optimization on eCommerce Data

This project showcases a modern ELT (Extract, Load, Transform) pipeline using Google Cloud Storage, BigQuery, Apache Airflow, and dbt to support inventory optimization use cases on sample eCommerce data. The data source is "theLook eCommerce" provided in the BigQuery public datasets.
The pipeline consists of the following steps:
- **Extract** raw data from BigQuery and store it in Google Cloud Storage.
- **Load** the data files from Google Cloud Storage into BigQuery.
- **Transform** the data in BigQuery using dbt.

Note: Although the first two steps may appear redundant, they are intentionally included to simulate the extract and load phases using Airflow.