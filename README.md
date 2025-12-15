# 📊 SQL Exploratory Data Analysis Projects  

This repository contains **four end-to-end SQL-driven Exploratory Data Analysis (EDA) projects**, each showcasing the integration of **Python, Pandas, and SQL (SQLite + ipython-sql)** to analyze diverse datasets.  

The projects demonstrate skills in:  
- Data cleaning and preprocessing with **Pandas**  
- Database creation and management with **SQLite**  
- Writing and optimizing **SQL queries** for insights  
- Combining SQL with Python for reproducible analytics  

---

## 🚀 Projects Overview  

| Project | Dataset | Key Focus | Skills Demonstrated |
|---------|---------|-----------|----------------------|
| **Meta Stock Price Analytics** | 10 years of Meta stock price & technical indicators | Time-series analysis, RSI, SMA, EMA, CCI | Window functions, recursive queries, financial indicators |
| **Home Loan Status Analysis** | Historical loan application dataset | Loan approval factors, demographics, credit history | Aggregations, joins, proportions, categorical analysis |
| **COVID-19 Global Data Analysis** | Worldwide COVID-19 cases & deaths | Continent-level trends, death percentages, top countries | Grouping, ranking, percentage calculations, comparative analysis |
| **Beauty Supply Chain Analytics** | Supply chain dataset (skincare, haircare, cosmetics) | Procurement, production, logistics, defect rates | Multi-table queries, supplier analysis, KPI calculations |

---

## 🛠️ Tech Stack  

- **Python 3.10**  
- **Pandas** for data manipulation  
- **SQLite** for database management  
- **SQLAlchemy** for database connectivity  
- **ipython-sql** for running SQL queries inside Jupyter Notebooks  

---

## 📂 Repository Structure  
```
eda_SQL-kaggle-projects/ 
│ 
├── Meta Stock Price.ipynb 
├── Home Loans.ipynb 
├── Covid-19 EDA.ipynb 
├── Beauty Supply Chain Analytics.ipynb 
└── README.md <-- (this file)
```
---
## 📈 Highlights  

- **Meta Stock Price**:  
  - Calculated yearly average closing prices  
  - Derived RSI (7-day & 14-day), SMA, EMA, CCI  
  - Identified highest/lowest trading days  

- **Home Loans**:  
  - Explored loan approval distribution by gender, education, property area  
  - Analyzed impact of credit history & employment status  
  - Computed approval rates by dependents  

- **COVID-19**:  
  - Summarized cases & deaths by continent  
  - Ranked countries by cases/deaths per million  
  - Compared death percentages across continents  

- **Supply Chain**:  
  - Revenue analysis by product type  
  - Supplier defect rate comparisons  
  - Logistics insights: shipping costs, carriers, transportation modes  

---

## 🎯 Skills Showcased  

- **SQL Window Functions**: `ROW_NUMBER()`, `RANK()`, `LAG()`, `LEAD()`  
- **Aggregations**: `SUM()`, `AVG()`, `MAX()`, `MIN()`  
- **CTEs & Recursive Queries** for advanced analytics  
- **Data Cleaning**: handling missing values, renaming columns, standardization  
- **Business Insights**: translating raw data into actionable findings  

---

## 📌 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/mcadriaans/eda_SQL-kaggle-projects.git
   cd eda_SQL-kaggle-project
   ```

2. Install dependencies:
```bash
   pip install pandas sqlalchemy ipython-sql
  ```

🏆 Conclusion
These projects highlight the power of SQL in data exploration when combined with Python. They demonstrate practical applications across finance, housing, healthcare, and supply chain domains, showcasing versatility and strong analytical skills.
