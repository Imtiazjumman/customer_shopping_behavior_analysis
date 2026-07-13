# Customer Shopping Behavior Analysis

An end-to-end data analytics project aimed at understanding customer purchasing patterns to drive sales growth, enhance customer satisfaction, and improve long-term brand loyalty for a leading retail company.

## 📌 Project Overview
This project addresses a critical business problem: **How can a retail organization leverage customer transactional data to optimize marketing, product assortment, and customer retention strategies?** By executing a full data pipeline—covering data preprocessing, exploratory data analysis (EDA), database modeling, SQL querying, and interactive business intelligence dashboarding—this project transforms raw consumer data into highly actionable strategic recommendations.

---

## 🛠️ Project Architecture & Deliverables
The project is executed across the following stages:
1. **Data Preparation & Engineering (Python):** Data cleaning, missing value handling, feature engineering, and demographic segmentations (e.g., age-group bucketing).
2. **Data Analysis & Querying (SQL):** Structuring the data into relational tables, simulating transactions, and executing advanced analytical queries to uncover core customer behaviors.
3. **Data Visualization (Power BI):** Developing an interactive executive dashboard highlighting key performance indicators (KPIs), demographics, and seasonal trends.
4. **Business Strategy & Reporting:** Translating data-driven insights into high-impact operational recommendations for executive leadership.

---

## 📊 Key Insights from the Data
* **Total Performance:** The dataset spans **3,900 unique customer transactions**, generating a total revenue of **$233,081** with an average order value (AOV) of **$59.76**.
* **The Gender Gap:** Male consumers represent the primary driver of revenue, accounting for **$157,890 (~67.7%)** compared to **$75,191 (~32.3%)** from female consumers.
* **Category Dominance:** **Clothing** is the highest-performing category by a wide margin ($104,264 revenue across 1,737 items), followed by **Accessories** ($74,200). **Footwear** ($36,093) and **Outerwear** ($18,524) remain heavily underutilized.
* **Customer Satisfaction:** The average customer review rating sits at a mediocre **3.75 / 5.00**, indicating a critical pain point that directly impacts the company's customer retention rates.
* **Seasonality vs. Loyalty:** While **Fall** generates the highest quarterly revenue ($60,018), **Winter and Spring** see the highest volume of repeat purchases from existing loyalty members.

---

## 📂 Repository Structure
```text
├── Data/
│   └── customer_shopping_behavior.csv    # Cleaned & processed source dataset
├── Notebooks/
│   └── Behavior_Analysis.ipynb          # Jupyter Notebook containing Python EDA & Prep
├── SQL/
│   └── analysis_queries.sql             # SQL scripts for data segmentations & KPIs
├── Dashboard/
│   └── Shopping_Behavior_Dashboard.pbix # Power BI Dashboard file
├── Documents/
│   └── Business Problem Document.pdf    # Original project guidelines and scope
└── README.md                            # Project documentation
