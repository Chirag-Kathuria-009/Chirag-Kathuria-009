# Hi, I'm Chirag 👋

Data Engineer with 2+ years of production experience in FinTech, currently completing an **M.Sc. in Data Science at Universität Trier** (graduating Oct 2026). Based in Frankfurt, Germany — open to **Werkstudent, internship, and full-time** Data Engineer / Data Scientist / AI Engineer roles across **Germany and Luxembourg**.

EU student visa, no employer sponsorship required.

---

### 🚧 Currently building

**[DORA ICT Incident Intelligence Pipeline](https://github.com/Chirag-Kathuria-009/DORA-Pipeline)**
A real-time data pipeline that classifies ICT operational incidents against EU DORA (Article 18) reporting thresholds, modeled on the compliance requirements now mandatory for 3,600+ German financial institutions.
Ingestion (Kafka), schema validation (Pydantic), and the BaFin classification rules engine (with full unit test coverage) are complete; the streaming, dbt/data-quality, orchestration, and dashboard layers are in active development.
`Kafka` · `PySpark Structured Streaming` · `Apache Iceberg` · `MinIO` · `dbt Core` · `Great Expectations` · `Airflow` · `Superset` · `Docker Compose`

**[Self-Healing Data Pipeline Agent](<add-your-repo-link>)**
A multi-agent LangGraph system that watches an Apache Airflow pipeline, diagnoses task failures with an LLM (tool-calling into log retrieval, schema inspection, and read-only SQL), and either auto-executes a fix or routes it to a human for approval — decided by a separate, deterministic guardrail layer, not by the LLM itself. The full pipeline (triage → investigate → remediate → approval/report) is built and tested end-to-end against real injected failures (upstream timeouts, schema drift, null spikes); automated test coverage and documentation are the remaining work.
`LangGraph` · `LangChain` · `Google Gemini` · `FastAPI` · `Apache Airflow` · `PostgreSQL` · `Docker Compose`

---

### 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**AI / Agentic Systems**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Data Engineering**
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)

**Cloud & Infra**
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Analytics & Viz**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Superset](https://img.shields.io/badge/Superset-20A6C9?style=flat&logo=apache&logoColor=white)

---

### 📂 Featured Projects

| Project | What it does |
|---|---|
| **[DORA-Pipeline](https://github.com/Chirag-Kathuria-009/DORA-Pipeline)** | Real-time ICT incident classification pipeline built to EU DORA / BaFin Article 18 reporting requirements |
| **[Self-Healing Pipeline Agent](https://github.com/Chirag-Kathuria-009/MultiAgent_Debugging_Pipeline)** | Multi-agent LangGraph system that diagnoses Airflow task failures with an LLM and auto-remediates or escalates to a human, gated by a deterministic guardrail layer |
| **[FraudTransactionsClassifier](https://github.com/Chirag-Kathuria-009/FraudTransactionsClassifier)** | Fraud detection on transaction data using LightGBM, served via FastAPI, deployed on AWS |
| **[FEVER_FACT_CHECKER](https://github.com/Chirag-Kathuria-009/FEVER_FACT_CHECKER)** | Automatic fact verification on Wikipedia claims using a BERT-based classifier (FEVER dataset) |


---

### 📍 Background

Production data engineering experience at **Bajaj Finserv**, building ETL pipelines, PySpark jobs, BI dashboards, and an eKYC document-extraction workflow (OpenCV + fuzzy name-matching). Currently sharpening that with regulatory-grade, EU-context data engineering through my M.Sc., and extending into agentic/LLM systems through the Self-Healing Pipeline Agent above.

Also learning German (A2 → B1).

---

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/chirag-kathuria/) · [Email](mailto:chiragkathuria24de@gmail.com)
