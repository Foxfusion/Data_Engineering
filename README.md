# Data Engineering

Cross-platform data-engineering workspace for patterns that are not tied to one execution engine.

## Use this repository for

- ingestion and ETL/ELT patterns
- orchestration examples
- data-quality patterns
- SQL and transformation examples
- architecture notes
- reusable utilities that span multiple platforms

## Repository boundaries

- **Data_Engineering** — cross-platform patterns and architecture
- **Spark** — Spark/Scala and Zeppelin work
- **FoxPySpark** — PySpark-specific work
- **Flink** — Apache Flink streaming/batch work
- **CDPSetup** — Cloudera platform setup
- **CDE_Tour_ACE_HOL** — Cloudera Data Engineering hands-on-lab material

The old **Scala** repository is not needed as a separate active repo; Scala/Spark examples belong in **Spark**.

The upstream **udemy-spark-streaming** fork is reference/course material and should not be treated as an active FoxFusion project.

## Layout

- `architecture/`
- `ingestion/`
- `orchestration/`
- `sql/`
- `quality/`
- `docs/`
- `tests/`

Do not commit credentials, customer data, large datasets, or generated runtime output.
