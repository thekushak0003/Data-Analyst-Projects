# Strategic Customer Segmentation & Growth Analysis for E-commerce

![Python](https://img.shields.io/badge/Python-3.9%2B-%233776AB?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-%23150458?logo=pandas)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-%23F2C811?logo=powerbi)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-%23F37626?logo=jupyter)

---

## 🎯 Project Overview

This repository contains the end-to-end data analytics project focused on analyzing a large-scale e-commerce dataset to derive actionable business insights. The project moves beyond surface-level metrics to perform a deep dive into customer behavior, culminating in a strategic segmentation framework and an interactive Power BI dashboard designed for executive decision-making. The core objective is to translate raw transactional data into a clear roadmap for targeted marketing, enhanced customer retention, and sustainable business growth.

---

## 📝 Problem Statement

In the hyper-competitive e-commerce landscape, untargeted, mass-marketing strategies are inefficient and costly. To foster sustainable growth, businesses must achieve a nuanced, data-driven understanding of their customer base. This project tackles this challenge by answering key business questions:
* Who are our most valuable customers?
* What are the distinct purchasing behaviors and preferences of different customer groups?
* Which customers are at risk of churning?
* How can we create targeted, effective marketing campaigns to increase customer lifetime value?

---

## 📊 Dataset

The analysis was performed on a consolidated dataset created by merging two years of sales data from the **Online Retail II dataset**, sourced from the UCI Machine Learning Repository.

* **Source:** [UCI Machine Learning Repository: Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
* **Size:** Over 1 million transactional records.
* **Attributes:** `Invoice`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `Price`, `Customer ID`, `Country`.

---

## ⚙️ Project Workflow

The project followed a structured, end-to-end data analytics lifecycle:

1.  **Data Preparation & Strategic Imputation:**
    * Merged and consolidated two years of sales data.
    * Executed a strategic imputation of over **243,000 missing `Customer ID`s** by mapping them to unique `Invoice` numbers. This critical decision preserved valuable transactional data, preventing analytical bias and enabling a holistic view of business operations.
    * Cleaned the data by removing cancellations, invalid entries, and records with missing descriptions.
    * Engineered a `TotalPrice` feature to serve as the core revenue metric.

2.  **Exploratory Data Analysis (EDA):**
    * Performed in-depth temporal, geographic, and behavioral analysis to uncover the core rhythms of the business, including sales seasonality, peak shopping hours, and the balance between new and returning customers.
    * Conducted an ABC Analysis to categorize the product portfolio into "superstars," "workhorses," and "long-tail" items based on revenue contribution.

3.  **RFM Customer Segmentation:**
    * Applied the **RFM (Recency, Frequency, Monetary)** model to move from general trends to specific customer personas.
    * Calculated R, F, and M metrics for each customer and used quintile-based scoring to create six distinct, actionable segments: **Champions, Loyal Customers, Potential Loyalists, At-Risk Customers, Needs Attention,** and **Lost**.

4.  **Interactive Dashboarding in Power BI:**
    * Developed a dynamic, two-page Power BI dashboard to serve as a strategic decision-support tool for executive and marketing teams.
    * The dashboard visualizes all key findings and allows for interactive filtering and deep dives into specific customer segments.

---

## 💡 Key Insights

* **Pareto Principle Confirmed:** The top-tier customer segments ("Champions" and "Loyal Customers"), while a minority of the customer base, are the primary engine of profitability, generating over **75% of total revenue**.
* **Significant Churn Risk Identified:** A valuable **"At-Risk"** segment was isolated, comprising customers with a history of high-value purchases who have become dormant. This group represents the most immediate opportunity for revenue recovery.
* **Dual Business Model:** The sales data reveals a hybrid operational pattern: a B2B-like daily rhythm with sales peaking during midday business hours, combined with a strong B2C seasonal trend with a revenue spike in Q4.
* **International Opportunity:** While the UK is the dominant market, **international customers have a significantly higher Average Order Value (AOV)**, presenting a key opportunity for strategic growth.

---

## 📈 Power BI Dashboard Showcase

The final output is a two-page interactive dashboard designed to translate complex data into clear, actionable intelligence.

**Page 1: Executive Sales Overview**
*Provides a high-level summary of KPIs, sales trends over time, and geographic performance. Designed for quick, at-a-glance assessment of overall business health.*

**Page 2: Customer Segmentation Deep Dive**
*The strategic core of the project. This page allows users to interactively filter by RFM segment to see that group's specific metrics, top-purchased products, and most valuable customers, enabling the execution of targeted marketing campaigns.*


---

## 🚀 Strategic Recommendations

Based on the analysis, the primary recommendation is to shift from generic marketing to a data-driven, segment-based strategy:

* 👑 **Champions:** Reward with VIP loyalty programs and exclusive perks to amplify retention.
* 💖 **Loyal Customers:** Nurture and upsell with product bundles and personalized recommendations to increase their AOV.
* 😨 **At-Risk Customers:** Launch immediate, targeted "We Miss You!" campaigns with personalized discounts to prevent churn.

---


## 👨‍💻 Author

* **Abhay Tiwari**
* **LinkedIn:** [My Profile](https://www.linkedin.com/in/thekushak/)
* **Motto:** "Converting raw data into valuable insights."
