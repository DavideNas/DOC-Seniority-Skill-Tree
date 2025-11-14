# 🧩 ETL & Data Warehouse – Skill Tree (2025)

---

## 🔰 1. **Fondamenta ETL & Data Engineering**

| Area                      | Dettagli                                                          |
| ------------------------- | ----------------------------------------------------------------- |
| Concetti Base ETL/ELT     | ✅✅✅ (estrazione, staging, trasformazione, load, orchestration) |
| Formati Dati              | ✅✅ (CSV, JSON, Parquet, ORC, Avro)                              |
| Batch vs Streaming        | ✅✅ (micro-batch, real-time, near-real-time)                     |
| Data Integration Patterns | ✅ (CDC, SCD, merge, upsert, snapshotting)                        |
| API & Data Sources        | ✅ (REST, SOAP, JDBC, ODBC, Webhook, file system, object storage) |

---

## ⚙️ 2. **ETL Tools & Pipelines**

| Area                | Dettagli                                                           |
| ------------------- | ------------------------------------------------------------------ |
| ETL Tradizionale    | ✅ (Talend, Pentaho Kettle, Informatica PowerCenter)               |
| Modern ELT          | ✅✅ (dbt, Airbyte, Fivetran)                                      |
| Orchestration       | ✅✅✅ (Apache Airflow, Dagster, Prefect: DAG, scheduler, sensors) |
| CDC Systems         | ✅ (Debezium, GoldenGate concetti base)                            |
| Workflow Automation | ✅ (cron, script bash/python, event-driven triggers)               |

---

## 📦 3. **Data Warehouse Architecture**

| Area                        | Dettagli                                        |
| --------------------------- | ----------------------------------------------- |
| Modellazione Star/Snowflake | ✅✅✅ (fact, dimension, junk, bridge tables)   |
| OLTP vs OLAP                | ✅ (differenze, workload, pattern di lettura)   |
| Storage Layer               | ✅ (columnar storage, partitioning, clustering) |
| Data Marts                  | ✅ (dipendenti, indipendenti, federati)         |
| Query Engine                | ✅ (pushdown, MPP, vectorized execution)        |

---

## 🧱 4. **Cloud Data Warehouse**

| Area                | Dettagli                                                 |
| ------------------- | -------------------------------------------------------- |
| BigQuery            | ✅✅ (dataset/table, partition, clustering, SQL tuning)  |
| Snowflake           | ✅✅ (virtual warehouses, micro-partitions, Time Travel) |
| Redshift            | ✅ (sort keys, dist keys, WLM, spectrum)                 |
| Databricks SQL      | ✅ (Delta Lake, ACID layer, medallion architecture)      |
| Synapse / Azure SQL | ✅ (serverless pool, dedicated pool concetti base)       |

---

## 🔄 5. **Data Transformation & Modeling**

| Area                       | Dettagli                                                 |
| -------------------------- | -------------------------------------------------------- |
| SCD (Slowly Changing Dim.) | ✅✅ (Tipo 0, 1, 2, 3, 6: quando usarli)                 |
| Data Cleansing             | ✅ (null handling, dedup, enrichment, standardizzazione) |
| Business Logic Layer       | ✅✅ (surrogate keys, grain, conformed dimensions)       |
| Aggregazioni & KPI         | ✅ (rollup, cube, window functions, pre-aggregations)    |
| Quality Checks             | ✅ (assert, expectations, anomaly detection)             |

---

## 🧪 6. **Data Quality & Governance**

| Area                    | Dettagli                                                        |
| ----------------------- | --------------------------------------------------------------- |
| Data Quality Checks     | ✅✅ (Great Expectations, dbt tests, metadata rules)            |
| Data Lineage            | ✅ (OpenLineage, Marquez, built-in lineage in DWH tools)        |
| Master & Reference Data | ✅ (MDM concetti: golden record, survivorship)                  |
| Metadata Management     | ✅ (data catalog, glossari, schema registry, tagging)           |
| GDPR & Compliance       | ✅ (mascheramento, minimizzazione, auditing dei dati sensibili) |

---

## 📊 7. **Monitoring, Logging & Performance**

| Area                  | Dettagli                                                            |
| --------------------- | ------------------------------------------------------------------- |
| ETL Monitoring        | ✅ (DAG failures, retries, SLA miss, task duration analysis)        |
| Warehouse Performance | ✅✅ (query plan, partition pruning, caching)                       |
| Cost Optimization     | ✅ (compute vs storage scaling, autoscaling, query budgeting)       |
| Log Management        | ✅ (ELK stack, CloudWatch/Stackdriver, custom logging in pipelines) |
| Data Freshness Alerts | ✅ (lateness detection, freshness tests, anomaly detection)         |

---

## 🐍 8. **Scripting & Automation**

| Area               | Dettagli                                                       |
| ------------------ | -------------------------------------------------------------- |
| Python per ETL     | ✅✅ (Pandas, PySpark, richieste API, automazione file)        |
| SQL Avanzato       | ✅ (CTE, window, analytic functions, MERGE, UNNEST)            |
| Bash & CLI Tools   | ✅ (cron, gsutil, aws-cli, ssh, rsync, jq)                     |
| Container in ETL   | ✅ (Docker + pipelines, esecuzione isolata di job)             |
| CI/CD per Data Ops | ✅ (deploy di modelli dbt, test automatici, versioning schema) |

---

## 🧠 9. **Data Lake & Big Data**

| Area                   | Dettagli                                                 |
| ---------------------- | -------------------------------------------------------- |
| Data Lake Architecture | ✅ (bronze/silver/gold, raw/curated/cleaned)             |
| Hadoop Ecosystem       | ✅ (HDFS concetti base, Yarn, Hive, Impala)              |
| Apache Spark           | ✅ (PySpark, RDD vs DataFrame, jobs, shuffle, caching)   |
| Delta Lake / Iceberg   | ✅ (ACID transactions, schema evolution, time travel)    |
| Stream Processing      | ✅ (Kafka, Spark Streaming, Flink concetti fondamentali) |

---

# 🎓 Risorse & Libri per studiare

## _Gratuite_

- **YouTube**

  1. freeCodeCamp – _Data Engineering Full Course_
  2. Seattle Data Guy – _ETL, Data Warehousing, Modern Stack_
  3. Data Engineering with Zach Wilson

- **Documentazione**

  - BigQuery Docs
  - Snowflake Docs
  - dbt Documentation
  - Airflow Documentation

---

## _A Pagamento_

- **Libri**

  - 📘 _The Data Warehouse Toolkit_ – Kimball
  - 📕 _Fundamentals of Data Engineering_ – O'Reilly
  - 📙 _Designing Data-Intensive Applications_ – Kleppmann

- **Corsi**

  - Udemy – _Data Engineering with Python & Airflow_
  - Coursera – _GCP Data Engineering Professional_
  - Snowflake / dbt / Databricks official certifications
