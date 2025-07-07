# 📱 SQL Case Study: Mobile Manufacturer Data Analysis

This repository presents a SQL-based data analysis project simulating a cellphone sales database. Created as part of the AnalytixLabs Advanced SQL case study, it models a relational schema from scratch and answers key business questions using SQL techniques such as joins, aggregations, filtering, window functions, and subqueries.

---

### 🧾 Case Overview

> **Business Scenario**  
> A  database named **"Cellphones Information"** holds data on sales transactions, manufacturers, models, customers, and geographical locations.  
> The case study is performed on manually created tables that simulate transactional data for mobile device purchases.

---

### 🗃️ Database Schema Summary

| Dimension Table       | Description                                         |
|-----------------------|-----------------------------------------------------|
| `DIM_MANUFACTURER`    | Manufacturer ID and names                           |
| `DIM_MODEL`           | Model info, unit price, manufacturer reference      |
| `DIM_CUSTOMER`        | Customer details (name, email, phone)              |
| `DIM_LOCATION`        | Zip, city, state, country info                      |
| `DIM_DATE`            | Dates with Year, Quarter, Month breakdowns         |
| `FACT_TRANSACTIONS`   | Sales records linking all dimensions                |

---

### 🧠 Project Objectives

> 🔍 Write SQL queries to solve advanced business problems such as:
- **Customer location analysis** between 2005–present
- **Top Samsung sales states in the US**
- **Transaction count per model, per zip code, per state**
- **Cheapest mobile phone identification**
- **Top 5 manufacturers by sales quantity + average model price**
- **Customers with high average spend in 2009**
- **Models ranking consistently in top 5 across 2008–2010**
- **Second highest selling manufacturer (2009 and 2010)**
- **Manufacturers active in 2010 but inactive in 2009**
- **Top 100 customers by year with % change in spend and quantity**

---

### 💼 Skills Applied

| Concepts Used          | Techniques                                 |
|------------------------|--------------------------------------------|
| SQL Joins              | INNER, LEFT, FULL JOINs                    |
| Aggregations           | COUNT, SUM, AVG                           |
| Window Functions       | RANK, DENSE_RANK                          |
| Filtering & Subqueries | WHERE, HAVING, IN, EXISTS                 |
| Date Functions         | YEAR(), MONTH(), DATEPART()               |
| Grouping & Partition   | GROUP BY, PARTITION BY                    |

---

### 📁 Folder Structure

- 📂 `Schema Creation/` — SQL scripts to define all required tables and relationships
- 📄 `Mobile manufacturer data analysis_ATM.pdf` — Case overview and instructions
- 📑 `README.md` — Project summary and explanation (this file)

---

### 👩‍💻 Author

**Surbhi** — Data Analyst at TechnoData Analytics  
Crafting real-time dashboards, automating insights, and delivering storytelling through SQL, Power BI, Excel, and Python.

🔗 [LinkedIn](www.linkedin.com/in/surbhi-995926161)  
🔗 [GitHub Portfolio](https://github.com/surbhigzb98)

---

### ⭐ How to Use

1. Download or clone the repo.
2. Review the schema design script to understand table creation logic.
3. Explore the `Mobile_Manufacturer_solution` for question-specific solutions.
4. Run queries in SQL Server Express or any RDBMS simulator.
   ![image](https://github.com/user-attachments/assets/b0168eb7-f7fe-4be8-ba86-1f7db7250f68)

---

### 📌 Highlights

- Simulates a realistic multi-dimensional SQL case study for interviews
- Demonstrates Surbhi’s ability to build schema from documentation
- Strong use of business reasoning and SQL logic to derive insights
- Great candidate showcase for BI/Data Analyst roles

---

> Feel free to star ⭐ the repository or share your suggestions!  
> This project is part of my journey to mastering SQL for real-world applications 💡📊
