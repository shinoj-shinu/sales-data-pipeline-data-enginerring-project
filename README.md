# sales-data-pipeline-data-enginerring-project
This project showcases an end-to-end sales data engineering pipeline built using Python (Flask) and Google Cloud Platform (GCP) services. The pipeline automates the ingestion, processing, and storage of sales data, while Looker Studio is used to create interactive dashboards and visualize key sales KPIs.
Features
1. Flask Web Portal

User-friendly interface to upload sales data (CSV/Excel).

Triggers backend processing and pipeline orchestration.

Simple dashboard to view upload history and pipeline status.

2. GCP Integration

Cloud Storage – Stores raw and processed files.

Cloud Functions / Cloud Run – Serverless transformation and validation.

Pub/Sub – Event-driven triggers for data workflow.

BigQuery – Central data warehouse for sales analytics.

Cloud Scheduler – Automates pipeline execution.

3. Automated ETL Pipeline

Cleans and validates raw sales data.

Applies transformations and enrichments.

Loads refined data into BigQuery fact and dimension tables.

Handles errors and maintains logs.

4. Looker Studio Dashboards

Visualizes key sales insights such as:

Total and daily sales

Revenue trends

Top-performing products

Region-wise performance

Monthly growth KPIs

# How It Works

User uploads sales file via Flask web portal.

File is stored in Cloud Storage (raw bucket).

Pub/Sub triggers ETL Cloud Function.

Data is validated, transformed, and sent to BigQuery.

Looker Studio fetches BigQuery data and updates dashboards automatically.

#Purpose of This Project

This project highlights real-world data engineering skills:

Building scalable data pipelines

Integrating cloud services

Orchestrating ETL workflows

Creating analytical dashboards

Deploying web apps for data operations
