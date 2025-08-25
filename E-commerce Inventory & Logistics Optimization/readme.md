# Optimizing E-commerce Operations: An Inventory & Logistics Analysis

## 🚀 Project Overview

This project is a comprehensive analysis of the Olist E-commerce dataset, designed to simulate a real-world business intelligence scenario. The goal is to tackle critical challenges in inventory management and logistics to improve operational efficiency and customer satisfaction for a fictional e-commerce marketplace, "SwiftShip."

Following my motto, "Converting raw data into valuable insights," this project transforms nearly 100,000 order records into a strategic command center, providing actionable recommendations to drive business growth.

---

## 🏢 Business Problem

"SwiftShip," a large Brazilian e-commerce marketplace, is facing two major challenges that threaten its growth and profitability:

1.  **Inventory Imbalance:** Customers frequently complain about popular products being out of stock, leading to lost sales. Simultaneously, warehouse costs are rising due to overstocking of slow-moving, unpopular items.
2.  **Inconsistent Delivery:** Delivery times are highly variable and often fail to meet estimates, causing a drop in customer satisfaction and an increase in support inquiries.

This project's objective is to analyze historical sales, product, and shipping data to diagnose the root causes of these problems and provide data-driven solutions.

---

## 🛠️ Tech Stack

* **Data Storage:** **PostgreSQL** for robust data management and complex querying.
* **Data Analysis & EDA:** **Python** (Libraries: Pandas for data manipulation, Matplotlib & Seaborn for initial visualizations).
* **Business Intelligence & Visualization:** **Power BI** for creating a comprehensive, interactive 4-page dashboard.
* **DAX (Data Analysis Expressions):** Used within Power BI to create advanced calculations and KPIs.

---

## 📊 The Dashboard: A 4-Page Command Center

The final output is an interactive 4-page Power BI dashboard designed for different stakeholders within the "SwiftShip" organization.

**(Pro Tip: Create a GIF of you clicking through your dashboard and replace the placeholder below. You can use a free tool like ScreenToGif.)**



### [➡️ Click here to view the Live Interactive Dashboard](https://app.powerbi.com/groups/me/reports/afb336b6-52a5-4ab3-b628-d81cc24810f5/64e56974877e07a935b1?experience=power-bi)

**The dashboard consists of four dedicated pages:**
1.  **Executive KPI Overview :** A high-level summary of business health, focusing on revenue, orders, and overall performance.
2.  **Inventory Optimization Deep Dive :** A toolkit for inventory managers to identify high-value products, "dead stock," and regional demand patterns using ABC analysis and other techniques.
3.  **Logistics Performance Analysis :** A diagnostic page for the logistics team to pinpoint the root causes of delays, whether from seller processing or carrier shipping.
4.  **Seller Performance Scorecard :** A management tool to rank, classify, and manage marketplace sellers to improve overall quality and reliability.

---

## 📈 Key Insights & Recommendations

This analysis yielded three critical, actionable insights:

| Insight                                                                                                         | Recommendation                                                                                                                                | Expected Impact                                                                                                    |
| --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| **1. Severe Inventory Imbalance:** 15% of product categories ("Category A") drive 80% of revenue, while 50% ("Category C") contribute less than 5%, representing significant "at-risk" stock. | **Implement an ABC Stocking Policy.** Prioritize stock for "Category A" items and drastically reduce inventory for the bottom 20% of "Category C" items. | Free up significant capital, reduce storage costs, and minimize stockouts of high-demand products.                   |
| **2. Dual Logistics Bottlenecks:** Delivery delays are not a single problem. Some regions suffer from slow **seller processing**, while others are plagued by inefficient **carrier shipping**. | **Launch a Seller Scorecard & Optimize Routes.** Incentivize fast seller fulfillment (<48h). Use data to renegotiate with carriers on the top 5 most problematic shipping routes. | Reduce the overall late delivery rate by targeting the specific root cause in each region, improving customer trust. |
| **3. Late Deliveries Directly Impact Loyalty:** Customers who experience even one late delivery are significantly less likely to make a repeat purchase.                               | **Create a Proactive Customer Service Protocol.** For orders identified as "at-risk" of being late, proactively communicate with the customer and offer a small voucher. | Mitigate customer frustration, improve satisfaction scores, and increase the customer retention rate.              |

---

## ⚙️ Project Workflow

1.  **Data Modeling & ETL:** Loaded 9 raw CSV files into a PostgreSQL database, establishing a robust relational schema.
2.  **Data Extraction:** Connected Power BI to the PostgreSQL database, importing the data via SQL queries.
3.  **Data Transformation & Analysis:**
    * Performed extensive data cleaning and preparation in Power Query.
    * Created over 50 advanced DAX measures and calculated columns to build KPIs for sales, logistics, inventory, and customer behavior.
4.  **Dashboarding & Visualization:** Designed and built the 4-page interactive dashboard, focusing on a clean UI and a clear narrative to guide users from high-level insights to granular details.

---

## 🚀 How to Reproduce

To reproduce this analysis, you will need to:
1.  Download the dataset from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
2.  Set up a PostgreSQL database and use the provided SQL scripts to create the schema and load the data.
3.  Open the `.pbix` file in Power BI Desktop and reconnect it to your local PostgreSQL database.

---

## 👨‍💻 Author

**Abhay Tiwari**

* LinkedIn: [Abhay Tiwari](https://www.linkedin.com/in/thekushak/)
* GitHub: [thekushak0003](https://github.com/thekushak0003/Abhay-Tiwari)

A 3rd-year undergraduate at NIT Allahabad, passionate about Data Science and Machine Learning. Actively seeking opportunities to apply my skills to solve meaningful, real-world problems.
