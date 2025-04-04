# Azure Synapse Analytics Workspace

This project focuses on provisioning and configuring an Azure Synapse Analytics workspace to support a lake database environment. The objective was to create a robust analytics platform integrated with a data lake, utilizing various Azure tools and services. Below is a summary of the key activities completed during the project.

## Project Overview

### Provisioning the Workspace
- Deployed an Azure Synapse Analytics workspace using a PowerShell script and an ARM template.
- Configured the workspace to connect seamlessly with an Azure Data Lake Storage Gen2 account, relying on the built-in serverless SQL pool for querying, with an optional Apache Spark pool for advanced data processing.

### Storage Configuration
- Explored the resource group created during deployment and adjusted the data lake storage account settings.
- Enhanced security by updating container permissions, switching from access keys to an Azure Entra user account authentication method.

### Creating a Lake Database
- Designed a lake database within Synapse Studio, defining its structure and linking it to a designated folder in the data lake.
- Configured the database to work with delimited text data for flexibility in handling various file formats.

### Building Tables
- Created a custom table from scratch and populated it with data uploaded from a CSV file.
- Utilized a prebuilt template to generate another table, customizing it to fit specific needs and loading it with data from a CSV file.
- Derived a third table from existing data in the data lake, establishing relationships between tables to ensure data integrity.

### Working with Data
- Queried the lake database using SQL scripts in Synapse Studio, joining multiple tables to extract valuable insights.
- Employed a Spark notebook to insert new data into the database and validated the operation with a subsequent query.

## What I Learned

This project provided practical insights into:
- **Azure Synapse Analytics**: Setting up and managing a workspace, integrating it with a data lake, and leveraging serverless SQL and Spark capabilities.
- **Lake Database Management**: Designing and configuring a lake database, handling data ingestion, and maintaining relationships across datasets.
- **Data Lake Operations**: Managing storage permissions and uploading data to a data lake for analytical use.
- **Analytical Tools**: Using SQL for querying and Spark for data manipulation within a unified platform.
- **Automation**: Deploying infrastructure with PowerShell and ARM templates, and navigating Synapse Studio for efficient workflows.

This experience strengthened my skills in cloud-based data engineering and highlighted the power of combining traditional analytics with modern data lake architectures.

**Connect with me**: [https://www.linkedin.com/in/eyilan/]
