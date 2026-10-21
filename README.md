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

<img width="1867" height="954" alt="Screenshot 2026-10-21 181301" src="https://github.com/user-attachments/assets/a6cd629b-ef4f-422c-8654-7c38096ccb6c" />

<img width="1863" height="954" alt="Screenshot 2026-10-21 175604" src="https://github.com/user-attachments/assets/239f1f77-a4f5-4178-ba1c-21d0a51094f5" />

<img width="1861" height="951" alt="Screenshot 2026-10-21 175706" src="https://github.com/user-attachments/assets/18e4043e-2c6f-41d2-b810-fab4d27f357f" />

<img width="1861" height="940" alt="Screenshot 2026-10-21 175725" src="https://github.com/user-attachments/assets/c7666d99-ee94-40a2-a434-27e0349ca704" />

<img width="1864" height="951" alt="Screenshot 2026-10-21 175744" src="https://github.com/user-attachments/assets/76b0b90d-4c57-49e9-a8f6-06f616d5202b" />



