# Fast-Food-Cafe-Sales-Data-Analysis-Project
Fast Food &amp; Cafe Sales

## Executive Summary
This project delivers a comprehensive data cleaning and exploratory data analysis (EDA) pipeline evaluating order transactions across major cities. By shifting messy raw timestamps into orderly datetime fields and engineering features like transactional gross values, the project highlights key sales channels, customer feedback distributions, and overall product financial performance. The goal of this analysis is to optimize regional menu offerings and target effective payment infrastructure rollouts.

---

## 🛠️ Data Cleaning Process
To ensure highly accurate insights, the following data cleaning and feature engineering steps were executed using **Pandas** and **NumPy**:
1. **Datetime Parsing:** Converted the raw string-based `Order_Date` object into a proper `datetime64` data type to support chronological tracking.
2. **Feature Engineering:** Extracted `Month` and `Day_of_Week` from the timestamp to facilitate future seasonal and operational scheduling analysis.
3. **Derived Metrics:** Generated a `Gross_Value` metric using array multiplication (`Price` * `Quantity`) to calculate pre-revenue benchmarks.
4. **Data Integrity:** Inspected the core structural matrix to confirm zero missing null values and zero duplicated rows, followed by a clean timeline sort.

---

## 📊 Key Data Insights & Discoveries

Based on our data visualizations generated with **Matplotlib** and **Seaborn**, we discovered the following trends:

### 1. Revenue Generation by Product
* **Insight:** Popular main-course options like **Pizza** and **Pasta** dominate overall revenue performance. Despite their higher base price points, healthy transaction volumes make them the absolute core drivers of business income.
* **Actionable Takeaway:** Protect margin structures for these top two items, and cross-promote them alongside lower-revenue sides like **Fries** or **Sandwiches** to boost the total average order value.

### 2. High Customer Satisfaction Stability
* **Insight:** Customer ratings heavily cluster in the positive **4.0 to 4.8 range**, forming a stable, high-satisfaction distribution. Very few orders drop below a 3.8 rating.
* **Actionable Takeaway:** Quality control is highly consistent. Focus marketing efforts around these strong customer approval scores to acquire new users via social proof.

### 3. Payment Mode Adaptability Across Cities
* **Insight:** Payment preferences vary distinctively across geographic regions. For instance, digital ecosystems like **UPI** show incredibly dense transaction totals in tech-centric hubs like **Bangalore** and financial centers like **Mumbai**. Traditional payment pathways or physical **Cash** remain prominent in other locations.
* **Actionable Takeaway:** Optimize checkout speed by prioritizing local favorite payment setups. Target zero-failure UPI pathways in Mumbai/Bangalore while ensuring reliable cash management structures remain available in physical cash-heavy cities.

 
