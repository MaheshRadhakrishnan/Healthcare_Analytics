# Healthcare_Analytics
End-to-end healthcare analytics project using Azure and Power BI
## Azure Data Factory Pipeline
This project uses Azure Data Factory to automate ingestion of healthcare data from cloud storage into Azure SQL.

### Architecture
Azure Blob Storage → Azure Data Factory → Azure SQL Database → Power BI

### ADF Implementation
- Created Linked Service to Azure Blob Storage
- Created Linked Service to Azure SQL Database
- Built Copy Data pipeline
- Configured column mapping CSV → SQL
- Executed and monitored pipeline runs

### Pipeline Screenshots
(see Screenshots folder)

### Business Use
This allows new healthcare data to be uploaded into Blob Storage and automatically loaded into SQL for reporting and analytics.
