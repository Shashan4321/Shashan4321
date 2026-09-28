<h1 align="center">Hi, I'm Shashank Singh 👋</h1>
<h3 align="center">Senior Data Analyst · Power BI & Microsoft Fabric · Snowflake · SQL · Python · GenAI (NL-to-SQL)</h3>

<p align="center">
  <a href="https://shashan4321.github.io"><img src="https://img.shields.io/badge/Portfolio-shashan4321.github.io-1F4E79?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/shashank-moon"><img src="https://img.shields.io/badge/LinkedIn-shashank--moon-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:shashan4321@gmail.com"><img src="https://img.shields.io/badge/Email-shashan4321%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open%20to%20work-Gurugram%20%7C%20Bengaluru%20%7C%20Hyderabad%20%7C%20Remote-2E8540?style=flat-square" alt="Open to work">
</p>

I turn messy ERP, sales and operations data into **trusted dashboards, automated reports and AI-assisted analytics** that business teams actually use.
At **Walitechs Solutions** I architect Microsoft Fabric + Power BI solutions across Sales, Finance, HR and Supply Chain, led a **zero-data-loss Dynamics AX → D365 Business Central migration**, and built an **NL-to-SQL** tool so non-technical managers can ask their data questions in plain English.

🏆 **Employee of the Month**, Walitechs Solutions

### 📈 Professional impact

| 3+ yrs | 10+ | 50+ | ~50% | 35% | 0 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| in data & MIS roles | enterprise Power BI dashboards | stakeholders served | less reporting time | faster SQL / Snowflake queries | records lost in the AX → D365 migration |

### 🚀 Featured projects

Every project runs on public or synthetic data, has tests and CI, and reports only numbers computed from its own data.

| Project | Business problem | Stack | Demo | Result (in the project) |
|---|---|---|---|---|
| **[NL-to-SQL Analytics Agent](https://github.com/Shashan4321/nl-to-sql-analytics-agent)** | Managers wait days for simple data answers | Claude API (tool use), DuckDB/SQL, sqlglot, Streamlit | **[▶ Live demo](https://shashan4321.github.io/nl-to-sql-demo/)** (in-browser, no sign-up) | AST-based read-only guardrails, self-correcting agent, **32-question eval set**, 66 tests (incl. DuckDB vs SQLite parity) |
| **[Fabric Lakehouse End-to-End](https://github.com/Shashan4321/fabric-lakehouse-end-to-end)** | No trusted view of supplier OTIF and stock | Microsoft Fabric, OneLake, PySpark, Delta, Warehouse, Direct Lake | [Deploy guide](https://github.com/Shashan4321/fabric-lakehouse-end-to-end/blob/main/docs/deploy_on_fabric.md) | Bronze → Silver → Gold with a DQ gate; OTIF **71.9%** vs 85% target, 63 bad receipts quarantined |
| **[Snowflake JSON CDC Pipeline](https://github.com/Shashan4321/snowflake-json-cdc-pipeline)** | Nested app events, duplicates, schema drift | Snowflake VARIANT, FLATTEN, Streams + Tasks, MERGE | `make local` | Idempotent CDC; net sales match an independent recomputation **to the paisa** |
| **[ERP Migration Toolkit (AX → D365) + Fabric reporting](https://github.com/Shashan4321/erp-migration-toolkit-ax-to-d365)** | ERP cut-overs lose data quietly, and legacy AX reports break after go-live | Python, pandas, YAML specs, Microsoft Fabric (Lakehouse, Delta, Spark), T-SQL | [Reconciliation report](https://github.com/Shashan4321/erp-migration-toolkit-ax-to-d365/blob/main/reports/reconciliation.md) · [Fabric AX views](https://github.com/Shashan4321/erp-migration-toolkit-ax-to-d365#after-go-live-ax-compatible-reporting-on-microsoft-fabric) | **14/14 migration checks pass**; BC → Fabric lakehouse with AX-compatible views, **10/10 reconciled** |
| **[AI Report Automation](https://github.com/Shashan4321/ai-report-automation)** | Hours lost writing monthly MIS commentary | Python, Claude API, Jinja2, GitHub Actions cron | [Sample report](https://github.com/Shashan4321/ai-report-automation/blob/main/docs/report_preview.png) | LLM narrative is **number-checked** against the KPI pack before it is e-mailed |
| **[Sales Intelligence (Power BI)](https://github.com/Shashan4321/sales-intelligence-powerbi)** | One sales truth + who is about to churn | SQL star schema, Power BI PBIP/TMDL, DAX, RLS, scikit-learn, SHAP | **[Power BI report](https://github.com/Shashan4321/sales-intelligence-powerbi#power-bi-report)** | 2 report pages built from code, 33 DAX measures, calc group, dynamic RLS; churn model ROC-AUC **0.92** |
| **[Python Analytics Playbook](https://github.com/Shashan4321/python-analytics-playbook)** | Slow, fragile notebook code in reporting jobs | pandas, Polars, DuckDB, Pandera, openpyxl, pytest | [Benchmarks](https://github.com/Shashan4321/python-analytics-playbook/blob/main/benchmarks/RESULTS.md) | **59% less memory**, 415x faster than loops on 1M rows; idempotent ETL, Excel MIS, 31 tests |
| **[Power BI Business Dashboards](https://github.com/Shashan4321/PowerBI-Business-Dashboards)** | Dashboards that drive decisions | Power BI, theme JSON, DAX specs | [5 pages](https://github.com/Shashan4321/PowerBI-Business-Dashboards#1-executive-sales-overview) | Sales and Churn pages built in Power BI; Product, HR and Supply Chain designed next |
| **[DAX Measures Library](https://github.com/Shashan4321/DAX-Measures-Library)** | Re-writing the same DAX in every report | DAX | Docs | 30+ patterns with example outputs (YoY, Indian FY, Top N, RLS) |

### 🛠️ Tech stack

**Cloud & Fabric**
![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-117865?style=flat-square)
![OneLake](https://img.shields.io/badge/OneLake-0078D4?style=flat-square)
![Lakehouse](https://img.shields.io/badge/Lakehouse%20%7C%20Warehouse-0078D4?style=flat-square)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

**BI**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Advanced%20Excel%20%7C%20VBA-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**SQL**
![SQL Server](https://img.shields.io/badge/SQL%20Server%20%7C%20T--SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)

**Python**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**ERP**
![Dynamics 365](https://img.shields.io/badge/D365%20Business%20Central-0B53CE?style=flat-square)
![Dynamics AX](https://img.shields.io/badge/Dynamics%20AX-0B53CE?style=flat-square)

**AI**
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![NL-to-SQL](https://img.shields.io/badge/NL--to--SQL%20%7C%20Prompt%20Engineering-555555?style=flat-square)

**Engineering**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square)

### 🔨 Currently building

- **NL-to-SQL agent v2:** Snowflake and Postgres connectors, few-shot retrieval from the eval set, a YAML semantic layer
- **Fabric lakehouse on a live trial:** pipeline run, Direct Lake report screenshots and Capacity Metrics
- **dbt:** moving the sales star schema to dbt models with tests and docs

### 🤝 Let's talk

Open to **Senior Data Analyst, Power BI Developer / BI Architect, Analytics Engineer and GenAI Data Analyst** roles in Gurugram / NCR, Bengaluru, Hyderabad or remote.
📫 [shashan4321@gmail.com](mailto:shashan4321@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/shashank-moon) · 🌐 [Portfolio](https://shashan4321.github.io)

<sub>🎓 MBA (Marketing & HR), GL Bajaj · B.Com (Hons), BHU · Data Analytics Certification, Ducat</sub>
