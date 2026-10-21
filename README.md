# E-Commerce-Analytics-Dashboard
# 📝 Overview

A comprehensive Power BI & Excel project transforming raw e-commerce data (1M+ rows across 7 tables) into actionable business insights, tracking sales profitability, inventory turnover, and web conversion funnels[cite: 1, 4, 5, 9, 10, 11, 12].

* **Domain:** E-Commerce & Supply Chain Operations

---

### 🎬 Live Video Demonstration

[![WATCH PROJECT DEMO](https://img.shields.io/badge/WATCH_PROJECT_DEMO-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/zDgt921UFSU?si=0FG7qeVt0e_4pxpw)
* 📌 **Project Walkthrough:** A comprehensive video explaining the data pipeline, DAX measures, and interactive report functionality.

---

### 🛠️ Tools & Technologies

* **Data Prep & ETL:** Excel & Power Query
* **Data Modeling & Analysis:** Power Pivot (DAX)
* **Visualization:** Power Pivot & Excel (Interactive 4-page Dashboard)

---

### ✨ Key Highlights

* 🔄 **Integration & Data Pipeline:** Executed an end-to-end ETL process using Power Query to clean, transform, and structure 7 relational tables into an optimized star-schema model[cite: 1, 4, 5, 9, 10, 11, 12].
* 📐 **Advanced Analytics:** Developed complex DAX measures for actual gross profit (`actual_gross_profit`), AOV, inventory hold age, and a unique-session conversion funnel (`session_conversion_rate_pct`)[cite: 9, 10, 12, 16].
* 📊 **Multi-Page Interactive Reporting:**
  * **Page 1 - Executive Overview & Sales:** High-level executive KPI tracking, sales trend lines, and order fulfillment status breakdowns (`Complete`, `Cancelled`, `Returned`)[cite: 2, 3, 16, 18].
  * **Page 2 - Customer & Traffic Analytics:** Demographics breakdown (Age, Gender, Geography) paired with user acquisition channels and non-buying user analysis[cite: 5, 6, 8, 21].
  * **Page 3 - Product & Inventory Performance:** Category/Brand profitability matrix coupled with unsold stock valuation (`available_inventory_cost`) and warehouse turnover[cite: 9, 10, 11].
  * **Page 4 - Web Analytics & Conversion Funnel:** A 5-step conversion funnel (`home` $\rightarrow$ `department` $\rightarrow$ `product` $\rightarrow$ `cart` $\rightarrow$ `purchase`) with browser drop-off tracking[cite: 27].

---

### 🎯 Challenge & Solution

* 🔴 **Challenge:** High row volume (1M+ clickstream events) causing severe funnel shape distortions due to multiple product views within a single user session[cite: 12, 27].
* 🟢 **Solution:** Implemented **Unique Session Aggregation (`DISTINCTCOUNT(session_id)`)** across funnel stages to accurately model true user journeys without bias[cite: 27].

---

### 🖼️ Dashboard Screenshots

#### 1. Executive Overview & Sales
![Executive Overview](./assets/executive-overview.png)

#### 2. Customer & Traffic Analytics
![Customer Analytics](./assets/customer-analytics.png)

#### 3. Product & Inventory Performance
![Product Performance](./assets/product-inventory.png)

#### 4. Web Analytics & Conversion Funnel
![Web Analytics](./assets/web-analytics.png)
