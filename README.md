<div align="center">

<!-- Replace YOUR_COLOR with e.g. 0d1117 for dark, or try: https://capsule-render.vercel.app -->
![header](https://capsule-render.vercel.app/api?type=waving&color=6E40C9&height=200&section=header&text=Rohith%20Srinivasa&fontSize=48&fontColor=ffffff&animation=fadeIn&desc=Data%20Engineer%20%7C%20ML%20Builder%20%7C%20ASU%20%2726&descSize=18&descAlignY=72)

</div>

---

Hey, I'm Rohith. I'm finishing my MS in Data Science at Arizona State and I build things that turn messy, real-world data into something actually useful.

Not dashboards for the sake of dashboards. Systems that give someone a decision they couldn't make before.

Right now I'm open to **Data Engineer** and **Data Analyst** roles on F1 OPT. Based in Tempe, AZ.

---

## what I've built

### ComorbidAlert — county-level health forecasting across the US
`Python` `Prophet` `LightGBM` `SHAP` `AWS S3` `Streamlit`

Forecasts diabetes-cardiac comorbidity risk across all 3,144 US counties, flagging counties on a worsening trajectory 2-3 years before they hit critical thresholds. Built a 3-layer scoring model (clinical burden + social vulnerability + trajectory), ran a weighted ensemble that hit WAPE 0.46%, and surfaced 830 early warning alerts with plain-English explanations.

Found a Great Plains emerging cluster (NE/IA/SD) that hadn't been documented in prior literature.

→ [live dashboard](https://comorbid-alert.streamlit.app) · [repo](https://github.com/rohith-66/comorbid-alert)

---

### DataFlow Studio — upload a CSV, get a production pipeline
`React` `FastAPI` `Claude API` `PySpark` `Vercel`

Drop in any CSV and it runs through a full Bronze → Silver → Gold medallion architecture powered by Claude. It detects schema issues, generates real PySpark and SQL transformations, builds a KPI dashboard, and exports a production-ready `.py` file. Not a toy demo, actual code you can run.

→ [live demo](https://dataflow-studio-seven.vercel.app) · [repo](https://github.com/rohith-66/dataflow-studio)

---

### Lakehouse Pipeline — GCP + Spark + BigQuery
`Apache Spark` `Docker` `GCS` `BigQuery` `Parquet`

Production-style lakehouse processing 80,000+ records per run. Raw JSON in GCS goes through Dockerized Spark transforms, lands as Parquet in Silver, and loads into a partitioned + clustered BigQuery warehouse. Single command execution, schema enforcement, deduplication built in.

→ [repo](https://github.com/rohith-66/lakehouse)

---

### Construction Portfolio — cost forecasting on 75,000+ work items
`PostgreSQL` `Power BI`

End-to-end project controls simulation. Planned vs actual cost tracking with SQL window functions, CPI & EAC forecasting, RAG risk classification, and what-if financial impact modeling. Identified real cost overruns and flagged high-risk projects before they escalated.

---

## stack

```
data engineering   PySpark · Spark · Docker · GCP · BigQuery · AWS S3 · Parquet
ml & forecasting   Prophet · LightGBM · Scikit-learn · SHAP · PyTorch
languages          Python · SQL · PostgreSQL
ai tooling         Claude API
viz & bi           Streamlit · Plotly · Power BI · Tableau
backend            FastAPI · REST APIs
frontend           React · Tailwind CSS
tools              Git · Docker · Jupyter
```

---

## find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rohith%20Srinivasa-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohithsrinivasa/)
[![Portfolio](https://img.shields.io/badge/Portfolio-rohithsrinivasa.com-6E40C9?style=flat-square&logo=vercel&logoColor=white)](https://rohithsrinivasa.com)
[![Email](https://img.shields.io/badge/Gmail-rohithsrinivasa1-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rohithsrinivasa1@gmail.com)

---

<div align="center">
  <sub>build systems that reduce uncertainty, not increase complexity</sub>
</div>
