<div align="center">

<h1>Ahmed Refat</h1>
<h3> Data Engineer · Building Scalable Pipelines · Turning Raw Data into Insights</h3>

<p>
  <a href="https://www.linkedin.com/in/ahmedrefat1412/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:ahmedrefat1412@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://portfolio-indol-alpha-oqb5g4f1kz.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

</div>

---

## 👋 About Me

I'm an aspiring **Data Engineer** with hands-on experience designing and building **end-to-end data platforms** — from raw ingestion to production-ready analytics systems.

I work across the full data engineering stack:
- 🔄 **Batch & Real-Time Pipelines** using PySpark, Kafka, and Spark Structured Streaming
- ☁️ **Cloud Data Warehouses** on Snowflake, Amazon Redshift, and PostgreSQL
- 🏗️ **Medallion Architecture** (Bronze → Silver → Gold) with Star & Galaxy Schema modeling
- 📊 **BI Dashboards** with Power BI and real-time monitoring with Grafana
- ⚙️ **Orchestration** with Apache Airflow

---

## 🛠️ Tech Stack

### Languages & Processing
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

### Orchestration & Storage
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Redshift](https://img.shields.io/badge/Amazon_Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)

### Databases & Visualization
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)

---

## 🚀 Featured Projects

### ✈️ 1. NYC Flight Delay Prediction & Analytics Platform
> End-to-end platform combining **batch + real-time** pipelines to predict and analyze flight delays using flight, weather, and airport data.

**Tech:** PySpark · Kafka · Spark Structured Streaming · XGBoost · Snowflake · TimescaleDB · Power BI · Grafana · Airflow

<p align="center">
  <img src="https://github.com/AhmedRefat1412/Flight-Airline-Analytics-Platform/blob/main/doc/Flight%20%26%20Airline%20Analytics%20Platform.png?raw=true" width="80%" />
</p>

| Layer | Stack |
|---|---|
| Batch Pipeline | Flights + Weather → AWS S3 (Bronze) → PySpark (Silver) → Snowflake → Power BI |
| Streaming Pipeline | OpenSky API → Kafka → Spark Streaming → XGBoost → TimescaleDB → Grafana |
| Schema | Galaxy Schema |
| Architecture | Medallion (Bronze / Silver / Gold) |

🔗 [View Project →](https://github.com/AhmedRefat1412/Flight-Airline-Analytics-Platform)

---

### 💰 2. End-to-End Financial Data Platform
> A production-grade cloud-native ELT platform for processing and analyzing financial data with automated transformations and data quality checks.

**Tech:** AWS Glue · PySpark · dbt · Amazon Redshift · Great Expectations · Airflow · Power BI

<p align="center">
  <img src="https://github.com/AhmedRefat1412/Financial_data_platform/blob/main/docs/Financial_data_paltform.drawio.png?raw=true" width="80%" />
</p>

| Layer | Stack |
|---|---|
| Ingestion | CSV / API → AWS S3 (Raw Layer) |
| Processing | AWS Glue / PySpark → S3 (Processed) |
| Transformation | dbt → Amazon Redshift |
| Quality | Great Expectations |
| Orchestration | Apache Airflow |

🔗 [View Project →](https://github.com/AhmedRefat1412/Financial_data_platform)

---

### 🚦 3. NYC Smart Traffic Data Pipeline
> A smart city simulation pipeline that ingests traffic, weather, and accident data to power both historical analytics and real-time dashboards.

**Tech:** MongoDB · PySpark · Kafka · Spark Streaming · Snowflake · TimescaleDB · Power BI · Grafana

<p align="center">
  <img src="https://github.com/AhmedRefat1412/NYC-Smart_Traffic_pipline/blob/main/docs/nyc%20_traffic.drawio.png?raw=true" width="80%" />
</p>

| Layer | Stack |
|---|---|
| Sources | MongoDB + CSV + Weather + Accidents |
| Batch | AWS S3 → PySpark → Snowflake → Power BI |
| Streaming | API → Kafka → Spark → TimescaleDB → Grafana |
| Schema | Star Schema |

🔗 [View Project →](https://github.com/AhmedRefat1412/NYC-Smart_Traffic_pipline)

---

### 🛒 4. E-Commerce Data Engineering Pipeline
> A fully orchestrated ETL pipeline transforming raw e-commerce data (MongoDB + CSV) into a structured Star Schema data warehouse with automated Airflow DAGs.

**Tech:** PySpark · Apache Airflow · PostgreSQL · Power BI · MongoDB

<p align="center">
  <img src="https://github.com/AhmedRefat1412/ecommerce-data-pipeline/blob/main/docs/E-commerce%20Data%20piplines.drawio.png?raw=true" width="80%" />
</p>

| Layer | Stack |
|---|---|
| Sources | MongoDB + CSV |
| Processing | PySpark Transformations |
| Warehouse | PostgreSQL (Star Schema) |
| Dashboard | Power BI |
| Orchestration | Airflow DAGs |

🔗 [View Project →](https://github.com/AhmedRefat1412/ecommerce-data-pipeline)

---

## 🎯 Currently Focusing On

- 🔥 Advanced PySpark & Distributed Processing patterns
- ⚡ Real-Time Streaming architectures (Kafka + Spark)
- ☁️ Cloud Data Engineering on AWS (Glue, Redshift, S3)
- 🧠 ML Integration into data pipelines

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AhmedRefat1412&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="160"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AhmedRefat1412&layout=compact&theme=github_dark&hide_border=true" height="160"/>

</div>

---

<div align="center">
  <i>"Build systems that scale, pipelines that never sleep, and dashboards that tell the story."</i>
</div>
