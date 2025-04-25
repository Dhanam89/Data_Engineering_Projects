# 🚀 Cloud Data Engineering & Data Science Projects

A collection of seven hands-on projects that showcase end-to-end data engineering and machine learning workflows — using cloud services, Python, and modern data tools.

Each project demonstrates skills in data ingestion, transformation, modeling, orchestration, and cloud deployment.

---

## 🧰 Tech Stack

- **Languages & Libraries:** Python, pandas, scikit-learn, PySpark, Streamlit, Airflow
- **Cloud Platforms:** AWS, GCP (EC2, S3, Lambda, BigQuery, Cloud Functions, etc.)
- **Tools & Frameworks:** Apache Airflow, Kafka, Spark, Great Expectations, SageMaker
- **DevOps:** Docker, Git, CI/CD (GitHub Actions), SSH, REST APIs

---

## 📦 Projects Overview

| # | Project | Description | Cloud Services |
|---|---------|-------------|----------------|
| 1 | **ETL Pipeline with Airflow** | Batch ETL pipeline extracting public data, transforming with pandas, and loading into BigQuery or Redshift | GCP Composer / AWS MWAA |
| 2 | **Real-Time Streaming Pipeline** | Real-time data ingestion using Kafka and Spark Streaming, storing results in AWS S3 | AWS MSK, Spark EMR |
| 3 | **Delta Lakehouse with ML** | Bronze-Silver-Gold architecture using Delta Lake on Databricks, ends with an ML model | Databricks (AWS/Azure) |
| 4 | **Serverless ML Pipeline** | End-to-end model training & inference using AWS Lambda, S3, Step Functions, SageMaker | AWS |
| 5 | **Data Quality Checks with Alerts** | Automated data validation using Great Expectations with alerting on failure | GCP / AWS + Slack/Email |
| 6 | **ML Monitoring System** | Monitor input drift and accuracy of a deployed model with Grafana and Prometheus | Self-hosted / EC2 |
| 7 | **Airbnb Price Predictor Web App** | ML model deployed as a Streamlit web app with real-time predictions | AWS EC2 or GCP Compute |

---

## 📁 Directory Structure

cloud-data-projects/ │ ├── 01_airflow_etl_pipeline/ ├── 02_realtime_kafka_spark/ ├── 03_delta_lakehouse_ml/ ├── 04_serverless_ml_pipeline/ ├── 05_data_quality_checks/ ├── 06_ml_monitoring_grafana/ ├── 07_airbnb_price_predictor/ │ ├── shared_utils/ # Common helper modules ├── LICENSE └── README.md #
