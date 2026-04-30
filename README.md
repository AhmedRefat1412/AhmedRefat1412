# 👋 Hi, I'm Ahmed Refat

Aspiring Data Engineer building scalable batch & real-time data pipelines using PySpark, Kafka, and Airflow, transforming raw data into production-ready data warehouses and analytics systems.

I have hands-on experience designing end-to-end data solutions, starting from data ingestion from multiple sources (APIs, MongoDB, CSV), through processing with distributed systems, to building optimized data warehouses and delivering insights via BI tools.

My expertise includes:

* Building ETL/ELT pipelines using PySpark & Apache Airflow
* Developing real-time streaming systems using Kafka & Spark Structured Streaming
* Designing Data Warehouses using Star Schema modeling
* Working with cloud storage (AWS S3) and modern databases (PostgreSQL, Snowflake, MongoDB)
* Building interactive dashboards using Power BI & Grafana

---

## 🛠️ Tools

* **Languages:** Python, SQL
* **Big Data:** PySpark, Apache Kafka
* **Data Engineering:** Apache Airflow, ETL/ELT Pipelines
* **Databases:** PostgreSQL, MongoDB, Snowflake, TimescaleDB
* **Cloud & DevOps Tools:** AWS, Snowflake, Docker, GitHub, Linux
* **BI & Visualization:** Power BI, Grafana

---

## 🔗 Connect with Me

💼 [LinkedIn](https://www.linkedin.com/in/ahmedrefat1412/)
📧 [Email](mailto:ahmedrefat1412@gmail.com)
🌐 [Portfolio](https://portfolio-indol-alpha-oqb5g4f1kz.vercel.app/)

---

##  Featured Projects

---

## 1. ✈️ NYC Flight Delay Prediction & Analytics Platform

**Overview:**
An end-to-end data engineering platform combining batch and real-time pipelines to analyze and predict flight delays using flight and weather data.

[View Project](https://github.com/AhmedRefat1412/Flight-Airline-Analytics-Platform)

### Architecture:

<p align="center">
  <img src="https://github.com/AhmedRefat1412/Flight-Airline-Analytics-Platform/blob/main/doc/Flight%20%26%20Airline%20Analytics%20Platform.png" width="70%" />
</p>

**Batch Pipeline:**
Flights + Weather + Airports Data
→ AWS S3 (Bronze Layer)
→ PySpark Processing (Silver Layer)
→ Data Modeling (Galaxy Schema)
→ Snowflake (Data Warehouse)
→ Power BI (Analytics Dashboard)

**Streaming Pipeline:**
OpenSky API + Weather API
→ Apache Kafka
→ PySpark Structured Streaming
→ XGBoost (Delay Prediction)
→ TimescaleDB
→ Grafana (Real-time Dashboard)

**Key Features:**

* Batch + Real-time Integration
* ML-based Delay Prediction
* Medallion Architecture
* Galaxy Schema Data Warehouse
* Airflow Orchestration

---

## 2. End-to-End Financial Data Platform

**Overview:**
A complete end-to-end data engineering platform designed to process financial data for analytics, reporting, and monitoring.

[View Project](https://github.com/AhmedRefat1412/Financial_data_platform)

### Architecture:

<p align="center">
  <img src="https://github.com/AhmedRefat1412/Financial_data_platform/blob/main/docs/Financial_data_paltform.drawio.png" width="70%"/>
</p>

**Batch Pipeline:**
CSV / API Financial Data
→ AWS S3 (Raw Layer)
→ AWS Glue / PySpark Processing
→ AWS S3 (Processed Layer)
→ dbt Transformations
→ Amazon Redshift (Data Warehouse)
→ Power BI (Analytics Dashboard)

### Key Features:

* End-to-End ELT Pipeline
* Medallion-Style Data Layering
* Data Quality Validation using Great Expectations
* Automated Transformations with dbt
* Analytics-Ready Data Warehouse in Redshift
* Workflow Orchestration with Apache Airflow
* Scalable Cloud Architecture on AWS

---

## 3. End-to-End NYC Smart Traffic Data Pipeline

**Overview:**
A complete batch + real-time data engineering pipeline simulating smart city traffic analytics.

[View Project](https://github.com/AhmedRefat1412/NYC-Smart_Traffic_pipline)

### Architecture:

<p align="center">
  <img src="https://github.com/AhmedRefat1412/NYC-Smart_Traffic_pipline/blob/main/docs/nyc%20_traffic.drawio.png" width="70%" />
</p>

**Batch Pipeline:**
MongoDB + CSV + Weather Data + Accidents
→ AWS S3 (Raw Layer)
→ PySpark Processing
→ AWS S3 (Processed Layer)
→ PySpark Transformations
→ Snowflake (Data Warehouse)
→ Power BI (Analytics)

**Streaming Pipeline:**
API → Kafka → PySpark Structured Streaming
→ TimescaleDB → Grafana (Real-time Dashboard)

**Key Features:**

* Star Schema Data Warehouse Design
* Data Cleaning & Deduplication
* Surrogate Key Generation
* Batch + Streaming Integration
* Scalable Architecture

---

## 4. End-to-End E-commerce Data Engineering Pipeline

**Overview:**
A full ETL pipeline orchestrated with Apache Airflow, transforming raw e-commerce data into a structured Data Warehouse.

[View Project](https://github.com/AhmedRefat1412/ecommerce-data-pipeline)

### Architecture:

<p align="center">
  <img src="https://github.com/AhmedRefat1412/ecommerce-data-pipeline/blob/main/docs/E-commerce%20Data%20piplines.drawio.png" width="70%" />
</p>

MongoDB + CSV
→ PySpark Processing
→ PostgreSQL (Data Warehouse)
→ Power BI Dashboard

**Key Features:**

* Airflow DAG Orchestration
* Star Schema Modeling
* Automated ETL Pipeline
* Data Transformation & Validation

---

## 🎯 Current Focus

* Advanced PySpark & Distributed Processing
* Real-Time Data Streaming (Kafka + Spark)
* Cloud Data Engineering (AWS)

---

## 🎯 Goals

To become a professional Data Engineer building production-grade data systems and scalable architectures.
