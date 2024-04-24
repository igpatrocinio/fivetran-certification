# fivetran-certification

With the objective of being approved in the Fivetran certification, I created this repo to support me in my studies. 

# 1 Introduction

## 1.1 Fivetran

A Data Moviment specialized company. Tech Partners with the biggest players in the Market (AWS, GCP, Azure, Databricks, Snowflake) 

Big numbers: 3500+ customers, 99,9% platform uptime, 90000+ connector, 3+ trillion records synced everymonth 

Fivetran sits in the ingestion portion of a Data Pipeline. It connects with several differents sources and automates Data Ingestion into the Modern Data Warehouses solutions.

## 1.2 The Solution

Fivetran It solves the problem of centralizing Data, getting it from operational systems and delivering it in modern data warehouses. Its goal is to make Data Teams focus more on generating insights instead of handling ELT/ETL process. It fully manages the data normalization and provides automatic DML updates, schema migrations, Idempontent pipelines, log based CDC, it is cloud agnostic and has integrated and pre-built transformations.

![image](https://github.com/igpatrocinio/fivetran-certification/assets/105254279/b3930a89-8a1a-44f1-90e3-ffdc177e62c1)

Big Numbers:
- Over 3,500 customers
- 200+ Engineers
- 99.9% uptime and guaranteed data delivery
- 65.000+ total connectors managed
- 3.5 TRILLION records synced each month

If a product is not a native connector, it is possible to build a Cloud Function (Lambda, Az Functions, GCP Cloud Function, etc), and then connects to Fivetran to became fully automated.

Fivetran uses ELT approach:
![image](https://github.com/igpatrocinio/fivetran-certification/assets/105254279/37ad543e-0912-40e7-ba59-6cd6b2a7728c)

In the backend the core process of Fivetran if the following
1 - Authenticate in the source
2 - Handling of Schedule, Batching, querying and API calling
3 - Source sends Data in JSON format
4 - Automatic normalization of data, type coercion and dedup
5 - Creation of appropriate schema and tables in the destination
6 - Staging and loading data into the destination
7 - Integrated transformations modeling

Fivetran benefits:
- Data Driven: Consolidate data across different systems.
- Operational Efficiency: Realtime and high volume movement. High available
- Data Democratic: Enables data access when needed. Breaks Data Silos. Enables Data governance.

# 2 Architecture

## 2.1 Reference Architecture
![image](https://github.com/igpatrocinio/fivetran-certification/assets/105254279/d9640901-8acd-4b90-8ea5-9af1898bdec8)

As seen in the image above, Fivetrans connects to diverse sources of several types, and delivers data at in the modern cloud warehouses.



