# COVID19 Data Pipeline - Azure Data Engineering

## Project Requirement
Develop an end-to-end Data Pipeline on Azure Data Factory to create a datawarehouse of COVID19 daily and weekly data related to Testing, Cases, Deaths, Hospital Admissions etc.

## Tasks
- Create a Data Model based on Project Requirement & Available ECDC API endpoints
- Develop Data Pipeline in Azure Data Factory
  - Fetched data from ECDC API and Azure Blob Storage
  - Processed data by applying diverse transformations as per requirements using 
    - Dataflows
    - Pyspark in Azure Databricks
  - Created a Data Lake to store Raw, Processed and Lookup files in separate containers
  - Loaded data into Azure SQL Database
- Develop a Datawarehouse in Azure SQL DB

## Services Used
- Azure Data Factory (Dataflows, Linked Services, Triggers, Azure Databricks)
- Azure Blob Storage
- Azure Lake Storage Gen 2
- Azure Key-Vault
- Azure SQL DB

## Solution Architecture:

![Solution Architecture](./assets/images/COVID-19%20Data%20Pipeline%20Architecture.jpg)

## Future Work

- Load data from Azure SQL DB into Power BI Desktop
- Visualize COVID-19 trends to gain insights in Power BI
