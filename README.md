# E-Commerce Executive Performance & Customer Retention Dashboard

## Project Overview
This project transforms raw transactional data into an executive-ready dashboard. It analyzes real transactional data from a UK-based online retailer. The main goal is to provide a single source of truth for your business, allowing you to monitor financial health and customer loyalty in real time.

---

## The Business Problem
Many e-commerce business owners struggle with messy daily data. You might face these three specific problems:
* **Untracked Financial Leaks:** Difficulty calculating net losses from returns because sales and refunds are mixed together.
* **Zero Visibility on Customer Loyalty:** Not knowing if your customers buy once and leave, or if they return to buy again.
* **Poor Marketing Budget Allocation:** Difficulty identifying the most profitable countries to optimize ad campaigns.

---

## The Solution
To solve these challenges, I built an end-to-end data pipeline and visualization system:

* **Data Cleaning & Engineering:** I separated successful sales from returned items using Power Query. This prevents negative numbers from distorting total revenue.
* **Solid Data Modeling:** I established a robust star-schema relational model and wrote custom DAX formulas to calculate Gross Revenue, Total Refunded, and Net Revenue dynamically.
* **Advanced Cohort Analysis:** I engineered a custom Customer Retention Cohort Matrix to track user behavior and retention rates based on their first purchase date.
* **UI/UX Design:** I designed a clean, modern dashboard layout with a collapsible filter panel to maximize screen space and applied automatic color gradients for instant readability.

<img width="1273" height="716" alt="Dashboard" src="https://github.com/user-attachments/assets/763f545a-9412-45d1-8223-3882bd775497" />

---

## Business Insights Delivered
This dashboard turns raw data into strategic business decisions:
* **Product Evaluation:** Instantly identify which products generate the highest net revenue.
* **Return Cost Efficiency:** Track exact financial losses from refunds, helping your operations team fix product quality issues.
* **Market Stability:** Highlight your primary revenue driver and identify high-performing regional markets.
* **Loyalty Analysis:** Use the cohort matrix to see exactly which customer groups remain loyal over time and when they typically stop buying.

---

## The Value I Bring to Your Business
* **Financial Clarity:** See exactly where you lose money from returned goods so you can improve your net profit margins.
* **Time Efficiency:** Understand your store's overall health in five seconds with an executive-ready layout.
* **Data-Driven Retention Strategy:** Allow your marketing team to detect customer churn points and launch targeted campaigns at the exact right time.
* **Scalability:** Transform messy raw data into a corporate-standard visualization that grows with your business.

---

## Tech Stack Used
* **BI Tool:** Power BI
* **Data Transformation:** Power Query
* **Calculations:** DAX (Data Analysis Expressions)
* **Data Source:** Excel / CSV Transactional Data
