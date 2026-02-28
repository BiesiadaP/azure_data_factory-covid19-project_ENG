## Azure Data Factory COVID-19 Project

### Overview
This project focuses on managing and processing COVID-19 data across Europe. It provides insights into the number of cases and deaths in various countries, utilizing Azure Data Factory’s capabilities for data integration and processing.

### European COVID-19 Data
The dataset comprises daily reported cases and deaths for various European countries. This data is sourced from reputable health organizations, ensuring accuracy and reliability.

### Tools Used
- **Azure Data Factory**: For data integration, orchestration, and ETL processes.
- **Azure DevOps**: To manage CI/CD pipelines across different environments (dev-test-prod).
- **Power BI**: For data visualization and reporting.

### Azure DevOps Environments
- **Development**: Initial coding and testing of data pipelines.
- **Testing**: Quality assurance tests to validate data transformations.
- **Production**: Live deployment of pipelines for real-time data processing.

### CI/CD Automation Process
This project employs a Continuous Integration/Continuous Deployment (CI/CD) approach:
1. **Build Pipeline**: Automates the build process to ensure code stability.
2. **Release Pipeline**: Deploys the code to various environments automatically upon successful builds and tests.

### Data Sources
Data is sourced from official government health websites and organizations such as WHO and ECDC, providing reliable statistics on COVID-19 cases and deaths.

### Processing Pipelines
The data processing involves:
- Ingesting raw data from various sources.
- Cleaning and transforming data using Azure Data Factory.
- Storing processed data in Azure SQL Database for reporting.

### Architecture
The project utilizes a modular architecture with distinct layers for data ingestion, processing, storage, and visualization.