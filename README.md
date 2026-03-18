<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:01080e,40:0d1b2a,70:4682b4,100:01080e&height=220&section=header&text=E-Commerce%20Sales%20Intelligence&fontSize=45&fontColor=ffffff&fontAlignY=35&desc=%F0%9F%9B%92%20Python%20+%20MySQL%20%E2%80%A2%20Relational%20ETL%20%E2%80%A2%20Retention%20Analytics&descSize=18&descAlignY=60&descColor=a9d6e5&animation=fadeIn" />

![GitHub Repo Size](https://img.shields.io/github/repo-size/mayurlokmanwar-analyst/E-Commerce-Sales-Customer-Behavior-Analysis-using-MySQL-Python?color=4682b4&style=for-the-badge)
![GitHub Last Commit](https://img.shields.io/github/last-commit/mayurlokmanwar-analyst/E-Commerce-Sales-Customer-Behavior-Analysis-using-MySQL-Python?color=a9d6e5&style=for-the-badge)
<br/>

[📊 View Full Python Notebook](https://github.com/mayurlokmanwar-analyst/E-Commerce-Sales-Customer-Behavior-Analysis-using-MySQL-Python/blob/main/MySQL+Python_E-commerce_Project.ipynb)

</div>

---

## 🚀 Strategic Overview
This project showcases a complete analytical lifecycle: transforming **100,000+ raw transactional records** into structured business intelligence. By migrating flat CSV data into a **MySQL Relational Schema**, the analysis uncovers critical trends in customer retention, regional market dominance (São Paulo/Rio), and the impact of installment-based payment strategies on total revenue.

### 🎯 Key Analytical Pillars
| **Module** | **KPIs & Analytical Focus** |
| :--- | :--- |
| **Market Density** | Pinpointing the Top 10 cities and states by customer concentration. |
| **Sales Velocity** | Monitoring order counts and monthly trends across 2017-2018. |
| **Payment Logic** | Analyzing the percentage and revenue impact of installment payments. |
| **Retention & Loyalty** | Measuring 6-month repeat purchase rates and VIP customer ranking. |

---

## 🛠️ Technical Architecture

<div align="center">

| **Phase** | **Technology** | **Implementation Details** |
| :--- | :--- | :--- |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | Built a Relational Schema joining 7 core e-commerce tables. |
| **ETL Pipeline** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Automated data migration using `mysql.connector` and `Pandas`. |
| **Analytics** | ![SQL](https://img.shields.io/badge/SQL-Advanced_Queries-orange?style=flat-square) | Applied CTEs, Window Functions (`DENSE_RANK`), and Joins. |
| **Viz Engine** | ![Seaborn](https://img.shields.io/badge/Viz-Seaborn_&_Matplotlib-blue?style=flat-square) | Generated statistical charts to visualize distribution and growth. |

</div>

---

## 💡 Strategic Business Insights
* **Regional Concentration:** **São Paulo (SP)** and **Rio de Janeiro (RJ)** are the primary revenue hubs, with São Paulo holding the highest customer density across the dataset.
* **Payment Flexibility:** Over **30% of all transactions** utilize installments, indicating that flexible payment options are a major driver for conversion on the platform.
* **Product Mix:** High-velocity categories such as **Health/Beauty** and **Bed Table Bath** consistently outperform other segments in both order count and total revenue.
* **Customer Retention:** Successfully identified the "Loyalty Segment"—customers who make a secondary purchase within a **6-month window** of their first order.
* **VIP Performance:** Utilized `DENSE_RANK` to isolate and rank the top 3 highest-spending customers per year, providing a list for targeted loyalty campaigns.

---

## 📁 Repository Structure
```text
E-Commerce-Behavior-Analysis/
├── 📂 Data/                    # Raw CSV Datasets (Customers, Orders, Products, etc.)
├── 📄 MySQL Queries Required.sql # Professional SQL script with complex KPIs
├── 📄 MySQL+Python_Project.ipynb # Full ETL, Analysis, and Visualization Notebook
├── 📄 Analysis_Report.pdf      # Executive summary of technical and business findings
└── 📄 README.md                # Project Documentation
