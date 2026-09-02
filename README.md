# Jangkoon Park

**Data Engineer | Oracle Performance | Pipeline Architecture**

Software engineer with 17+ years of experience in enterprise systems (SI/SM), specializing in Oracle-based system maintenance, performance tuning, and operational stability.

Now focused on designing and implementing **end-to-end data pipeline systems**, with an emphasis on **system boundaries, data flow reliability, and reproducible environments**. Built and validated both a file-based batch pipeline (NiFi → Airflow → Elasticsearch) and its streaming/distributed alternative (Kafka → Spark), so architectural trade-offs are backed by two working implementations rather than one implementation and an opinion.

---

## Why Data Engineering

17 years inside enterprise systems provided deep insight into where data pipelines fail:

* data duplication
* silent data corruption — a pipeline that runs cleanly and returns a wrong number
* boundary mismatches between systems

The expensive failures were rarely the ones that looked like failures. A query that hard-parses five hundred times a minute is fast in isolation and slows the whole database under load. A merge against a history-keeping dimension inflates a total by 22% without raising anything. This experience directly translates into building **reliable, production-oriented data pipelines**.

---

## Core Strengths

* Oracle performance tuning — execution plans, statistics, bind variables, flashback recovery
* End-to-end data pipeline design (ingestion → processing → serving), both file-based and streaming
* Designing system boundaries across independent data layers
* Data cleaning as a testable contract — decisions scored against ground truth, not just implemented
* Backend development (Java, Spring)
* Web development alongside backend — HTML, CSS, JavaScript, SVG; data layer and presentation layer handled by one person
* Enterprise system operations and maintenance

---

## Tech Stack

* **Languages** — Python, SQL, PL/SQL, Java
* **Database** — Oracle (17 years, enterprise ERP), PostgreSQL, MySQL
* **Data Engineering** — Airflow, NiFi, Kafka, Spark, Pandas
* **Backend** — Spring Framework, JSP
* **Frontend** — HTML, CSS, JavaScript, SVG
* **Infrastructure** — Linux, Docker
* **Tools** — Git, Jupyter Notebook

---

## Featured Projects

| Repository | Description |
| --- | --- |
| [oracle-tuning-labs](https://github.com/jangkoon-park/oracle-tuning-labs) | Five Oracle production failure patterns reproduced locally — index-disabling predicates, row-by-row procedures, stale statistics, hard parsing, and flashback recovery. Each lab names the condition under which the rejected fix would have been correct |
| [data-cleaning-labs](https://github.com/jangkoon-park/data-cleaning-labs) | Cleaning decisions scored against ground truth — 57 contract tests, rejected approaches kept as failing-case assertions |
| [data-engineering-pipeline-labs](https://github.com/jangkoon-park/data-engineering-pipeline-labs) | End-to-end pipeline built two ways — file-based (NiFi → Airflow → Elasticsearch) and streaming/distributed (Kafka → Spark) — with the trade-off between them measured, not assumed |
| [data-engineering-fundamentals-project](https://github.com/jangkoon-park/data-engineering-fundamentals-project) | Architecture and design-decision study; every rejected alternative documented with its reasoning |
| [sql-plan-tuning-labs](https://github.com/jangkoon-park/sql-plan-tuning-labs) | PostgreSQL/MySQL tuning with reproducible benchmarks and execution plan comparison (up to 45× improvement) |
| [warehouse-map-svg](https://github.com/jangkoon-park/warehouse-map-svg) | Interactive warehouse floor plan drawn from a versioned layout record rather than a hand-drawn SVG — stock joins on location ID, and a CI check fails when inventory exists the map cannot show |

---

## Professional Experience

* 17+ years in SI/SM development and enterprise system maintenance
* Experience across finance, construction, public sector, and large-scale enterprise systems
* Projects include CJ Construction, KT, Lotte Card, POSCO, Doosan

---

## Education

* Big Data MBA · Sejong University
* B.S. in Mechanical Engineering · Sejong University

---

## Current Focus

* Extending pipeline and cleaning work toward cloud-native tooling (AWS/GCP)
* Applying the same decision-record discipline to new data engineering problems

---