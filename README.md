# Data Engineering Bootcamp

## Syllabus

### [Week 1: Introduction & Prerequisites](week_1_basics_n_setup)

* Course overview
* Introduction to GCP
* Docker and docker-compose 
* Running Postgres locally with Docker
* Setting up infrastructure on GCP with Terraform
* Preparing the environment for the course
* Homework

[More details](week_1_basics_n_setup)


### [Week 2: Data ingestion](week_2_data_ingestion)

* Data Lake
* Workflow orchestration
* Setting up Airflow locally
* Ingesting data to GCP with Airflow
* Ingesting data to local Postgres with Airflow
* Moving data from AWS to GCP (Transfer service)
* Homework

[More details](week_2_data_ingestion)


### [Week 3: Data Warehouse](week_3_data_warehouse)


* Data Warehouse
* BigQuery
* Partitoning and clustering
* BigQuery best practices
* Internals of BigQuery
* Integrating BigQuery with Airflow
* BigQuery Machine Learning

[More details](week_3_data_warehouse)


### [Week 4: Analytics engineering](week_4_analytics_engineering/)

* Basics of analytics engineering
* dbt (data build tool)
* BigQuery and dbt
* Postgres and dbt
* dbt models
* Testing and documenting
* Deployment to the cloud and locally
* Visualising the data with google data studio and metabase 


[More details](week_4_analytics_engineering)


### [Week 5: Batch processing](week_5_batch_processing)

* Batch processing 
* What is Spark
* Spark Dataframes
* Spark SQL
* Internals: GroupBy and joins

[More details](week_5_batch_processing)

### [Week 6: Streaming](week_6_stream_processing)

* Introduction to Kafka
* Schemas (avro)
* Kafka Streams
* Kafka Connect and KSQL

[More details](week_6_stream_processing)


### [Week 7, 8 & 9: Project](week_7_project)

Putting everything we learned to practice

* Week 7 and 8: working on your own project
* Week 9: reviewing your peers

[More details](week_7_project)


### Upcoming buzzwords

*  Delta Lake/Lakehouse
  * Databricks
  * Apache iceberg
* Data mesh
* KSQLDB
* Streaming analytics
* MLOps


## Overview

### Architecture diagram
<img src="images/architecture/arch_1.jpg"/>

### Technologies
* *Google Cloud Platform (GCP)*: Cloud-based auto-scaling platform by Google
  * *Google Cloud Storage (GCS)*: Data Lake
  * *BigQuery*: Data Warehouse
* *Terraform*: Infrastructure-as-Code (IaC)
* *Docker*: Containerization
* *SQL*: Data Analysis & Exploration
* *Airflow*: Pipeline Orchestration
* *dbt*: Data Transformation
* *Spark*: Distributed Processing
* *Kafka*: Streaming


## Instructors

- Ankush Khanna (https://linkedin.com/in/ankushkhanna2)
- Sejal Vaidya (https://linkedin.com/in/vaidyasejal)
- Victoria Perez Mola (https://www.linkedin.com/in/victoriaperezmola/)
- Alexey Grigorev (https://linkedin.com/in/agrigorev)

## Tools 

For this course you'll need to have the following software installed on your computer:

* Docker and Docker-Compose
* Python 3 (e.g. via [Anaconda](https://www.anaconda.com/products/individual))
* Google Cloud SDK 
* Terraform

See [Week 1](week_1_basics_n_setup) for more details about installing these tools



