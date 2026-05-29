
# Yoganand Kodali
#### Senior Data Engineer &nbsp;|&nbsp; Spark · PySpark · Databricks · Snowflake · dbt · Delta Lake · Airflow · Kafka · SQL · AWS · Azure · GCP

---

I build the data infrastructure that companies depend on — high-throughput pipelines, real-time streaming systems, and cloud-native platforms that process billions of records and power analytics, fraud detection, and machine learning at enterprise scale. 

Currently based in New Jersey and actively exploring Senior / Staff Data Engineer roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yoganand-kodali)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:yoganand.kodali@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-grey?style=flat-square&logo=githubpages&logoColor=white)](https://yoganand-kodali-1f0qyn6.gamma.site/)

---

## What I Have Built

At **PNC Bank**, architected GCP pipelines ingesting **2M+ daily banking transactions** across BigQuery, Dataflow, and Pub/Sub — reducing data latency by 35%, cutting infrastructure costs by 20%, and maintaining 99% SLA compliance across all enterprise datasets.

At **Ventiv Technologies**, designed an Azure data lakehouse (ADF + Databricks + ADLS Gen2) processing **1M+ insurance records monthly**, implemented Delta Lake with dbt Core modeling, and reduced report generation time by 50% through advanced SQL tuning.

At **OLA Electric**, built Airflow-orchestrated ETL pipelines handling **100K+ monthly orders**, reduced manual pipeline intervention by 60%, and maintained 99.9% data accuracy across operational dashboards.

---

## Impact

| | |
|---|---|
| Daily transactions processed | **2,000,000+** |
| Data latency reduction | **35%** |
| Infrastructure cost reduction | **20%** |
| Pipeline maintenance effort saved | **30%** |
| SLA compliance | **99%** |
| Manual intervention reduced | **60%** |
| Report generation time cut | **50%** |

---

## Projects

### [DE Job Pipeline](https://github.com/Yoganand-Kodali/DE-job-pipeline-custom)

A fully automated job intelligence pipeline built for a Senior Data Engineer job search. Scrapes LinkedIn, Indeed, and Dice daily, scores each posting against resume skills using a weighted tier system, filters by experience requirements and role relevance, and delivers a ranked interactive HTML dashboard to your inbox — automatically.

Built with multi-source scraping using `cloudscraper` to bypass bot detection, resume skill extraction via `pdfminer`, OPT/visa signal detection, salary parsing, remote/hybrid/onsite classification, and a dark-themed Chart.js dashboard with real-time filtering, sorting, and CSV export.

`Python` `BeautifulSoup4` `cloudscraper` `pandas` `pdfminer` `smtplib` `HTML/CSS/JS`

---

### [JobFlow — AI Job Search Dashboard](https://github.com/Yoganand-Kodali/jobflow-dashboard)

A self-contained local CRM for managing an active job search, powered by the Anthropic Claude API. Single HTML file with a Python persistence server — no backend, no cloud dependency, no framework.

Features a 9-step AI application agent: company research, fit analysis, contact finding, CV tailoring, cover letter generation, cold outreach, application Q&A, send sequence planning, and a full tailored resume rewritten as a 1-page PDF for each specific JD. Every output auto-saved per job. Kanban pipeline, analytics dashboard, and JSON/CSV export.

`Python` `Anthropic Claude API` `Vanilla JS` `HTML/CSS` `localStorage` `http.server`

---

### [Loan Defaulter Prediction](https://github.com/Yoganand-Kodali/loan-defaulter-prediction)

End-to-end machine learning pipeline on 307,511 loan applicant records (122 features). Covers the full data science workflow: exploratory analysis across all 122 features with statistical significance testing, KNN imputation on a dataset split into 6 batches for scalability, SMOTE for class imbalance, RFE for feature selection down to 30, and evaluation of 7 classification models.

Best result: Gradient Boosting — Train F1 **0.933**, Test F1 **0.932**. Selected over higher-scoring models that showed overfitting.

`Python` `Scikit-learn` `XGBoost` `imbalanced-learn` `Pandas` `Matplotlib` `Seaborn`

---

### [Earthquake Data Analysis](https://github.com/Yoganand-Kodali/earthquake-data-analysis)

Interactive CLI application analyzing 23,406 seismic events (1965–2016) alongside 44,554 global city records. Users filter by tremor type, date range, magnitude, latitude, and longitude. Implements the Haversine formula from scratch for geodesic distance calculations to find affected cities within a given radius. Generates 3 matplotlib visualizations: geographic scatter plot with magnitude color-mapping, events-per-year bar chart, and average magnitude trend.

`Python` `matplotlib` `csv` `datetime` `math` `Haversine formula`

---

### [Uno Card Game Simulator](https://github.com/Yoganand-Kodali/uno-card-game)

Functional Python implementation of a simplified Uno game — deck creation, round-robin dealing, match detection by color and number, draw/discard logic, and a full game loop. All functions include assertion-based tests that pass on run.

`Python` `Unit Testing` `Functional Programming`

---

## Tech Stack

**Languages** &nbsp; `Python` `SQL` `PySpark` `Spark SQL` `T-SQL` `Shell Scripting`\
**Data Engineering** &nbsp; `Apache Spark` `Apache Kafka` `Apache Airflow` `dbt Core` `Delta Lake` `Hadoop` `Hive`\
**Warehousing** &nbsp; `Snowflake` `BigQuery` `SQL Server` `MySQL` `Oracle` `MongoDB`\
**DevOps** &nbsp; `Docker` `Kubernetes` `CI/CD` `Azure DevOps` `Git` `Jenkins` `OpenShift`\
**BI & Analytics** &nbsp; `Power BI` `Tableau` `Pandas` `NumPy`\
**Cloud** &nbsp; `GCP — BigQuery · Dataflow · Pub/Sub · Cloud Composer` &nbsp; `Azure — ADF · Databricks · Synapse · ADLS Gen2` &nbsp; `AWS — S3 · Glue · Redshift · Lambda`\

---
