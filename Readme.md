# Supply Chain Performance & Predictive Analytics 📦🚛

This repository contains an end-to-end Data Science project focused on analyzing global supply chain inefficiencies and building a predictive engine to mitigate delivery risks

## 📌 Project Overview
The core objective of this project is to address a critical operational failure: a **54.83% late delivery rate**. By analyzing a real-world dataset of 180,519 records across 53 variables, I performed comprehensive data cleaning, feature engineering, and predictive modeling to identify bottlenecks and forecast future delays

## 📂 Repository Contents
* `DataCo_SupplyChain_Analysis.ipynb`: The primary Jupyter Notebook containing the full technical workflow: data cleaning, EDA, visualization, and machine learning.
* `Supply_Chain_Analysis_Final.csv`: The cleaned and processed dataset optimized for dashboarding and high-performance analysis.
* `README.md`: Project documentation and executive summary.

## 🛠️ Technical Stack
* **Languages:** Python 🐍
* **Data Wrangling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn, Plotly
* **Machine Learning:** Scikit-Learn
* **Dashboarding:** Panel

## 📊 Visual Insights & Business Impact

### 1. Identifying Operational Bottlenecks
* **Visual:** Bar Chart of Top 10 High-Risk Categories
* **Impact:** Discovered that logistics failures are concentrated in specific products Categories like **'Cleats'** and **'Men's Footwear'** consistently fail to deliver on time over 50% of the time, signaling a need for targeted inventory and carrier re-evaluation

### 2. Financial Justification
* **Visual:** Average Profit by Delivery Status
* **Impact:** Statistically demonstrated that **'Late Deliveries'** often correlate with lower average profit per order compared to on-time shipments. This provides the financial evidence required to justify logistics infrastructure investments

### 3. Geographic Risk Assessment
* **Visual:** Global Sales & Delay Distribution Map
* **Impact:** Pinpointed regions like **Western Europe** and **Central Africa** as hotspots for delays. This data allows the business to renegotiate localized shipping contracts in underperforming territories

### 4. Service Level Reliability
* **Visual:** Reliability vs. Shipping Mode (Bar & Line Chart).
* **Impact:** Revealed that premium shipping tiers (First/Second Class) often suffer from the same delay rates as Standard ClassThis insight exposes a brand-risk where customers pay for "speed" that isn't being delivered

## 🤖 Machine Learning: The Predictive Engine
To move from reactive to proactive management, I developed a **Random Forest Classifier** to predict the probability of a late delivery before an order is even processed.
* **Model Performance:** Achieved 90%+ accuracy.
* **Key Features:** The model identified **'Shipping Mode'** and **'Days for Shipment Scheduled'** as the most critical predictors of delivery failure

## 🖥️ Interactive Dashboard
The analysis is wrapped in a professional dashboard built with **Panel** and **Plotly**
* **Key Features:** Real-time KPI monitoring (Total Profit, Late Rate, Avg Delay), monthly trend analysis, and dynamic filtering by region and shipping mode.

---

**Author:** [Swetha Mehtre]  
**Goal:** Future Data Scientist / Data Analyst
**linkdn:** https://www.linkedin.com/in/swetha-6619442a9/
