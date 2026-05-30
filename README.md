# GoodCabs Lakehouse Pipeline

An end-to-end Data Engineering pipeline built for GoodCabs, a fast-growing cab company operating across multiple cities in India. Regional managers were not receiving operational data on time — this pipeline solves that by automating data flow from source to dashboard using Medallion Architecture on Databricks.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Databricks | Cloud data platform |
| PySpark | Distributed data processing |
| Lakeflow Spark Declarative Pipelines | Pipeline orchestration |
| Delta Lake | Storage with ACID transactions |
| Unity Catalog | Data governance and cataloging |
| AWS S3 | Raw data landing zone |
| Auto Loader | Incremental file ingestion |
| Python | Core programming language |

---

## Architecture

Raw trip data from multiple cities lands in S3, flows through three layers inside Databricks, and is served to dashboards for regional managers.
