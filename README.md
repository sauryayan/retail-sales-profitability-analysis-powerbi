# 📊 Retail Sales & Profitability Analysis Dashboard (Power BI)

Interactive business intelligence dashboard built to analyze **9,904 retail transactions**, uncover profitability leakage, evaluate customer behavior, and identify actionable business opportunities.

---

## 🧩 Problem Statement

Retail businesses often generate strong revenue while silently losing profitability due to:

- excessive discounting
- inefficient product mix
- weak regional performance
- poor pricing strategy

This project analyzes transactional retail data to uncover the real drivers behind revenue, profit, and losses.

---

## 🎯 Objectives

✔ Identify top loss-making products and categories  
✔ Analyze the impact of discounting on profitability  
✔ Evaluate customer segment performance and efficiency  
✔ Assess regional sales and margin performance  
✔ Study customer engagement and purchase behavior  
✔ Deliver actionable business recommendations

---

## 🛠️ Tools & Technologies

- **Power BI** (Dashboard Design & Visualization)
- **DAX** (Advanced Calculations & Measures)
- **Power Query** (Data Cleaning & Transformation)
- **Data Modeling**
- **Business Analytics**

---

## 📂 Dataset

**Source:** Superstore Retail Dataset

**Dataset Size:** 9,904 transactional records

### Features:
- Order ID
- Customer ID
- Sales
- Profit
- Discount
- Quantity
- Product / Category / Sub-category
- Customer Segment
- Region
- Order Date

---

## 📊 Dashboard Overview

### 1️⃣ Executive Overview

High-level business monitoring dashboard including:

- 💰 Total Sales
- 📈 Net Profit
- 📊 Profit Margin %
- 🚀 YoY Growth
- 📉 Total Loss

Visuals:
- Sales trend over time
- Regional revenue comparison
- Top loss-making products
- Executive business insights

---

### 2️⃣ Product & Discount Analysis

Deep-dive profitability analysis focused on discount leakage.

Includes:

- Discount threshold analysis
- Category profitability comparison
- Top loss-making products
- Loss contribution %
- Pricing risk assessment

---

### 3️⃣ Customer & Regional Performance

Business performance analysis by customer segment and geography.

Includes:

- Segment revenue vs profitability
- Regional sales & margin efficiency
- Discount impact by region
- Customer base analysis
- Purchase frequency analysis

---

### 4️⃣ Interactive Tooltip Dashboard

Custom tooltip page for enhanced user experience.

Dynamic hover insights include:

- Region-specific loss contribution
- Discount diagnostics
- Category profit breakdown

---

## 🔍 Key Business Insights

### 💸 Profitability & Discount Insights

- Profitability declines sharply beyond the **20% discount threshold**
- High-discount products are the primary drivers of total losses
- A small subset of products contributes nearly **30% of total losses**

---

### 🪑 Product & Category Insights

- **Technology** is the strongest profit contributor
- **Furniture** contributes ~39% of total losses despite strong sales
- Higher discounting combined with weak margins creates structural profitability risk

---

### 👥 Customer Segment Insights

- **Consumer segment** drives the highest revenue and net profit due to the largest customer base
- **Corporate and Home Office** demonstrate stronger margin efficiency
- Purchase frequency remains relatively stable across segments, suggesting customer volume drives growth more than repeat behavior

---

### 🌍 Regional Insights

- **West region** leads in revenue and profit but margin quality is weakened by low-margin, discount-heavy top-selling categories
- **East region** delivers the strongest profitability performance
- **Central region** experiences discount-driven margin pressure
- **South region** underperforms due to lower customer engagement and weaker purchase activity

---

## 📈 Business Recommendations

✅ Reevaluate discounting beyond 20%  
✅ Optimize pricing strategy for Furniture category  
✅ Reduce exposure to structurally loss-making products  
✅ Improve customer acquisition & engagement in South region  
✅ Investigate East’s stronger profitability model for transferable insights  

---

## 🧠 Key Learnings

This project reinforced critical analytics lessons:

- Understanding **business grain before data cleaning**
- Importance of **DAX filter context**
- Translating raw numbers into business decisions
- Designing dashboards for **executive storytelling**
- Balancing **UX clarity vs analytical depth**
- Using **tooltips and drill-through insights effectively**

---

## ⚠ Important Analytical Lesson

During development, duplicate Order IDs were mistakenly removed under the assumption they represented duplicate records.

This drastically changed business metrics and led to misleading insights.

After investigation:

✔ Order IDs legitimately contained multiple line items  
✔ Transactional grain was preserved  
✔ Analysis was rebuilt correctly  

**Key lesson:** Never clean data without understanding business grain.

---

## 📌 Conclusion

This project demonstrates how business intelligence can move beyond reporting into actionable decision support.

By combining **profitability diagnostics, customer analytics, regional performance evaluation, and pricing analysis**, the dashboard helps identify where revenue is healthy—and where profitability silently leaks.

---

## 👨‍💻 Author

**Sauryayan Pankaj Ralhi**
[Linked In](https://www.linkedin.com/in/sauryayan/)

Data Analyst | Power BI | SQL | Python | DAX

📌 Open to Data Analyst Opportunities
