<div align="center">
  <h1>Hamza Shaikh</h1>
  <p><strong>Aspiring Data Analyst | Data Engineering | Python & BI</strong></p>
  <p>📍 Mumbai, India</p>

  <p>
    <a href="https://www.linkedin.com/in/hamza-shaikh-data/">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/ShaikhHamza104">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="mailto:kmohdhamza10@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>

---

### 👋 About Me

BSc IT student at VSIT, Mumbai, targeting **Data Analyst, BI Analyst, Junior Data Engineer and Analytics Engineer** roles, with a path into **Data Science**. I build end-to-end data projects: ETL pipelines, SQL analytics, star-schema modeling, APIs and Power BI dashboards.

* 🎯 **Target roles:** Data Analyst, BI Analyst, Junior Data Engineer, Analytics Engineer
* 📚 **Learning:** statistics, hypothesis testing, scikit-learn (CampusX Data Science Mentorship)

---

### 🛠️ Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Analytics & BI** | SQL (MySQL, DuckDB), Power BI (DAX, Power Query), star-schema modeling, EDA |
| **Data Engineering** | ETL pipelines, DuckDB, Apache Parquet, MySQL, SQLite, SQLAlchemy, Bronze/Silver data layers, data quality validation |
| **Python** | Pandas, NumPy, Matplotlib, Seaborn, Plotly, Pydantic, pytest |
| **APIs & Collection** | FastAPI, REST API design, ASGI middleware, Selenium, BeautifulSoup, Regex |
| **Tools** | Git, GitHub, GitHub Actions, Docker, Streamlit, Jupyter, Marimo, Uvicorn, uv, Linux/Bash |

---

### 🚀 Featured Projects

#### 1. 🏏 [CricPulse Engine – High-Performance IPL Analytics API](https://github.com/ShaikhHamza104/CricPulse-Engine)

🌐 **Live API & Interactive Docs:** [cricpulse-engine.onrender.com/docs](https://cricpulse-engine.onrender.com/docs)

```text
Cricsheet Data ➔ ETL ➔ DuckDB Bronze (raw) ➔ Silver (cleaned) + Parquet ➔ FastAPI Endpoints ➔ Docker + CI/CD
```

* Architected a **columnar OLAP analytical engine in DuckDB** with an automated Python ETL pipeline processing **1,243 matches (295,000+ deliveries)** into raw (Bronze) and cleaned (Silver) tables backed by Parquet.
* Designed a **5-stage data quality gate**: resolved 51 missing venue/city records, harmonized franchise rebrandings, and validated 14,705 dismissals with 0 nulls.
* Built **9 REST endpoints** with FastAPI + Pydantic v2 and **sub-30ms** analytical aggregations: player career profiles, head-to-head rivalries and season leaderboards.
* Added ASGI middleware under a 512MB RAM limit: sliding-window rate limiting (60 req/min), OWASP security headers, request ID tracing and latency profiling, covered by **92 automated tests**.
* Containerized with **multi-stage Docker** and deployed to production with automated **GitHub Actions CI/CD**.

**Skills Used:**

* Python 3.13, FastAPI, Pydantic v2, Uvicorn, REST API design
* DuckDB, Apache Parquet, ETL, Bronze/Silver data layers, data quality validation
* ASGI middleware, rate limiting, OWASP security, pytest
* Docker (multi-stage), GitHub Actions CI/CD, Git/GitHub

---

#### 2. 📊 [Brazilian E-Commerce Analytics (Olist)](https://github.com/ShaikhHamza104/brazilian-ecommerce-analytics)

```text
9 Relational CSVs ➔ Python Cleaning ➔ MySQL (3NF) ➔ Star Schema (Parquet) ➔ 4-Page Power BI Report
```

* Modeled 9 raw CSVs (about 100K orders) into a 3NF MySQL database, then a **7-table star schema** (5 dimensions, 2 facts) in Parquet feeding a 4-page Power BI report.
* Wrote analytical SQL with CTEs and window functions (LAG, ROW_NUMBER, SUM OVER) for MoM growth, cohort retention, Pareto analysis and delivery performance.
* **Findings:** late deliveries cut average review scores from 4.29 to 1.70; the top 17.65% of sellers generate about 80% of revenue; repeat buyers spend 91.3% more over their lifetime.
* Separated `customer_id` from `customer_unique_id` to recover 3,217 repeat purchases; wrote 19 pytest tests for the cleaning package.

**Skills Used:**

* SQL (MySQL; CTEs, window functions, views), star-schema modeling
* Python, Pandas, PyArrow, pytest
* Power BI, DAX, Power Query, EDA

---

#### 3. 📱 [SmartPulse – Mobile Phone Data Intelligence Platform](https://github.com/ShaikhHamza104/SmartPulse)

```text
Smartprix Listings ➔ Selenium Scraping ➔ Cleaning Module ➔ Analytics ➔ Docker Image
```

* Built a scraping and analytics pipeline collecting **500+ smartphone listings** from Smartprix, with retry logic and automatic pagination.
* Wrote a cleaning module to standardize prices and specs and remove duplicates.
* Containerized the app with Docker and published the image to Docker Hub.

**Skills Used:**

* Python, Selenium, BeautifulSoup, Pandas
* Plotly, data cleaning, web scraping
* Docker, Docker Hub

---

### 💼 Experience

**Software Engineering Intern** | TechStalwarts Software Development LLP | *June 2023 – July 2023*

* Built Python data ingestion components for backend data workflows.
* Improved FastAPI endpoints used to serve data.
* Added ETL validation checks to catch bad records before loading.

---

### 🎓 Education

* **BSc Information Technology**, Vidyalankar School of Information Technology (VSIT), Mumbai | Currently pursuing | SGPA: 8.6
* **Diploma in AIARKP**
* **Certification:** Data Science Mentorship Program, CampusX (in progress)

---

### 📬 Connect

* **Email:** [kmohdhamza10@gmail.com](mailto:kmohdhamza10@gmail.com)
* **LinkedIn:** [linkedin.com/in/hamza-shaikh-data](https://www.linkedin.com/in/hamza-shaikh-data/)
* **GitHub:** [github.com/ShaikhHamza104](https://github.com/ShaikhHamza104)
