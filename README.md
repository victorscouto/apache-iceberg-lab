# Apache Iceberg Data Engineering Lab

Welcome to my Apache Iceberg study repository! This project serves as a practical laboratory to explore, benchmark, and master **Apache Iceberg** table format across different data processing engines.

## 🚀 Objective

The main goal of this repository is to deep-dive into modern data lake architectures using Apache Iceberg. While the primary focus during this initial phase is on **Apache Spark**, the scope will expand to include other read/write engines and tools in future iterations.

## 🗂️ Repository Structure

```text
├── notebooks/        # Jupyter notebooks and interactive scripts
├── src/              # Python/Scala source code and pipelines
├── data/             # Sample datasets and warehouse storage
└── README.md         # Project documentation


## 🛠️ Tech Stack & Roadmap

* ​Table Format: Apache Iceberg
* ​Processing Engines:
* * ​Phase 1 (Current): Apache Spark
* * ​Phase 2 (Upcoming): Trino / Presto, Flink, and DuckDB (to be explored)
* ​Storage & Catalogs: Local / Cloud object storage, Hive Metastore / Nessie (as applicable)

## ​📚 References & Studies

​This repository's initial foundational setup and learning path are inspired by and developed alongside the following material:

* ​Course: Engenharia de Dados com Apache Iceberg e Spark
* ​Instructor: Prof. Fernando Amaral
* ​Platform: Udemy
* ​Key Topics Covered in Initial Studies:
* * ​Time Travel queries for auditing and historical analysis.
* * ​Data partitioning creation and optimization.
* * ​Catalog and metadata exploration (schemas, snapshots, manifests).
* ​* Data compaction and retention period management.
* * ​Schema evolution without data or history loss.
* * ​Insert, update, and upsert (merge) operations, alongside Parquet file integration.
* * ​Rollback operations to restore previous table states.

​Feel free to explore, open issues, or contribute with suggestions as this data engineering lab evolves!