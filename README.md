# 🛒 FMCG Financial Intelligence & Sales Analytics
**An End-to-End Data Engineering & BI Solution for Global Retail Operations**

---

## 📌 Executive Summary for Hiring Managers
I developed a comprehensive data pipeline utilizing **Excel, Python, SQL, and Power BI** to transform raw retail data into a **"Single Source of Truth"** for global operations. 

My workflow involved:
1.  **Excel:** Initial data auditing and structural integrity checks of 1,000+ raw records.
2.  **Python:** Automated ETL (Extract, Transform, Load) to clean data and normalize multi-regional currencies.
3.  **SQL:** Engineering a relational Star-Schema to bridge sales, payroll, and material costs.
4.  **Power BI:** Developing an interactive executive suite to identify a **4.27M revenue driver** and pinpoint profit erosion.

---

## 📊 1. Final Executive Dashboard (Power BI)
![Final Dashboard Preview](images/Dashboard.png)
* **Value Added:** Created high-level KPIs in **Power BI** to provide real-time visibility into Gross Sales and Net Margins across **Pakistan, UAE, and Malaysia**.

---

## 📉 2. Initial Data Auditing (Excel & Raw Data)
![Raw Data Interface](images/RawData.png)
* **Technical Action:** Conducted a deep-dive audit of the source `Global_Automotive_Analytics_1000_Records.xlsx` file.
* **Value Added:** Identified critical inconsistencies in currency symbols and unformatted string values that required automated cleaning.

---

## 🐍 3. Automated ETL & Cleaning (Python)
![Python ETL Process](images/pyhton script.png)
* **Technical Action:** Developed a **Python** script (Pandas/NumPy) to automate the cleaning of the raw exports shown above.
* **Value Added:** Handled complex string manipulation and currency normalization, ensuring **100% audit-ready financial accuracy**.

---

## 🗄️ 4. Relational Database Migration (SQL)
![SQL Schema and Queries](images/SQL_q.png)
* **Technical Action:** Successfully migrated cleaned data from Python into a **MySQL** relational database.
* **Value Added:** Engineered complex **SQL** joins to calculate true profitability by connecting sales transactions with manufacturing costs and employee overheads.

---

## 📈 5. SKU & Market Performance (Cleaned Data View)
![Cleaned Data Analysis](images/cleaneddata.png)
* **Technical Action:** Used **DAX** to create dynamic measures for Net Contribution analysis on the finalized dataset.
* **Value Added:** Isolated **Biscuits (UNL-BIS-105-PK)** as the top performer while flagging underperforming segments for strategic review.

---

## 🛠️ Technical Tech Stack
* **Initial Auditing:** Excel (Pivot Tables, Data Validation)
* **Data Engineering:** Python (Pandas, NumPy, Regex)
* **Database Management:** MySQL (Relational Modeling, Joins, Primary/Foreign Keys)
* **Business Intelligence:** Power BI (DAX, Interactive Filtering)
* **Data Volume:** 1,000+ Global Transactions

---


* `/sql`: Database schema and complex query scripts.
* `/images`: Documentation of the end-to-end workflow.
