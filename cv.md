# Priyanka Bhutada

Data / ML Engineer — I build the pipelines and the models that run on them.

- **Location:** Boston, Massachusetts, United States
- **Email:** priyankabhutada02@gmail.com
- **Phone:** +1 857-421-7449
- **LinkedIn:** linkedin.com/in/priyanka-bhutada
- **GitHub:** [add link]
- **Blog:** [add link]

## Summary

Data/ML Engineer who owns the full path from ingestion to the model. Most of my
work is on the ingestion and transformation side, and the ML systems I have
shipped sit downstream of production pipelines I owned end-to-end. Spark,
Databricks, Python, SQL, MLflow. Ex-Accenture, currently completing an MS in
Applied Machine Intelligence at Northeastern.

## Experience

### Whiteklay — Artificial Intelligence Engineer
*January 2023 – August 2024*

- Owned the production Spark ETL (~2M records/day) feeding the recommendation
  and feedback systems.
- Modeled the curated tables (data products) that three downstream teams
  reported from.
- Built a collaborative-filtering recommender — personalization coverage +25%,
  engagement +22%.
- Fine-tuned a BERT classifier that routed incoming customer feedback,
  replacing manual triage.
- Tracked training runs and model versions in MLflow so results held up across
  retrains.

### Accenture — Data Engineer
*June 2022 – November 2022*

- Built production Python and SQL ETL pipelines moving 10M+ records/week into
  the reporting layer.
- Trained an XGBoost anomaly-detection model with SHAP explanations so analysts
  could see why individual records were flagged.

### Accenture — Application Development Associate
*December 2020 – May 2022*

- Built and deployed Spring Boot + PostgreSQL microservices on AWS for a
  cashless-payments client application.
- Built REST and GraphQL services over PostgreSQL.
- Built Talend ETL workflows that consolidated source systems into the
  reporting database.
- Promoted to Data Engineer.

## Projects

### CFPB × Lending Club Lakehouse Pipeline
Lakehouse pipeline over CFPB consumer-complaint and Lending Club loan data. The
two datasets share no row-level join key, so I reported segment-level
correlation and stated explicitly that it does not show causation. Backfilling
the CFPB API required working around a 10,000-record paging cap, which I solved
with a resumable, month-by-month load. — [add link]

### LLM-as-Judge Evaluation Pipeline
Built an LLM-as-judge pipeline for evaluating generated drafts. The judge kept
inventing problems to fill its quota until I required every criticism to quote
the draft verbatim, which grounded its critiques in the actual text. — [add link]

## Education

### Northeastern University
Master's, Applied Machine Intelligence — *September 2024 – May 2026*

### Shri Ramdeobaba College of Engineering and Management
Bachelor of Engineering (BE), Electrical, Electronics and Communications
Engineering — *August 2016 – October 2020*

## Skills

**Data Engineering:** Apache Spark, Databricks (Azure), SQL, Python, ETL/ELT
pipeline design, Airflow, dbt, Talend, Hive, Hadoop/HDFS, data modeling,
lakehouse, PostgreSQL

**ML / AI:** MLflow, XGBoost, SHAP, BERT fine-tuning, collaborative filtering /
recommenders, LLM evaluation

**Backend / Cloud:** Java, Spring Boot, REST, GraphQL, AWS (Lambda, API Gateway)
