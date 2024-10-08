# Daily Job Market Sentiment Analysis Pipeline
A end-to-end data pipeline for analyzing job market sentiment using Microsoft Fabric, Azure Data Factory, and Power BI.

## Project Flow
<a href="flow_diagram.jpg" target="_blank">
  <img src="flow_diagram.jpg" alt="Flow Diagram" width="60% align="center">
</a>

## Dashboards
<p float="left">
  <img src="page1.jpg" width="49%" />
  <img src="page2.jpg" width="49%" />
</p>

# Flow
This pipeline performs the following tasks:
1. Ingests job listings from Bing API using Azure Data Factory
2. Processes raw JSON data into structured Delta tables using Synapse
3. Conducts sentiment analysis on job listings using a pre-trained ML model
4. Visualizes results in Power BI dashboards
5. Orchestrates daily pipeline runs and implements alert systems

## Key Features

- Data ingestion from Bing API
- Data processing and transformation using Synapse
- Sentiment analysis using pre-trained ML models
- Real-time visualization with Power BI
- Automated pipeline orchestration
- Alert system integration with Microsoft Teams

## Technologies Used

- Microsoft Fabric
- Azure Data Factory
- Azure Synapse Analytics
- Power BI
- Data Activator
- Microsoft Teams (for alerts)

## Reference
Youtube: [Mr. K Talks Tech - End to End Azure Data Engineering Project ](https://youtube.com/playlist?list=PLrG_BXEk3kXyEV0dzmAN-49tLrQsM0jUa&si=nzYbyesTKRcCZhaX)
