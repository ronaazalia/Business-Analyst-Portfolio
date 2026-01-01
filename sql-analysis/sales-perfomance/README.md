# Sales Performance Analysis

This case demonstrates SQL-based analysis developed to support
business and operational decision-making related to sales performance.

The analysis focuses on evaluating actual sales against defined targets
at both sales representative and territory levels.

---

## Business Questions
- How does each sales representative perform against their target?
- Who are the top-performing sales representatives in January and February?
- How does sales performance aggregate at the territory level?
- Which territory generates the highest sales during the selected period?

---

## Analysis Scope
- Actual sales amount calculated from order quantity and unit price
- Sales performance evaluated by fiscal period (monthly)
- Target values maintained at the sales representative level
- Territory performance derived by aggregating sales representative targets
- Analysis focused on identifying top-performing sales representatives
  and highest-performing territories for selected periods

---

## Data Sources
This analysis is based on transactional and master data commonly used
in a manufacturing sales environment.

📄 **Table structure and relationships:**  
[View tables overview](sql-analysis/sales-perfomance/0_db_sales_performance.pdf)

---

## Analysis Logic (SQL)
The following SQL queries are used to answer the business questions:

1. **Sales achievement by sales representative**  
   [View SQL query](sql-analysis/sales-perfomance/1.0_sales_achv_by_salesrep.sql)

2. **Top-performing sales representatives by month**  
   [View SQL query](queries/top-performer-by-month.sql) placeholder

3. **Sales achievement by territory**  
   [View SQL query](sql-analysis/sales-perfomance/2.0_sales_achv_by_territory.sql)

---

## Results Summary
The summarized outputs generated from the analysis can be viewed here.
All results are anonymized and provided for illustration purposes only.

📊 **Sample results:**  
[View summarized table](sql-analysis/sales-perfomance/3.0_achv_result.pdf)

---

## Notes
This analysis uses dummy data for portfolio demonstration purposes.
The structure and logic reflect real-world business scenarios, but all values and identifiers are fictional.


