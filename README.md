# 🚀 Optimizing Inventory and Pricing Strategy for Zepto

**Author: Vivek Balmiki**

## 📌 Business Problem

Quick-commerce platforms like Zepto face two critical operational challenges:

* Frequent stockouts of high-demand essential items
* Sub-optimal pricing strategies affecting profitability

This project uses structured exploratory analysis and inventory classification techniques to identify the root causes and propose data-driven strategic solutions.

---

## 🎯 Objective

To analyze product-level data and:

* Identify high-risk inventory categories
* Diagnose stockout patterns
* Evaluate pricing and discount behavior
* Apply ABC analysis for inventory prioritization
* Generate actionable business recommendations

---

## 📂 Project Structure

```
zepto-inventory-pricing-optimization/
│
├── dataset/
│   └── zepto.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Inventory_and_Pricing_Optimization.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🔍 Key Analytical Techniques Used

* Exploratory Data Analysis (EDA)
* Revenue Proxy Modeling
* Category-Level Analysis
* Correlation Analysis
* Stockout Pattern Visualization
* ABC Inventory Classification
* Business Risk Segmentation

---

## 📊 Major Findings

### 1️⃣ Stockouts Are Concentrated in Essential, Low-MRP Items

Stockouts occur primarily in:

* Low-MRP
* Low-discount
* High-demand staple goods

This indicates:

> Stockouts are caused by failure to meet organic demand — not excessive promotions.

---

### 2️⃣ Inventory Risk is Unevenly Distributed

Using ABC analysis:

* **Class A items** represent a small percentage of SKUs but drive the majority of revenue and operational risk.
* Uniform inventory policies are inefficient.
* High-risk goods require differentiated control mechanisms.

---

### 3️⃣ Pricing Is Not the Root Cause

Correlation analysis suggests:

* Discounts do not strongly drive rating or demand.
* Essentials maintain demand regardless of promotions.

This rules out pricing strategy as the primary issue.

---

## 📈 Business Interpretation

The inventory challenge likely stems from:

* Poor SKU-level demand forecasting
* Lack of tiered inventory management
* Possible bullwhip effect in supply chain
* Delayed replenishment cycles for high-demand goods

The root problem is **replenishment inefficiency**, not promotional strategy.

---

## ✅ Actionable Recommendations

### 1️⃣ Implement ABC-Driven Inventory Policy

* **Class A:** High safety stock, daily monitoring
* **Class B:** Standard monitoring
* **Class C:** Lean inventory model

---

### 2️⃣ Improve Demand Forecasting

Develop SKU-specific forecasting models for:

* Class A items
* High-risk Class B items

---

### 3️⃣ Priority-Based Replenishment Alerts

Implement automated alerts triggered by:

* Low stock levels
* ABC priority classification

---

### 4️⃣ Strategic Price Optimization Test

Since demand is stable:

* Test 1–3% price increase on high-demand staples
* Reinvest additional revenue into supply chain stability

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📌 Impact Potential

If implemented:

* Reduced stockouts
* Improved fill rate
* Better working capital efficiency
* Increased operational stability
* Improved profitability margins

---

## 🧠 What This Project Demonstrates

* Business-first thinking
* Structured analytical reasoning
* Operational strategy formulation
* Translating EDA into executive recommendations
* Applying inventory management frameworks (ABC analysis)

---

## 🚀 Future Improvements

* Build demand forecasting model (ARIMA / ML-based)
* Simulate inventory optimization model
* Add cost-of-stockout estimation
* Build interactive dashboard (Streamlit / Power BI)

---

That README is strong enough for interviews.

---

# ✅ 4️⃣ requirements.txt (Add This)

Create a file:

`requirements.txt`

Add:

```
pandas
numpy
matplotlib
seaborn
jupyter
```

---