# Data Engineering Project: Building an ELT Pipeline for Inventory Optimization on eCommerce Data

This project showcases a modern ELT (Extract, Load, Transform) pipeline using Apache Airflow and dbt to support inventory optimization use cases on sample eCommerce data. The data source is "theLook eCommerce" provided in the Google BigQuery public datasets.
The pipeline consists of the following steps:
- **Extract** raw data from BigQuery and store it as CSV/Parquet to an S3 bucket on AWS
- **Load** the data files from S3 into Redshift
- **Transform** the data in Redshift using dbt