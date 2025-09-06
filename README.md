# Retail_sales_ADF_pipeline
Overview

This project implements a retail sales data pipeline using Azure Data Factory, Databricks and ADLS.

It ingests data from SQL databases and APIs, processes it through a Lakehouse architecture, and provides analytics via Power BI dashboards.

Architecture

Sources: SQL (Transaction, Store, Product), API (JSON)

ADF: Orchestrates data movement to ADLS

ADLS: Stores raw and intermediate data

Databricks:

Bronze: Raw data

Silver: Cleaned & joined data

Gold: Business-level analytics

Power BI: Visualizes data from Gold layer

Use Cases

Sales trends & performance

Product and store-level insights

Real-time reporting
