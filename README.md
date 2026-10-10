# 🚚 FMCG Supply Chain Analytics & Performance Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

## 🔗 Live Interactive Dashboard
👉 **[Click Here to View the Live Interactive Power BI Dashboard](<iframe title="FMCG_Project" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiZTMwNjMxODItMWFlMS00MTBlLTg2ZDQtMzc0OTIxZGMwYWRjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" frameborder="0" allowFullScreen="true"></iframe>)**

---

## 📌 Project Overview
AtliQ Supply Chain is facing delivery SLA breaches across major retail customers in the Gujarat region. This project provides end-to-end supply chain visibility by combining **SQL-based backend analytics** with an **interactive Power BI dashboard**.

The objective is to track key delivery metrics, identify fulfillment gaps, tier customers based on volume, and analyze lead time bottlenecks to improve overall customer satisfaction.

---

## 🎯 Key Performance Indicators (KPIs) Tracked
* **OTIF% (On-Time In-Full):** Combined percentage of orders delivered both on time and in full.
* **OT% & IF%:** Individual tracking for On-Time delivery and In-Full delivery rate.
* **LIFR (Line Item Fill Rate):** Percentage of ordered item lines delivered successfully.
* **VOFR (Volume Order Fill Rate):** Percentage of total order quantity delivered.
* **SLA Target Gap:** The variance between actual performance and agreed-upon customer service levels.

---

## 💡 Analytical Framework & SQL Analysis
The project evaluates 8 core business questions using SQL (`JOIN`s, `CASE` statements, `WINDOW` functions, and aggregated logic):

1. **Overall OTIF Target vs. Actual Variance**
2. **Customer Tiering & Segmentation** (Categorized by volume scale)
3. **Product Shortfall Analysis** (Identifying high-demand items causing delivery delay)
4. **Order-Line & Volume Fill Rates (LIFR vs. VOFR)**
5. **City-Wise Delivery SLA Performance**
6. **Delivery Lead Time & Delay Distribution**
7. **Customer-Specific Service Level Agreements**
8. **Monthly & Weekly Trend Analysis**

*(All SQL queries are available in the [`SQL_Analysis/`](./SQL_Analysis) folder).*

---

## 📸 Dashboard Preview

### 1. Executive Summary
![Executive Dashboard](<img width="1810" height="941" alt="image" src="https://github.com/user-attachments/assets/fd129950-6b93-4aa2-931a-cdb817b3764e" />
)

### 2. Customer & Order-Line Analysis
![Customer Dashboard](<img width="1805" height="945" alt="image" src="https://github.com/user-attachments/assets/8f448683-80b7-4902-9693-1ce2dfc8260e" />
)
### 3. Product Analysis
 <img width="1770" height="940" alt="image" src="https://github.com/user-attachments/assets/92eedd53-a0bf-414c-84c8-a05135997b92" />

### 4. Delivery delay and lead time Analysis
  <img width="1797" height="951" alt="image" src="https://github.com/user-attachments/assets/533584ee-314e-43f2-acde-9200040c8814" />

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop & Service:** Data modelling, DAX measures, Sync Slicers, Bookmarks, UI design.
* **SQL (MySQL):** Advanced data extractions and transformations.
* **Excel:** Primary data validation and checks.

---

## 🚀 How to Run Local Project

1. Clone this repository:
   ```bash
   git clone [https://github.com/farhan0111xx/fmcg-supply-chain-analytics.git](https://github.com/farhan0111xx/fmcg-supply-chain-analytics.git)
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/fmcg-supply-chain-analytics.git](https://github.com/YOUR_USERNAME/fmcg-supply-chain-analytics.git)
