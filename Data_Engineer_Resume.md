# ASHOK — Data Engineer

---

## Professional Summary

Results-driven Data Engineer with extensive hands-on experience in designing, building, and maintaining scalable data pipelines and architectures on Microsoft Azure. Proficient in the full Azure data ecosystem, including ingestion, transformation, storage, analytics, and governance. Passionate about delivering high-quality, reliable data solutions that empower data-driven decision-making.

---

## Technical Skills

### Azure Data & Analytics Services

| Category | Technologies |
|---|---|
| **Data Integration & ETL/ELT** | Azure Data Factory (ADF), Azure Data Factory Mapping Data Flows, Azure Data Factory Data Flow Debugging, Azure Data Factory Managed Virtual Network, Azure Data Factory Integration Runtime (Self-Hosted & Azure IR) |
| **Big Data & Processing** | Azure Databricks (Apache Spark), Azure HDInsight (Hadoop, Spark, Hive, Kafka, HBase), Azure Synapse Analytics (Synapse Spark Pools, Synapse SQL Pools, Synapse Pipelines, Synapse Serverless SQL, Synapse Link), Azure Stream Analytics |
| **Data Storage** | Azure Data Lake Storage Gen2 (ADLS Gen2), Azure Blob Storage, Azure SQL Database, Azure SQL Managed Instance, Azure Cosmos DB, Azure Table Storage, Azure Files |
| **Data Warehousing** | Azure Synapse Analytics (Dedicated SQL Pool), Azure Synapse Serverless SQL Pool |
| **Messaging & Streaming** | Azure Event Hubs, Azure IoT Hub, Azure Service Bus, Apache Kafka on Azure HDInsight, Azure Event Grid |
| **Data Governance & Catalog** | Microsoft Purview (Azure Purview), Microsoft Purview Data Map, Microsoft Purview Data Catalog, Microsoft Purview Data Estate Insights, Microsoft Purview Data Lineage |
| **Machine Learning & AI** | Azure Machine Learning, Azure Cognitive Services, Azure OpenAI Service, Azure AI Search (formerly Cognitive Search) |
| **Business Intelligence** | Microsoft Power BI, Power BI Embedded, Power BI Dataflows, Power BI Premium |
| **DevOps & CI/CD** | Azure DevOps (Repos, Pipelines, Boards, Artifacts), GitHub Actions, Azure Resource Manager (ARM) Templates, Bicep, Terraform on Azure |
| **Identity & Security** | Azure Active Directory (Microsoft Entra ID), Azure Key Vault, Azure Managed Identities, Azure Private Link, Azure Virtual Network (VNet) Service Endpoints, Azure Role-Based Access Control (RBAC), Row-Level Security (RLS), Column-Level Security, Dynamic Data Masking |
| **Monitoring & Logging** | Azure Monitor, Azure Log Analytics, Azure Application Insights, Azure Alerts, Azure Diagnostics |
| **Networking** | Azure Virtual Network (VNet), Azure Private Endpoints, Azure VNet Peering, Azure ExpressRoute, Azure VPN Gateway |
| **Infrastructure & Compute** | Azure Virtual Machines, Azure Kubernetes Service (AKS), Azure Container Instances, Azure Functions, Azure Logic Apps, Azure App Service |

### Programming Languages & Frameworks

- **Languages:** Python, SQL, T-SQL, Scala, PySpark, SparkSQL, R, Java, Bash/Shell Scripting, PowerShell
- **Frameworks:** Apache Spark, Delta Lake, Apache Kafka, Apache Airflow, dbt (data build tool)
- **Data Formats:** Parquet, Avro, ORC, JSON, CSV, Delta

### Databases

- Azure SQL Database, Azure Cosmos DB, Azure Database for PostgreSQL, Azure Database for MySQL, SQL Server, Oracle, MongoDB

### Tools & Platforms

- Jupyter Notebooks, Azure Data Studio, SQL Server Management Studio (SSMS), Visual Studio Code, Git, Docker, Kubernetes

---

## Professional Experience

### Senior Data Engineer

**Company Name** | *Location* | *MM/YYYY – Present*

- Designed and implemented end-to-end data pipelines using **Azure Data Factory** with parameterized pipelines, linked services, and Mapping Data Flows to ingest data from 50+ heterogeneous sources (REST APIs, SFTP, on-premises SQL Server, Oracle, flat files) into **Azure Data Lake Storage Gen2**.
- Built advanced analytics and data transformation layers using **Azure Databricks** with PySpark and SparkSQL, processing 10+ TB of data daily in batch and near-real-time.
- Architected a modern **Lakehouse** solution on **Azure Synapse Analytics** using Synapse Spark Pools and Synapse Serverless SQL Pools with **Delta Lake** format, enabling ACID-compliant data storage and time-travel queries.
- Implemented real-time streaming pipelines using **Azure Event Hubs** and **Azure Stream Analytics** to process IoT telemetry and clickstream data with sub-second latency.
- Established data governance practices using **Microsoft Purview**, including automated data classification, lineage tracking, sensitivity labeling, and glossary management across the data estate.
- Secured data infrastructure with **Azure Key Vault** for secret management, **Azure Managed Identities** for service-to-service authentication, and **Azure Private Link / Private Endpoints** for secure network access.
- Created interactive dashboards and reports in **Microsoft Power BI** connected to Azure Synapse Analytics, implementing Row-Level Security (RLS) for multi-tenant data access control.
- Managed CI/CD pipelines using **Azure DevOps Pipelines** for automated deployment of ADF pipelines, Databricks notebooks, Synapse workspaces, and ARM/Bicep infrastructure templates.
- Set up comprehensive monitoring and alerting using **Azure Monitor**, **Log Analytics**, and **Application Insights** for pipeline health, resource utilization, and SLA tracking.
- Optimized Synapse Dedicated SQL Pool performance through distribution strategies (hash, round-robin, replicate), partitioning, materialized views, and result-set caching.

### Data Engineer

**Company Name** | *Location* | *MM/YYYY – MM/YYYY*

- Developed ETL workflows with **Azure Data Factory** to migrate on-premises data warehouse to **Azure Synapse Analytics**, reducing infrastructure costs by 40%.
- Built scalable data processing jobs on **Azure HDInsight** (Spark, Hive) for large-scale log analytics and historical data processing.
- Designed and implemented a **Cosmos DB**-based solution with Change Feed for event-driven microservices architecture, supporting global distribution and multi-region writes.
- Created data quality frameworks using **Azure Databricks** with Great Expectations and custom PySpark validation rules to ensure data integrity across bronze, silver, and gold layers.
- Automated infrastructure provisioning using **Terraform** and **ARM templates** for Azure resources (Storage Accounts, Data Factory, Synapse, Databricks workspaces).
- Implemented **Azure Event Grid** and **Azure Functions** for event-driven pipeline triggering and lightweight serverless data processing.
- Collaborated with data science teams to deploy ML models on **Azure Machine Learning** and integrate model scoring into production pipelines.
- Used **Azure Logic Apps** for orchestrating cross-system workflows including email notifications, Teams alerts, and ServiceNow ticket creation on pipeline failures.

### Junior Data Engineer

**Company Name** | *Location* | *MM/YYYY – MM/YYYY*

- Wrote complex **T-SQL** stored procedures, views, and functions in **Azure SQL Database** for data transformations and business reporting.
- Assisted in building data ingestion pipelines using **Azure Data Factory** with Copy Activity and parameterized datasets.
- Created and maintained **Power BI** reports and dashboards for business stakeholders, utilizing DirectQuery and Import modes.
- Performed data analysis and profiling using **Python** (pandas, NumPy) and **SQL** to identify data quality issues and trends.
- Managed database security using **Azure AD authentication**, RBAC, and Dynamic Data Masking in Azure SQL Database.
- Supported migration of SSIS packages to **Azure Data Factory** using the SSIS Integration Runtime.

---

## Azure Certifications

- **Microsoft Certified: Azure Data Engineer Associate (DP-203)**
- **Microsoft Certified: Azure Fundamentals (AZ-900)**
- **Microsoft Certified: Azure Data Fundamentals (DP-900)**
- **Microsoft Certified: Azure Solutions Architect Expert (AZ-305)**
- **Microsoft Certified: Azure Administrator Associate (AZ-104)**
- **Databricks Certified Associate Developer for Apache Spark**

---

## Education

**Bachelor of Technology (B.Tech) in Computer Science & Engineering**
*University Name* | *Year of Graduation*

---

## Key Projects

### Enterprise Data Lakehouse on Azure

- Built a multi-layer (Bronze/Silver/Gold) Lakehouse architecture using **ADLS Gen2**, **Azure Databricks**, **Delta Lake**, and **Azure Synapse Analytics**.
- Automated data ingestion from 100+ sources using **Azure Data Factory** with metadata-driven framework.
- Implemented data lineage and cataloging using **Microsoft Purview** across the entire data estate.

### Real-Time Analytics Platform

- Designed a real-time data streaming platform using **Azure Event Hubs**, **Azure Stream Analytics**, and **Azure Cosmos DB** for processing 1M+ events per second.
- Built real-time dashboards in **Power BI** with DirectQuery to Cosmos DB and Synapse Serverless.

### Cloud Data Warehouse Migration

- Led migration of on-premises SQL Server Data Warehouse to **Azure Synapse Analytics Dedicated SQL Pool**.
- Used **Azure Database Migration Service** and **ADF** for data migration with zero downtime.
- Implemented **PolyBase** and **COPY INTO** for high-performance data loading.

---

## Additional Azure Technologies & Concepts

- **Azure Data Explorer (ADX / Kusto)** for log and telemetry analytics
- **Azure Analysis Services** for enterprise-grade semantic modeling
- **Azure Cache for Redis** for high-performance caching layers
- **Azure API Management** for API gateway and management
- **Azure Notification Hubs** for push notifications
- **Azure Batch** for large-scale parallel and HPC workloads
- **Azure Data Share** for secure B2B data sharing
- **Azure Arc** for hybrid and multi-cloud data services
- **Azure Migrate** for cloud migration assessment and execution
- **Azure Cost Management** for cloud spend optimization
- **Azure Policy** for governance and compliance enforcement
- **Azure Blueprints** for environment standardization
- **Microsoft Fabric** for unified analytics platform (OneLake, Data Warehouse, Lakehouse, Data Engineering, Data Science, Real-Time Analytics)

---

*References available upon request.*
