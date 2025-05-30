# Data Engineering Project: Building an ELT Pipeline for Inventory Optimization on eCommerce Data

<span style="color:purple"><em>👾 Under construction 👾</em></span>

This project showcases a modern ELT (Extract, Load, Transform) pipeline using Apache Airflow and dbt to support inventory optimization use cases on sample eCommerce data. The data source is "theLook eCommerce" provided in the Google BigQuery public datasets.
The pipeline consists of the following steps:
- **Extract** raw data from BigQuery and store it as Parquet to an S3 bucket on AWS
- **Load** the data files from S3 into Redshift
- **Transform** the data in Redshift using dbt

## Data

This project uses the synthetic **theLook eCommerce** dataset, publicly available in Google BigQuery. It includes sales, customer, and inventory data. Key tables are:

- `orders`: Sales transactions, including dates, order value, and profit
- `order_items`: Line items for each order, includes quantity and product linkage
- `products`: Product catalog with category, brand, and price info
- `users`: Customer demographic info (gender, age, location)
- `distribution_centers`: Info on where products are shipped from
- `inventory_items`: Inventory status per product per location


## Use Cases

This project is centered on inventory optimization to improve stock levels and reduce over- or under-stocking. Handled use cases include:

TBD

## Architecture

This project follows a modular ELT design with cloud-native tooling:

TBD

## Setup

To run this project:

TBD

## Testing

This project aims to incorporate multiple levels of testing to ensure data integrity and pipeline reliability:

- Data Quality Tests (dbt):
  - TBD
- Pipeline Functionality Tests (Airflow):
  - TBD
- Integration Tests (Optional):
  - TBD