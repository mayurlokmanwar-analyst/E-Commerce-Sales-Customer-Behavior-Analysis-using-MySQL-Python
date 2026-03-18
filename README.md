<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:01080e,40:0d1b2a,70:4682b4,100:01080e&height=220&section=header&text=E-Commerce%20Sales%20Intelligence&fontSize=45&fontColor=ffffff&fontAlignY=35&desc=%F0%9F%9B%92%20Python%20+%20MySQL%20%E2%80%A2%20Retention%20Analytics%20%E2%80%A2%20Customer%20Behavior&descSize=18&descAlignY=60&descColor=a9d6e5&animation=fadeIn" />

![GitHub Repo Size](https://img.shields.io/github/repo-size/mayurlokmanwar-analyst/E-Commerce-Sales-Customer-Behavior-Analysis?color=4682b4&style=for-the-badge)
![GitHub Last Commit](https://img.shields.io/github/last-commit/mayurlokmanwar-analyst/E-Commerce-Sales-Customer-Behavior-Analysis?color=a9d6e5&style=for-the-badge)
<br/>

[📊 View Python Notebook](https://github.com/mayurlokmanwar-analyst/E-Commerce-Sales-Customer-Behavior-Analysis/blob/main/MySQL+Python_E-commerce_Project.ipynb)

</div>

---

## 🚀 Strategic Overview
This project bridges the gap between raw transactional data and executive-level decision-making. By building an automated pipeline to import **100,000+ records** into a structured **MySQL** environment, this analysis identifies high-growth customer cities, tracks monthly sales velocity, and calculates complex metrics like **Customer Retention Rate** and **Revenue Contribution by Category**.

### 🎯 Key Analytical Pillars
| **Module** | **KPIs & Analytical Focus** |
| :--- | :--- |
| **Market Concentration** | Identifying Top 10 cities and states by customer density. |
| **Sales Velocity** | Monthly and yearly order trends (focused on 2017-2018 performance). |
| **Financial Health** | Revenue analysis by product category and installment payment behavior. |
| **Customer Loyalty** | Calculating retention rates and identifying top-tier VIP spenders. |

---

## 🛠️ Technical Architecture

<div align="center">

| **Phase** | **Technology** | **Implementation Details** |
| :--- | :--- | :--- |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | Relational Schema across 7 tables (Customers, Orders, etc.). |
| **Data Pipeline** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Automated ETL using `mysql.connector` and `Pandas`. |
| **Analytics** | ![SQL](https://img.shields.io/badge/SQL-Advanced_Queries-orange?style=flat-square) | Complex Joins, CTEs, and Window Functions for ranking. |
| **Visualization** | ![Matplotlib](https://img.shields.io/badge/Viz-Seaborn_&_Matplotlib-blue?style=flat-square) | Dynamic bar charts and line graphs for trend analysis. |

</div>

---

## 📸 Project Preview
*Visualizing regional distribution and high-value customer spending patterns.*

<div align="center">
  <img src="https://raw.githubusercontent.com/mayurlokmanwar-analyst/E-Commerce-Sales-Customer-Behavior-Analysis/main/E-Commerce%20Sales%20&%20Customer%20Behavior%20Analysis%20Dashboard.png" alt="E-Commerce Analysis Dashboard Preview" width="900" style="border-radius: 10px; border: 2px solid #1b263b;">
</div>

---

## 💡 Strategic Business Insights
* **Urban Hubs:** **São Paulo (SP)** and **Rio de Janeiro (RJ)** dominate the market, with São Paulo holding the highest customer concentration by a significant margin.
* **Category Revenue:** High-grossing categories like **Bed Table Bath** and **Health/Beauty** drive the bulk of the platform's revenue.
* **Payment Behavior:** Over **30% of orders** utilize installment plans, indicating a consumer preference for flexible payment options on higher-value items.
* **Retention Metric:** Identified a core segment of repeat buyers, with a detailed analysis of customers who make follow-up purchases within a **6-month window**.
* **High-Value Spenders:** Used Window Functions (`DENSE_RANK`) to isolate the top 3 spending customers per year for targeted VIP loyalty programs.

---

## 📁 Repository Structure
```text
E-Commerce-Behavior-Analysis/
├── 📂 Data/                    # Raw CSV files (Customers, Orders, Payments, etc.)
├── 📄 MySQL Queries Required.sql # Optimized SQL script for analytical KPIs
├── 📄 MySQL+Python_Project.ipynb # Full ETL and Visualization Notebook
├── 📄 Analysis_Report.pdf      # Executive summary and technical findings
└── 📄 README.md                # Project Documentation
