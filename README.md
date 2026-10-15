# Instacart Retail Analytics Platform

End-to-end retail analytics project built with **AWS, Python, SQL, Amazon Athena, and Tableau**. The project processes more than **32 million retail transaction records** and combines data engineering with business analytics using a Medallion Architecture.

## Project Overview

The goal of this project is to build a scalable cloud analytics workflow that transforms raw retail data into analytics-ready datasets and business dashboards.

The pipeline ingests raw Instacart CSV files, cleans and transforms them with Python, stores optimized Parquet datasets in Amazon S3, catalogs the data with AWS Glue, queries curated datasets with Amazon Athena, and visualizes business KPIs in Tableau.

## Architecture

```text
Raw CSV Data
     |
     v
Python ETL / Data Profiling
     |
     v
Amazon S3
Bronze -> Silver -> Gold
     |
     v
AWS Glue Data Catalog
     |
     v
Amazon Athena
     |
     v
Tableau Executive Dashboard