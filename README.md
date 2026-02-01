# 🛒 Retail Dashboard 2026 — Save-On-Foods (Yoghurt Category)

## 📌 Project Overview
As a BI Analyst, I tend to see data in everything — it’s a bit of a devil on your back. You notice patterns everywhere, but you don’t always get to share them… or even want to 😅.

This project started after watching **Jon Acampora’s** YouTube video on how *unstructured data can still produce powerful insights*. That idea stuck with me. Shortly after, I remembered the **photos I had taken during a grocery shopping trip** — shelf layouts, pricing, product sizes, and brand placement.

That curiosity turned into this challenge:
> **Can retail shelf images be transformed into a decision-ready analytics dashboard?**

The answer is **yes**.

---

## 🎯 Objective
Transform unstructured shelf observations into a **retail analytics dashboard** that answers:
- Which brands dominate shelf availability?
- How pricing differs by size, category, and product type
- Premium vs mass-market positioning
- Shelf share as a proxy for demand
- Pricing gaps between protein and regular yoghurt

---

## 🧠 Data Source (Unstructured → Structured)
- 📸 **Source:** Images captured during an in-store shopping trip
- 🧾 **Manual extraction:** Brand, category, size (g), price (CAD), shelf count
- 🧮 **Proxy metrics:** Shelf units used as a demand signal

---

## 🧹 Data Preparation (Excel)
Raw observations were cleaned and standardized in Excel:
- Normalized brand names and categories
- Converted sizes and prices to consistent formats
- Created product variants and pricing tiers
- Prepared data for relational modeling

**Excel cleanup snapshot:**
![Excel Cleanup](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/Excel%20Cleanup.png)

---

## 🏗️ Data Modeling (Power BI)
A **star schema** was implemented for scalability and performance:
- **Fact tables:** Shelf observations & pricing
- **Dimension tables:** Brand, category, product attributes
- **Measures table:** Centralized DAX logic

**Model diagram:**
![Star Schema](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/relationship%20star%20schema.png)

---

## 📐 DAX Measures
Key measures were built to support analytical storytelling:
- Average / Min / Max Price
- Product Variants
- Shelf Share %
- Premium Price Index
- Protein vs Regular Price Gap
- Estimated Shelf Units

**Measures examples:**
![Measures](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/measures.png)
![Measures 2](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/measures%202.png)

---

## 📊 Dashboard Design & Storytelling

### 🔹 Dashboard Main
High-level executive snapshot:
- Top brand by availability
- Price range and average price
- Shelf share and premium positioning
- Brand vs product type insights

![Dashboard Main](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/Dashboard%20Main.png)

**Drill-through views:**
![Drill 1](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/Dashboard%20Main-Drill%201.png)
![Drill 2](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/Dashboard%20Main-Drill%202.png)

---

### 🔹 Dashboard Page 2 — Deep Dive
Focused on:
- Price vs size behavior
- Brand price volatility
- Category-level pricing patterns
- Decomposition tree for price drivers

![Dashboard 2](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/Dashboard%202.png)

**Drill-through analysis:**
![Dashboard 2 Drill 1](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/Dashboard%202-Drill%201.png)
![Dashboard 2 Drill 2](https://github.com/iyanusol/Retail-Dashboard-2026-Save-On-Foods-/blob/main/images/Dashboard%202-Drill%202.png)

---

## 💡 Key Insights
- Shelf availability strongly mirrors brand dominance
- Protein products often command premium pricing, but not consistently
- Larger sizes don’t always guarantee better value
- Shelf share acts as a powerful demand proxy in the absence of sales data

---

## 🛠 Tools Used
- **Power BI** (Modeling, DAX, Drill-through, Decomposition Tree)
- **Excel** (Data cleanup & structuring)
- **Manual data extraction** from real-world observations

---

## 🚀 Why This Project Matters
This project demonstrates:
- Turning **unstructured data into structured insight**
- Strong **data modeling fundamentals**
- Business-first dashboard storytelling
- Real-world analytical curiosity beyond clean datasets

---

## 🔗 Connect With Me
If you enjoyed this project or want to discuss data storytelling, BI, or analytics:

👉 **LinkedIn:** https://www.linkedin.com/in/iyanu-adebara-5a62a0103
