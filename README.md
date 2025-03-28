# Automated ETL Pipeline with Apache Airflow on AWS EC2

## Overview
This project demonstrates a Python-based ETL pipeline using Apache Airflow on an AWS EC2 instance. The pipeline extracts Philadelphia weather data using Open Weather API, transforms it using pandas, and loads transformed data into Amazon S3 buckets. Upon arrival in S3, AWS Crawlers is triggered to load the transformed data into a data warehouse table using AWS Glue. Finally, AWS Athena is utilized to query and derive insights from the data. Apache Airflow orchestrates and automates this entire process.

![architech](https://github.com/user-attachments/assets/524156d9-71ff-423e-a6f2-6a909752b670)

## Steps
### 1. Connect to Open Weather API to extract raw data
### 2. Transform data using pandas
### 3. Upload Data into Amazon S3
### 4. Orchestrate Pipeline with Apache Airflow
- Install and set up Apache Airflow on an AWS EC2 instance to schedule and manage the ETL tasks, ensuring seamless data flow through the pipeline.
![Airflow DAG](https://github.com/user-attachments/assets/74a166ce-56b1-46a4-9bef-7fed3c3a1081)

### 5. Connect AWS Glue with IAM Role for data catalog and database
### 6. Use AWS Athena to query the data

_Inspired by the video tutorial: "How to Build and Automate a Python ETL Pipeline with Apache Airflow on AWS EC2" by tuplespectra._
