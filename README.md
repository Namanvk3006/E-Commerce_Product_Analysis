# 📊 E-Commerce Product & Supply Chain Analysis

## 📌 Project Overview
E-commerce warehouses face severe capital constraints when storing dead inventory. This project analyzes over 15,000 raw sales transactions to optimize inventory management and forecast future revenue trends. 

By building an end-to-end data pipeline, this analysis identifies high-value products, engineers financial metrics, and provides a data-driven strategy for supply chain reallocation.

## 🛠️ Tech Stack & Tools
* **Data Processing & Engineering:** Python, Pandas, NumPy
* **Database & Querying:** SQLite (In-memory execution with Window Functions)
* **Data Visualization:** Matplotlib, Seaborn, Plotly (Interactive)
* **Predictive Modeling:** Statsmodels (Holt-Winters Exponential Smoothing)

## 🚀 Key Business Insights
1. **ABC Inventory Classification (Pareto Principle):** * Programmatically proved that **20% of the product SKUs generated ~65% of the total revenue** (Class A).
   * **Recommendation:** Prioritize Class A inventory for constant restocking while liquidating Class C (bottom 50% of SKUs) to free up warehouse capacity.
2. **Dynamic Regional Performance:**
   * Utilized SQL `SUM() OVER` window functions to track cumulative monthly revenue, identifying Maharashtra and Karnataka as peak markets requiring targeted ad spend.
3. **Short-Term Forecasting:**
   * Deployed a time-series forecasting model to predict a 7-day revenue trend, enabling proactive warehouse staffing.

## 💻 How to Run This Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/Ecommerce-Product-Analysis.git](https://github.com/yourusername/Ecommerce-Product-Analysis.git)
