# tokyo-olympic-azure-data-engineering-project<img width="1321" height="458" alt="Screenshot 2026-04-04 113732" src="https://github.com/user-attachments/assets/4ba458c2-e67c-4d47-82b2-48414f7048a6" />


# 🏅 Tokyo Olympic Azure Data Engineering Project

[![Azure](https://img.shields.io/badge/Azure-Data%20Engineering-blue?logo=microsoftazure)]()
[![PySpark](https://img.shields.io/badge/PySpark-3.0-orange?logo=apachespark)]()
[![Azure Data Factory](https://img.shields.io/badge/Azure-Data%20Factory-blue)]()
[![Azure Data Lake](https://img.shields.io/badge/Azure-Data%20Lake%20Gen2-blue)]()
[![Azure Synapse](https://img.shields.io/badge/Azure-Synapse-purple)]()
[![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)]()
[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)]()

---

# 📌 Project Overview

This project demonstrates an **end-to-end Azure Data Engineering pipeline** using the **Tokyo Olympics dataset**. The pipeline ingests raw data into Azure Data Lake Storage, transforms it using Azure Databricks (PySpark), stores curated data, and enables analytical reporting through Azure Synapse Analytics and Power BI.

The project follows a modern **Medallion Architecture (Bronze → Silver → Gold)** to ensure scalable, maintainable, and analytics-ready data processing.

---

# 🎯 Business Objective

The objective of this project is to build a cloud-native data engineering pipeline capable of:

- Collecting Olympic datasets
- Performing scalable ETL transformations
- Cleaning and validating data
- Storing processed datasets
- Enabling SQL-based analytics
- Creating business intelligence dashboards

---

# 🏗️ Architecture

```
                 Tokyo Olympic Dataset
                         │
                         ▼
              Azure Data Factory (ADF)
                         │
                         ▼
          Azure Data Lake Storage Gen2
                 (Raw / Bronze Layer)
                         │
                         ▼
         Azure Databricks (PySpark ETL)
                         │
                         ▼
          Azure Data Lake (Silver Layer)
                         │
                         ▼
          Azure Synapse Analytics
                         │
                         ▼
                Power BI Dashboard
```

---

# ⚙️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Azure Data Factory | Data Ingestion |
| Azure Data Lake Storage Gen2 | Data Storage |
| Azure Databricks | Data Transformation |
| PySpark | ETL Processing |
| Azure Synapse Analytics | SQL Analytics |
| Power BI | Dashboard & Visualization |
| Python | Data Processing |

---

# 📂 Project Structure

```
tokyo-olympic-azure-data-engineering-project
│
├── data/
│   ├── raw/
│   ├── transformed/
│   └── curated/
│
├── notebooks/
│   ├── Data_Ingestion.ipynb
│   ├── Data_Transformation.ipynb
│   └── Data_Analysis.ipynb
│
├── datasets/
│   ├── athletes.csv
│   ├── coaches.csv
│   ├── entriesgender.csv
│   ├── medals.csv
│   └── teams.csv
│
├── images/
│   ├── architecture.png
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

# 📊 Dataset

The project uses publicly available **Tokyo Olympic 2021 datasets**, including:

- Athletes
- Coaches
- Teams
- Medals
- Gender Entries

---

# 🔄 ETL Workflow

### Step 1 — Data Ingestion

- Azure Data Factory copies source datasets into Azure Data Lake Storage (Raw Layer).

### Step 2 — Data Transformation

Azure Databricks performs:

- Missing value handling
- Data type conversion
- Duplicate removal
- Data validation
- Feature engineering
- Column renaming
- Data cleansing

using **PySpark**.

### Step 3 — Curated Data Storage

Processed datasets are stored in the curated layer for downstream analytics.

### Step 4 — SQL Analytics

Azure Synapse Analytics enables efficient SQL queries over curated datasets.

### Step 5 — Business Intelligence

Power BI connects to Azure Synapse to build interactive dashboards.

---

# 📈 Key Insights

Examples of analytical questions answered:

- Medal distribution by country
- Top-performing athletes
- Gender participation analysis
- Medal trends by sport
- Country-wise performance comparison
- Coach contribution analysis

---

# 📊 Sample Dashboard

> *(Insert Power BI Dashboard Screenshot Here)*

```
images/dashboard.png
```

---

# 🚀 Features

- End-to-End Azure Data Engineering Pipeline
- Cloud-Based ETL
- Azure Data Factory Integration
- Azure Databricks (PySpark)
- Azure Data Lake Storage Gen2
- Azure Synapse Analytics
- Power BI Reporting
- Scalable Architecture
- Modular Data Pipeline

---

# 💡 Skills Demonstrated

- Azure Cloud
- Data Engineering
- ETL Pipelines
- PySpark
- SQL
- Azure Data Factory
- Azure Data Lake
- Azure Synapse
- Power BI
- Data Modeling

---

# 📌 Future Enhancements

- Incremental Data Loading
- Delta Lake Integration
- Azure Key Vault
- Parameterized ADF Pipelines
- CI/CD using Azure DevOps
- Pipeline Monitoring
- Logging & Alerting
- Data Quality Checks
- Unit Testing

---

# 📸 Project Screenshots

### Architecture

```
images/architecture.png
```

### Power BI Dashboard

```
images/dashboard.png
```

---

# ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/tokyo-olympic-azure-data-engineering-project.git
```

2. Upload datasets to Azure Data Lake Storage.

3. Execute Azure Data Factory pipeline.

4. Run Azure Databricks notebooks.

5. Query processed data in Azure Synapse.

6. Connect Power BI to Azure Synapse.

---

# 📚 Learning Outcomes

This project demonstrates:

- Designing scalable ETL pipelines
- Cloud-native data engineering
- Distributed data processing with PySpark
- Data warehousing in Azure
- Business Intelligence reporting
- End-to-end Azure ecosystem integration

---

# 👨‍💻 Author

**Siddharth Jaiswal**

Electrical Engineering Undergraduate | NIT Raipur

- 💼 Aspiring Data Engineer & Data Analyst
- 📧 Email: your-email@example.com
- 🔗 LinkedIn: https://linkedin.com/in/your-profile
- 💻 GitHub: https://github.com/SiddharthJaiswa110

---

# ⭐ If you found this project useful

Please consider giving this repository a ⭐ to support the project!
