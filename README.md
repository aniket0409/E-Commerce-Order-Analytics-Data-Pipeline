# 1. Project Overview
This project implements an end-to-end data engineering pipeline on Databricks Community Edition to process and transform transactional e-commerce data into an analytics-ready data model.

The pipeline ingests raw operational datasets related to customers, orders, purchased items, payments, and shipping details. Using PySpark on the Databricks platform, the data is cleaned, validated, transformed, and modeled into curated datasets optimized for analytics workloads.

The project demonstrates core data engineering skills including distributed data processing, ETL pipeline development, data modeling, and performance optimization within a cloud-based analytics environment.

# 2. Business Problem
Operational e-commerce systems typically store data in normalized transactional tables optimized for application operations rather than analytics.

Business teams require insights such as:

- Which product category generate the most revenue
- What payment methods are most commonly used
- Which geographic regions generate the highest order volumes

To answer these questions, raw operational data must be integrated and transformed into analytics-ready datasets. This project builds a scalable data pipeline to enable such analysis.

# 3. Technology Stack

- **Platform**:  Databricks Community Edition

- **Processing Engine**:  Apache Spark (PySpark)

- **Language**:  Python

- **Storage Format**:  CSV (raw layer) and Parquet structured outputs from Delta tables

- **Notebook Environment**:  Databricks Notebooks

- **Version Control**:  Github 


# 4. Data Sources

The project processes five primary datasets representing different entities in an e-commerce system:

- **customers.csv**  Customer demographic and registration information

- **orders.csv**  Order level transactional data

- **items.csv**   Product level details within each order

- **payments.csv**  Payment transaction information

- **shippings.csv**  Order shipping and logistics details


