# 🛡️ LoanGuard-Analytics

A credit risk ETL pipeline that ingests public loan data, calculates risk metrics, and loads results into Snowflake — orchestrated with Apache Airflow and Docker.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | ETL logic and transformation |
| Apache Airflow | Pipeline orchestration |
| Snowflake | Cloud data warehouse |
| PostgreSQL | Airflow metadata database |
| Docker | Containerization |

---

## 📁 Project Structure

```
LoanGuard-Analytics/
├── dags/
│   └── loanguard_dag.py
├── logs/
├── plugins/
├── config/
├── .env
└── docker-compose.yml
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/LoanGuard-Analytics.git
cd LoanGuard-Analytics
cp .env.example .env        # Add your Snowflake credentials
docker compose up
```

Open Airflow at `http://localhost:8080` — default login: `airflow / airflow`

---

## 📊 Risk Metrics

- Debt-to-Income Ratio (DTI)
- Delinquency Flag
- Risk Tier (Low / Medium / High)
- Default Probability Score

---

## 👤 Author

**Jaime Manzueta** 
