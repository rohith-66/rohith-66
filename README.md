# Hi, I'm Rohith

**MS Data Science @ Arizona State University** · Graduating May 2026 · Open to Data Engineer & Data Analyst roles (F1 OPT)

I build data systems end to end — from raw, messy inputs to production-ready insights. My work spans cloud-native pipelines, ML forecasting, and AI-powered tooling.

---

## Flagship Projects

### ComorbidAlert — US County Comorbidity Forecasting System
> *Python · Prophet · LightGBM · SHAP · AWS S3 · Streamlit · Plotly*

End-to-end ML pipeline forecasting diabetes-cardiac comorbidity risk across all 3,144 US counties — built to catch counties on worsening trajectories 2–3 years before they cross critical thresholds.

```
CDC PLACES + Census ACS + BRFSS → 3-Layer Comorbidity Index → Weighted Ensemble Forecast → Early Warning Alerts
```

- **3-layer scoring model** — L1 clinical burden · L2 social vulnerability · L3 trajectory
- **Weighted ensemble** (Prophet + LightGBM) — WAPE 0.46%, outperforms both individual models
- **830 early warning alerts** — Critical / Warning / Watch tiers with plain-English reasons
- **Novel finding** — Great Plains emerging cluster (NE/IA/SD) not documented in prior literature
- **Live Streamlit dashboard** — choropleth map, county drill-down, alert table, key insights

🔗 **[Live Dashboard](https://comorbid-alert.streamlit.app)** · **[GitHub Repo](https://github.com/rohith-66/comorbid-alert)**

---

### DataFlow Studio — AI-Powered Data Engineering Pipeline
> *React · FastAPI · Claude AI · PySpark · Python · Vercel + Render*

Upload any CSV and watch it flow through a full Bronze → Silver → Gold medallion architecture powered by Claude AI.

- **Bronze** — Schema detection, null analysis, data quality profiling
- **Silver** — AI-generated PySpark & SQL transformations with real code output
- **Gold** — Auto-generated KPIs, charts, and business insights dashboard
- **Export** — Cleaned CSV, production PySpark `.py` file, pipeline report

🔗 **[Live Demo](https://dataflow-studio-seven.vercel.app)** · **[GitHub Repo](https://github.com/rohith-66/dataflow-studio)**

---

### Lakehouse Pipeline — GCP + Spark + BigQuery
> *Apache Spark · Docker · Google Cloud Storage · BigQuery · Parquet*

Production-style lakehouse architecture processing 80,000+ records per run.

```
Raw JSON (GCS Bronze) → Spark Transforms (Dockerized) → Parquet (Silver) → BigQuery Warehouse (Gold)
```

- Parameterized daily batch pipeline — single command execution
- Schema enforcement, nested JSON flattening, deduplication
- Partitioned + clustered BigQuery modeling

🔗 **[GitHub Repo](https://github.com/rohith-66/lakehouse)**

---

### Construction Portfolio — Cost Forecasting System
> *PostgreSQL · Power BI · 75,000+ Work Items*

End-to-end performance analytics framework simulating a real-world project controls environment.

- Planned vs Actual Cost Tracking with SQL window functions
- CPI & EAC forecasting, portfolio risk classification (RAG framework)
- What-if financial impact simulation
- Identified cost overruns, flagged high-risk projects

---

## Core Stack

| Layer | Technologies |
|-------|-------------|
| **Data Engineering** | PySpark · Apache Spark · Docker · GCP · BigQuery · AWS S3 · Parquet |
| **ML & Forecasting** | Prophet · LightGBM · Scikit-learn · SHAP · PyTorch |
| **Languages** | Python · SQL · PostgreSQL |
| **AI Tooling** | Claude API |
| **BI & Visualization** | Streamlit · Plotly · Power BI · Tableau |
| **Backend** | FastAPI · REST APIs |
| **Frontend** | React · Tailwind CSS |
| **Tools** | Git · Docker · Jupyter |

---


## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rohith%20Srinivasa-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohithsrinivasa/)
[![Portfolio](https://img.shields.io/badge/Portfolio-rohithsrinivasa.com-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://rohithsrinivasa.com)
[![Email](https://img.shields.io/badge/Gmail-rohithsrinivasa1-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohithsrinivasa1@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-rohith--66-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rohith-66)

---

*Build systems that reduce uncertainty — not increase complexity.*
