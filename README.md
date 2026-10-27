# Azure-Repo
A place to put all of my azure projects.

# Azure Data Fundamentals (DP-900) Project

## Overview

This project was completed as part of the **Microsoft Azure Data Fundamentals (DP-900)** training course during a **Data Technician Bootcamp**. The project provided hands-on experience with cloud computing concepts, Azure data services, and modern data analytics platforms. It covered relational and non-relational data storage, real-time data ingestion, analytical workloads, and practical data querying across multiple Azure technologies. The project focused on understanding how organizations can collect, store, process, and analyse data in the Microsoft Azure ecosystem. 【1-834fe0】

## Key Skills Demonstrated

### Cloud Computing Fundamentals
- Understanding core cloud concepts and service models:
  - Infrastructure as a Service (IaaS)
  - Platform as a Service (PaaS)
  - Software as a Service (SaaS)
- Comparing public, private, hybrid, and community cloud deployments
- Understanding scalability, availability, security, and cost optimisation within cloud environments
- Exploring Azure pricing, resource provisioning, and cloud architecture design principles 【1-834fe0】

### Relational Data with Azure SQL Database
- Working with structured relational datasets using **Azure SQL Database**
- Designing and querying relational data models
- Understanding tables, relationships, primary keys, and foreign keys
- Performing data analysis with SQL queries to support reporting and business insights
- Exploring cloud-hosted database solutions for transactional workloads through Azure SQL Database labs 【1-834fe0】

### Non-Relational Data with Azure Storage & Cosmos DB
- Exploring non-relational data storage using:
  - **Azure Storage Accounts**
  - **Azure Blob Storage**
  - **Azure Cosmos DB**
- Understanding JSON document storage and flexible schemas
- Comparing relational and NoSQL database technologies
- Selecting appropriate storage solutions based on workload requirements
- Working with scalable cloud-based storage for semi-structured and unstructured data 【1-834fe0】

### Analytical Workloads with Microsoft Fabric
- Exploring modern analytics workloads with **Microsoft Fabric**
- Working with **Lakehouse architecture** for unified data storage and analytics
- Understanding data engineering, data warehousing, and business intelligence concepts
- Using Fabric to support reporting and large-scale analytics workloads
- Exploring real-time analytics capabilities and Power BI integration within Microsoft Fabric 【1-834fe0】

### Data Ingestion & Integration
- Understanding multiple methods for data ingestion into Azure analytics platforms
- Working with:
  - Event-driven data ingestion
  - Microsoft Fabric Eventstreams
  - Batch data imports
  - Cloud storage ingestion pipelines
- Learning how real-time and historical datasets can be collected and processed for analytics and reporting
- Understanding data movement and integration across Azure services and analytical platforms

## SQL Skills Applied

Throughout the project, SQL was used to retrieve, filter, aggregate, and analyse business data.

### Querying & Filtering Data
- `SELECT`
- `WHERE`
- `ORDER BY`
- `DISTINCT`
- `BETWEEN`
- `LIKE`

### Data Aggregation & Analysis
- `GROUP BY`
- `COUNT()`
- `SUM()`
- `AVG()`
- Business KPI calculations

### Working with Relationships
- `INNER JOIN`
- Multi-table analysis across related datasets
- Combining customer, product, sales, supplier, and transaction data

### Example SQL Queries

``` sql
SELECT CategoryName,
       COUNT(ProductID) AS ProductCount
FROM Categories
JOIN Products
    ON Categories.CategoryID = Products.CategoryID
GROUP BY CategoryName;
```

``` sql
SELECT Customers.CustomerName,
       Orders.OrderDate
FROM Customers
JOIN Orders
    ON Customers.CustomerID = Orders.CustomerID;
```

### Data Analytics & Business Insights

The project focused on analysing datasets such as retail, product, customer, and sales information to answer real-world business questions, including:

Identifying top-selling products
Monitoring sales performance trends
Analysing customer purchasing behaviour
Comparing product categories and suppliers
Evaluating inventory and stock performance
Supporting data-driven business decision making

By combining SQL analysis with cloud-based storage and analytics services, raw business data was transformed into meaningful insights that could support operational and strategic decisions.

## Azure Services Explored
### Data Storage
- Azure SQL Database
- Azure Storage Account
- Azure Blob Storage
- Azure Cosmos DB
### Analytics & Reporting
- Microsoft Fabric
- Fabric Lakehouse
- Power BI
- Real-Time Analytics
### Data Integration
- Eventstreams
- Data ingestion pipelines
- Cloud-based data movement and transformation services
### Additional Azure Concepts
- Resource Groups
- Virtual Machines
- Cloud Security
- Cost Management
- Scalability & High Availability
## Tools & Technologies
- Microsoft Azure
- Azure SQL Database
- Azure Storage Account
- Azure Cosmos DB
- Microsoft Fabric
- Fabric Lakehouse
- Eventstreams
- SQL
- Power BI
- Cloud Data Platforms
## Learning Outcomes

Through this project, I developed practical experience in:

- Understanding cloud computing fundamentals and Azure services
- Working with both relational and non-relational data stores
- Building foundational knowledge of Microsoft Fabric analytics workloads
- Ingesting and processing data using cloud-native technologies
- Writing SQL queries to analyse business datasets
- Applying database concepts across multiple Azure platforms
- Supporting data-driven decision making using modern cloud analytics solutions
##Project Outcome

This project demonstrates a foundational understanding of Microsoft Azure's data ecosystem, including cloud computing concepts, Azure SQL Database, Azure Storage, Azure Cosmos DB, Microsoft Fabric Lakehouse, and real-time analytics. By combining data ingestion, storage, querying, and analytics techniques, the project showcases how Azure services can be used together to collect, manage, and transform retail and sales data into actionable business insights.
