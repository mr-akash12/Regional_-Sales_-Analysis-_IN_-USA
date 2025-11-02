
# 📊 Regional Sales Analysis — EDA & Power BI Dashboard

## 🧩 Project Overview
This project focuses on analyzing **5 years of regional sales data** to uncover key business insights, identify growth opportunities, and support data-driven decision-making. The analysis was conducted using **Python (EDA)** and visualized using an **interactive Power BI dashboard**.

---

## 🎯 Business Problem
The company faced inconsistent revenue and profit performance across U.S. regions, lacking visibility into:
- Seasonal sales patterns
- Top-performing SKUs and channels
- Regional profitability differences

**Goal:** Build data-driven insights and an interactive dashboard to optimize regional sales strategy.

---

## 🧠 Approach

### Phase 1: Exploratory Data Analysis (Python)
Performed data cleaning, feature engineering, and exploratory visualizations to identify sales trends, product performance, and customer segmentation.

**Steps:**
1. Data Import & Inspection  
2. Data Cleaning & Transformation  
3. Feature Engineering  
4. Statistical Analysis  
5. Data Visualization & Insight Extraction  

### Phase 2: Interactive Dashboard (Power BI)
Developed an intuitive, interactive dashboard that allows business users to explore:
- Regional performance  
- Product profitability  
- Customer segmentation  
- Seasonal and channel-wise trends  

---

## 🧰 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Programming | Python |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, Plotly |
| Visualization | Power BI |
| File Format | Excel / CSV |
| Documentation | Markdown, PowerPoint Summary |

---

## 🧼 Data Pre-Processing
- Merged multiple raw tables: **Sales**, **Products**, **Customers**, **Regions**, and **Budgets**  
- Standardized column names  
- Removed redundant columns  
- Created new features:  
  - `profit` = revenue - cost  
  - `profit_margin_pct` = profit / revenue * 100  
- Verified: No missing or duplicate records  

---

## 📊 Key Insights

| Area | Findings |
|------|-----------|
| **Seasonality** | Revenue peaks in May–June, drops in January |
| **Top Products** | SKUs 26 & 25 generate ~25% of total sales |
| **Channels** | Wholesale = 54% of sales; Export = highest margin (~38%) |
| **Geography** | California dominates sales ($230M); West region leads overall |
| **Customers** | “Aibox Company” contributes highest revenue |
| **Correlations** | Unit price drives profit (corr = 0.79) more than quantity |

---

## 💡 Recommendations
1. **Seasonal Promotions:** Boost sales in low months (Jan–Apr)  
2. **SKU Optimization:** Focus on top 25% of products, phase out low-margin SKUs  
3. **Channel Strategy:** Expand export partnerships and incentivize wholesale volume  
4. **Regional Focus:** Replicate California’s success model in Midwest & Northeast  
5. **Margin Alerts:** Monitor and improve low-margin orders  

---

## 📈 Dashboard Overview

**Power BI Pages:**
1. **Performance Summary:** Revenue, profit, and region KPIs  
2. **Customer Segmentation:** Revenue vs Profit Margin insights  
3. **Revenue Scenarios:** Forecast and comparative analysis  

---

## ✅ Results & Impact
- Achieved complete **end-to-end analysis** pipeline from raw data to insights  
- Improved **visibility into regional trends** and **product performance**  
- Enabled **self-service analytics** for business users via Power BI  

---

## 📂 Files Included

| File | Description |
|------|--------------|
| `EDA.ipynb` | Python notebook for data analysis |
| `Regional_Sales_Dashboard.pbix` | Power BI dashboard |
| `PPT --- Regional Sales Analysis.pptx` | Presentation summary |
| `README.md` | Project documentation (this file) |

---

## 🚀 Future Improvements
- Integrate real-time data pipelines (Power BI + SQL)  
- Add predictive models for sales forecasting  
- Automate monthly performance reports  

---

**Author:** [Your Name]  
**Role:** Data Analyst / Data Scientist  
**Tools:** Python, Power BI, Excel  
**Location:** Bangalore, India  
