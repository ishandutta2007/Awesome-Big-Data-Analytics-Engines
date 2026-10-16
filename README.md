# Awesome-Big-Data-Analytics-Engines

## Top Big Data & Analytics Engines Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Distributed Query Processing, Lakehouse Architecture & Real-Time Analytics*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Big Data & Analytics Engines**. These tools enable organizations to process petabytes of data, run sub-second analytical queries, and build lakehouse architectures—from MPP data warehouses to distributed SQL engines and unified batch/stream processing frameworks.



**Examples** include Snowflake, Databricks, Google BigQuery, Amazon Redshift, ClickHouse, Starburst, Firebolt, Teradata Vantage, Azure Synapse, and SingleStore (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, distributed query processing, and open lakehouse infrastructure—ideal for data engineers, analytics teams, and organizations seeking transparent, vendor-independent data platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Snowflake](https://www.snowflake.com/)**  

  **The cloud data warehouse that defined the modern analytics stack** . **Separates storage and compute**—scale each independently. Features **Snowpark for Python/Java/Scala**, **Snowpipe for streaming ingestion**, **Time Travel for historical queries**, and **data sharing across accounts**. **The enterprise standard** for cloud analytics.



- **[Databricks](https://www.databricks.com/)**  

  **The lakehouse platform** built by the original creators of Apache Spark . **Delta Lake** for ACID transactions on data lakes. **Photon engine** for vectorized query execution. **Mosaic AI** for model training and serving. **Unity Catalog** for unified governance across data and AI.



- **[Google BigQuery](https://cloud.google.com/bigquery)**  

  **Google's serverless, highly scalable data warehouse** . **Separation of storage and compute** with **automatic scaling**. **BigQuery ML** for in-database machine learning. **BI Engine** for sub-second dashboards. **The simplest serverless option**—no infrastructure to manage.



- **[Amazon Redshift](https://aws.amazon.com/redshift/)**  

  **AWS's petabyte-scale data warehouse** . **Redshift Spectrum** for querying S3 directly. **AQUA (Advanced Query Accelerator)** for hardware-accelerated queries. **RA3 instances** with managed storage. **The most integrated with AWS ecosystem**.



- **[ClickHouse Cloud](https://clickhouse.com/)**  

  **Managed version of the fastest open-source OLAP database** . **Sub-second queries on billions of rows**. **Column-oriented storage** with **vectorized execution**. **Real-time ingestion** with **materialized views**. **The fastest analytical database** for real-time dashboards.



- **[Starburst Galaxy](https://www.starburst.io/)**  

  **Fully managed Trino service** for federated analytics. **Query across data lakes, databases, and warehouses** without data movement. **The most flexible federated query engine**.



- **[Firebolt](https://www.firebolt.io/)**  

  **Cloud data warehouse purpose-built for analytics** . **Sub-second query performance** on petabyte-scale data. **Separates storage and compute** with **elastic scaling**.



- **[Teradata Vantage](https://www.teradata.com/)**  

  **Enterprise data platform** with **massively parallel processing**. **The most mature enterprise data warehouse** —decades of optimization for complex analytical workloads.



- **[Azure Synapse Analytics](https://azure.microsoft.com/en-us/products/synapse-analytics/)**  

  **Microsoft's unified analytics platform** combining **data integration, enterprise data warehousing, and big data analytics**. **Deep integration with Power BI and Microsoft ecosystem**.



- **[SingleStore](https://www.singlestore.com/)**  

  **Distributed SQL database** for **real-time analytics and transactions** . **HTAP (Hybrid Transactional/Analytical Processing)** —run operational and analytical workloads on the same data.



## Open-Source GitHub Projects



- **[Apache Spark](https://github.com/apache/spark)**  

  **The unified analytics engine for large-scale data processing** (Apache-2.0) . **40,000+ GitHub stars** . **The most widely deployed open-source big data processing engine** . **Features**: **Spark SQL** for structured data, **Spark Streaming** for real-time processing, **MLlib** for machine learning, **GraphX** for graph processing, and **Spark Core** for distributed computing . **Runs on Hadoop, Kubernetes, standalone, or cloud** . **The foundation of Databricks** and most modern data platforms .



- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**  

  **The fastest open-source column-oriented OLAP database** (Apache-2.0) . **40,000+ GitHub stars** . **Sub-second queries on billions of rows** —real-time analytics at unprecedented scale . **Features**: **column-oriented storage**, **vectorized query execution**, **real-time ingestion**, **materialized views**, **SQL support**, **distributed queries**, and **approximate functions** . **The standard for real-time analytics dashboards** and **log/event analytics** .



- **[Trino](https://github.com/trinodb/trino)**  

  **Distributed SQL query engine for federated analytics** (Apache-2.0) . **10,000+ GitHub stars** . **Query across heterogeneous data sources** —HDFS, S3, relational databases, Cassandra, Kafka, and more . **The open-source engine underlying Starburst Galaxy** . **The most flexible federated query engine** .



- **[Apache Druid](https://github.com/apache/druid)**  

  **Real-time analytics database** (Apache-2.0) . **Sub-second queries on streaming and batch data** . **Features**: **native Kafka/Kinesis integration**, **SQL support**, **schema auto-discovery**, and **elastic architecture** for billions to trillions of rows .



- **[Apache Doris](https://github.com/apache/doris)**  

  **MPP-based real-time analytical database** (Apache-2.0) . **MySQL protocol compatible** . **Features**: **real-time ingestion**, **high-concurrency point queries**, **materialized views**, and **lakehouse federation** .



- **[StarRocks](https://github.com/StarRocks/starrocks)**  

  **High-performance OLAP database** (Apache-2.0) . **Sub-second queries on data lake and warehouse** . **Features**: **lakehouse federation**, **materialized views**, **CBO optimizer**, and **vectorized execution** .



- **[Apache Flink](https://github.com/apache/flink)**  

  **Stateful computations over unbounded and bounded data** (Apache-2.0) . **The standard for stream processing** . **Features**: **event-time processing**, **exactly-once semantics**, **stateful operations**, **CEP (Complex Event Processing)**, and **SQL support** .



- **[Apache Beam](https://github.com/apache/beam)**  

  **Unified programming model for batch and streaming** (Apache-2.0) . **Features**: **portable APIs** across runners (Flink, Spark, Dataflow, Samza), **language SDKs** (Java, Python, Go), and **unified batch/streaming semantics** .



- **[Apache Hive](https://github.com/apache/hive)**  

  **Data warehouse software for reading, writing, and managing large datasets** (Apache-2.0) . **The original SQL-on-Hadoop solution** . **Features**: **HiveQL**, **partitioning**, **bucketing**, and **storage format abstraction** .



- **[Presto (prestodb)](https://github.com/prestodb/presto)**  

  **Distributed SQL query engine** (Apache-2.0) . **The original Presto implementation** —used at Facebook scale . **Features**: **SQL-on-Anything architecture**, **pluggable connectors**, and **low-latency interactive queries** .



- **[DuckDB](https://github.com/duckdb/duckdb)**  

  **In-process analytical database** (MIT) . **The SQLite of analytics** —runs anywhere, embedded in your application . **Features**: **columnar storage**, **vectorized execution**, **zero dependencies**, **Python/R/Java/Node.js bindings**, and **direct querying of Parquet/CSV** . **The fastest path to local analytical processing** .



- **[Apache Iceberg](https://github.com/apache/iceberg)**  

  **Open table format for huge analytic datasets** (Apache-2.0) . **The emerging standard for lakehouse tables** . **Features**: **schema evolution**, **partition evolution**, **time travel**, **ACID transactions**, and **multi-engine support** (Spark, Trino, Flink, Presto) .



- **[Delta Lake](https://github.com/delta-io/delta)**  

  **Open-source storage framework for ACID transactions on data lakes** (Apache-2.0) . **The Databricks-backed lakehouse format** . **Features**: **ACID transactions**, **scalable metadata**, **time travel**, **schema enforcement**, and **unified batch/streaming** .



- **[Apache Hudi](https://github.com/apache/hudi)**  

  **Streaming data lake platform** (Apache-2.0) . **Features**: **upserts and deletes**, **incremental processing**, **record-level indexing**, and **near-real-time ingestion** .



### Additional Strong Open-Source Options



- **[Apache Kylin](https://github.com/apache/kylin)** — Distributed analytics engine for extreme OLAP on Hadoop (Apache-2.0) . **Sub-second queries on petabyte-scale data** .

- **[Apache Kudu](https://github.com/apache/kudu)** — Columnar storage for fast analytics on rapidly changing data (Apache-2.0) .

- **[Greenplum](https://github.com/greenplum-db/gpdb)** — MPP data warehouse based on PostgreSQL (Apache-2.0) .

- **[TimescaleDB](https://github.com/timescale/timescaledb)** — Time-series database built on PostgreSQL (Apache-2.0) .

- **[Apache Calcite](https://github.com/apache/calcite)** — Dynamic data management framework (Apache-2.0) . **The SQL parser and optimizer powering many engines** .

- Community **n8n** workflows for data pipeline orchestration and analytics alerting.



**Frameworks for building custom systems**: Combine **Apache Spark** for batch processing with **Apache Flink** for streaming, **ClickHouse** or **DuckDB** for fast analytical queries, **Trino** for federated access, **Apache Iceberg** or **Delta Lake** for open table formats, and **Apache Doris** or **StarRocks** for real-time OLAP—creating a fully self-hosted, enterprise-grade data platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Big data analytics engines handling enterprise data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **Open-source analytics engines are mature and production-ready.** Apache Spark is the foundation of Databricks and most modern data platforms . ClickHouse delivers sub-second queries on billions of rows . Trino provides federated access across heterogeneous sources . DuckDB is the SQLite of analytics . **These are genuine alternatives to commercial platforms.**

- **The lakehouse architecture is the emerging standard.** Apache Iceberg, Delta Lake, and Apache Hudi provide ACID transactions, schema evolution, and time travel on object storage . **Open table formats decouple storage from compute**, eliminating vendor lock-in for the data layer.

- **Right tool for the right workload.** Spark for large-scale batch processing and ML . Flink for stateful stream processing . ClickHouse for real-time analytics dashboards . Trino for federated queries across silos . DuckDB for local analytics and embedded use cases . **No single engine dominates across all workloads.**

- **Separation of storage and compute is the cloud-era architecture.** Snowflake, BigQuery, Redshift, and Databricks all separate these layers—scale each independently based on workload . **Open-source equivalents (Spark on K8s, Trino on S3, Iceberg) provide the same flexibility without vendor lock-in.**

- Self-hosted open-source solutions require proper cluster management, query optimization, and ongoing maintenance. **Query performance depends on data layout**—partitioning, clustering, and file sizing matter more than engine choice for most workloads.



---



**Made for data engineers, analytics teams, and organizations building transparent data platform solutions.**  

Let's make Big Data & Analytics Engines more open, data-driven, and scalable.
