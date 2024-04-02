# Analytics on Natural Disasters and Global Temperature
## Introduction
This repository contains data analysis and insights derived from two datasets obtained from Kaggle Datasets. One dataset focuses on US Disasters, while the other captures climate change data, specifically temperature variations. The project aims to analyze the relationship between natural disasters and global temperature changes.

## Dataset Sources
US Disasters Dataset: 

Climate Change (Temperature Change) Dataset: 
## Project Workflow
Data Collection: Obtained datasets from Kaggle for US Disasters and climate change (temperature change).

Data Cleaning: Utilized Python for data cleaning operations, removing anomalies, and performing normalization.

Data Storage: Created bucket storage in Google Cloud Platform (GCP) and loaded normalized data into the bucket.

Data Transformation: Divided the data into tables using Python for further normalization.

Data Pipeline: Utilized Apache Airflow for data orchestration and transfer to Staging.

ETL Operations: Implemented ETL (Extract, Transform, Load) operations using Airflow DAG (Directed Acyclic Graph).

Data Analysis: Loaded tables into Google BigQuery for performing complex queries and analysis.

Insights Visualization: Utilized Tableau for visualizing and deriving meaningful insights from the analyzed dataset.

## Tools Used
Python: Data cleaning, normalization, and data transformation.

Google Cloud Platform (GCP): Bucket storage for data storage and Google BigQuery for data analysis.

Apache Airflow: Data orchestration and ETL operations.

Tableau: Visualization of insights derived from the dataset.
