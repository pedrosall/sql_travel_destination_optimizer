# ✈️ VIP Travel Optimization: SQL-Driven Destination Finder

> **Relational Database & Analytics Project** applying advanced SQL querying and multi-criteria filtering to determine the optimal, high-privacy beach destination for a high-profile celebrity and their family.

---

## 🛠️ Tech Stack & Tools

![SQL](https://img.shields.io/badge/SQL-003B5C?style=for-the-badge&logo=database&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

---

## 🎯 Project Objective

The goal of this project is to model and query a relational database to solve a complex decision-making problem: selecting the perfect holiday destination for a world-famous singer. The solution requires balancing highly specific, non-negotiable constraints:
1. **Maximum Privacy:** Low tourist density and low media footprint to ensure the family goes completely unnoticed.
2. **Geographic Constraints:** Immediate proximity to premium beach/coastal areas.
3. **Family Infrastructure:** Safety, luxury accommodation metrics, and accessibility features.

---

## 📊 Dataset & Architecture

* **Source:** Private relational datasets structured for Master's degree analytical modules.
* **Content:** Raw and processed tables including global destination metrics, tourism density indices, climate history, and geographical classifications.

---

## ⚙️ Database Methodology

The analysis is structured within a Jupyter Notebook using a Python-to-SQL connection workflow, following these database engineering phases:

1. **Connection Parameters:** Establishing a secure connection pipeline between the Python runtime environment and the SQL database engine.
2. **Database Schema Design:** Mapping the entity-relationship model (ERD) to understand constraints, primary keys, and foreign key alignments across destination and privacy tables.
3. **Table Creation & DDL:** Writing clean Data Definition Language (DDL) scripts to initialize schemas, define data types, and enforce structural integrity.
4. **Analytical Queries (DML):** Developing multi-table `JOIN` statements, nested subqueries, CTEs (Common Table Expressions), and conditional logic (`CASE WHEN`) to score and rank locations based on the celebrity's profile.
5. **Key Insights & Notes:** Extracting the top 3 optimal destinations that successfully satisfied 100% of the rigorous anonymity and geographical criteria.

---

## 📦 Repository Deliverables

* 📁 `notebooks/` - Jupyter Notebook containing the full database setup, connection strings, SQL scripts, and markdown documentation of the final decision matrix.
* 📁 `sql/` - (Optional/If applicable) Raw `.sql` scripts with schema definitions and analytical queries.

---

## 🚀 How to Run

1. Clone this repository to your local machine:
```bash
   git clone [https://github.com/pedrosall/your-new-repo-name.git](https://github.com/pedrosall/your-new-repo-name.git)
