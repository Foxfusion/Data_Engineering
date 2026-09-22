# Data Engineering Repository Boundaries

Use one repository per logical area:

- **Data_Engineering** — cross-platform design and reusable patterns
- **Spark** — Spark/Scala and Zeppelin
- **FoxPySpark** — PySpark
- **Flink** — Flink
- **CDPSetup** — Cloudera platform setup
- **CDE_Tour_ACE_HOL** — Cloudera Data Engineering lab material

## Repositories to retire

- **Scala** — contains no meaningful standalone code; Spark/Scala belongs in `Spark`.
- **udemy-spark-streaming** — upstream course fork; retain only as an archive/reference if desired.

Avoid duplicating the same example across several repositories.
