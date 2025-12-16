# ADF-CovidProject

## Overview
This project implements an **Azure Data Factory (ADF)–based data integration pipeline** to ingest, process, and transform COVID-related datasets. It follows a modular and event-driven design using ADF components such as pipelines, datasets, linked services, data flows, and triggers.

## Project Structure
ADF-CovidProject/
│
├── dataflow/ # Mapping Data Flows for transformations
├── dataset/ # Source and sink datasets
├── linkedService/ # Connections to databases and storage
├── pipeline/ # ADF pipelines for ingestion and processing
├── trigger/ # Event-based and schedule triggers
├── publish_config.json
└── README.md


## Key Features
- Automated ingestion of COVID datasets (cases, hospital admissions, population data)
- Data transformation using **ADF Mapping Data Flows**
- Event-based and scheduled triggers for pipeline execution
- Modular and production-style ADF repository structure
- Supports scalable and repeatable ETL workflows

## Technologies Used
- Azure Data Factory
- Azure SQL / Azure Storage
- Mapping Data Flows
- Event & Schedule Triggers

## Use Case
- Public health data ingestion and processing
- Daily hospital admission analytics
- COVID trend analysis and reporting pipelines

## How to Deploy
1. Import repository into Azure Data Factory
2. Configure linked services with valid credentials
3. Validate and publish ADF resources
4. Enable triggers to start automated execution

## Future Enhancements
- Add monitoring and alerting
- Integrate Power BI for visualization
- Implement data quality and validation checks
