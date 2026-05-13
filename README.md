# 🟡 Blinkit Grocery Sales Analysis Dashboard

> An end-to-end Excel-based business intelligence dashboard analyzing Blinkit's grocery sales performance across outlets, item categories, and locations.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Key Performance Indicators](#key-performance-indicators)
- [Dataset Description](#dataset-description)
- [Dashboard Features & Analysis](#dashboard-features--analysis)
- [Key Insights](#key-insights)
- [File Structure](#file-structure)
- [Tools & Technologies](#tools--technologies)
- [How to Use](#how-to-use)
- [Data Dictionary](#data-dictionary)
- [Screenshots](#screenshots)
- [Author](#author)

---

## 🧩 Project Overview

This project delivers a **comprehensive sales analysis dashboard** for **Blinkit** (India's last-minute grocery delivery app), built entirely in Microsoft Excel. The dashboard transforms raw transactional grocery data into actionable business insights, enabling stakeholders to make informed decisions around product strategy, outlet expansion, and inventory optimization.

The analysis covers **8,523 grocery items** sold across multiple outlet types, sizes, and geographic tiers — spanning establishment years from **2011 to 2022**.

---

## 📊 Key Performance Indicators

| Metric | Value |
|---|---|
| 💰 **Total Sales** | ₹ 12,01,681.49 |
| 📈 **Average Sales per Item** | ₹ 140.99 |
| 🛒 **Total Number of Items** | 8,523 |
| ⭐ **Average Customer Rating** | 3.97 / 5 |

---

## 🗂️ Dataset Description

The raw dataset (`BlinkIT Grocery Data` sheet) contains transactional records for grocery items sold across Blinkit's outlet network.

- **Total Records:** 8,523 rows
- **Total Columns:** 13
- **Time Span:** Outlet establishment years 2011 – 2022
- **Outlet Locations:** Tier 1, Tier 2, Tier 3 cities
- **Outlet Types:** Grocery Store, Supermarket Type 1, Type 2, Type 3

---

## 🔍 Dashboard Features & Analysis

The dashboard (`Sheet Design` & `DashBoard` tabs) presents **7 core analytical views**:

### 1. 🥗 Total Sales by Fat Content
Breaks down total revenue by product fat content classification:

| Fat Content | Total Sales (₹) |
|---|---|
| Low Fat | 7,76,319.69 |
| Regular | 4,25,361.80 |

> Low Fat products account for **~65%** of total sales, reflecting a health-conscious consumer trend.

---

### 2. 🏪 Fat Content by Outlet Tier (Sales Contribution)
Cross-tabulation of fat content against outlet location tier:

| Location | Regular (₹) | Low Fat (₹) |
|---|---|---|
| Tier 1 | 1,21,349.90 | 2,15,047.91 |
| Tier 2 | 1,38,685.87 | 2,54,464.78 |
| Tier 3 | 1,65,326.04 | 3,06,806.99 |

---

### 3. 🛍️ Total Sales by Item Type
Sales performance ranked across **16 product categories**:

| Rank | Item Type | Sales (₹) |
|---|---|---|
| 1 | Fruits and Vegetables | 1,78,124.08 |
| 2 | Snack Foods | 1,75,433.92 |
| 3 | Household | 1,35,976.53 |
| 4 | Frozen Foods | 1,18,558.88 |
| 5 | Dairy | 1,01,276.46 |
| 6 | Canned | 90,706.73 |
| 7 | Baking Goods | 81,894.74 |
| 8 | Health and Hygiene | 68,025.84 |
| 9 | Meat | 59,449.86 |
| 10 | Soft Drinks | 58,514.17 |
| 11 | Hard Drinks | 29,334.68 |
| 12 | Breads | 35,379.12 |
| 13 | Others | 22,451.89 |
| 14 | Starchy Foods | 21,880.03 |
| 15 | Breakfast | 15,596.70 |
| 16 | Seafood | 9,077.87 |

---

### 4. 📅 Total Sales by Outlet Establishment Year
Year-wise revenue trend since each outlet's founding year:

| Year | Sales (₹) |
|---|---|
| 2011 | 78,131.57 |
| 2012 | 1,30,476.86 |
| 2014 | 1,31,809.02 |
| 2015 | 1,30,942.78 |
| 2016 | 1,32,113.37 |
| 2017 | 1,33,103.91 |
| **2018** | **2,04,522.26** ⬆️ |
| 2020 | 1,29,103.96 |
| 2022 | 1,31,477.78 |

> **2018** was the peak year for new outlet openings contributing to total sales.

---

### 5. 📦 Sales by Outlet Size

| Outlet Size | Sales (₹) |
|---|---|
| Medium | 5,07,895.74 |
| Small | 4,44,794.17 |
| High | 2,48,991.59 |

> **Medium-sized outlets** drive the highest revenue, contributing ~42% of total sales.

---

### 6. 📍 Sales by Outlet Location (City Tier)

| Location Type | Sales (₹) |
|---|---|
| Tier 3 | 4,72,133.03 |
| Tier 2 | 3,93,150.65 |
| Tier 1 | 3,36,397.81 |

> **Tier 3 cities** generate the most revenue — highlighting strong demand in smaller cities and towns.

---

### 7. 🏬 All Metrics by Outlet Type

| Outlet Type | Total Sales (₹) | Avg Sales (₹) | Item Count |
|---|---|---|---|
| Supermarket Type1 | 7,87,549.89 | 141.21 | 5,577 |
| Grocery Store | 1,51,939.15 | 140.29 | 1,083 |
| Supermarket Type2 | 1,31,477.78 | 141.68 | 928 |
| Supermarket Type3 | 1,30,714.67 | 139.80 | 935 |

> **Supermarket Type 1** dominates with ~65.5% of total revenue and the highest item count.

---

## 💡 Key Insights

1. **Low Fat dominates sales** — 64.6% of revenue comes from Low Fat products, suggesting a health-aware customer base.
2. **Fruits, Vegetables & Snacks** are the top-selling categories — perishables and convenience foods drive volume.
3. **Tier 3 cities outperform** Tier 1 and Tier 2 cities in revenue, pointing to untapped potential in smaller markets.
4. **2018 was a breakout year** — outlets established in 2018 have the highest cumulative sales.
5. **Medium-sized stores** are the sweet spot — balancing item variety with operational efficiency.
6. **Average rating of ~3.97** across all outlets indicates generally positive but improvable customer satisfaction.
7. **Supermarket Type 1** is the most dominant format, accounting for nearly two-thirds of all sales and items.

---

## 📁 File Structure

```
Blinkit_Analysis_Dashboard__Excel_.xlsx
│
├── 📄 BlinkIT Grocery Data      ← Raw transactional dataset (8,523 rows × 13 columns)
├── 📊 Sheet Design              ← Pivot tables, KPI calculations & data summaries
└── 🖥️  DashBoard                ← Interactive visual dashboard with charts & slicers
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Primary tool for data analysis, pivot tables, and dashboard creation |
| **Pivot Tables** | Aggregating and summarizing sales data across multiple dimensions |
| **Excel Charts** | Visualizing trends (bar, donut, line charts) |
| **Conditional Formatting** | Highlighting KPIs and performance metrics |
| **Excel Formulas** | KPI calculations (SUM, AVERAGE, COUNT) |

---

## 🚀 How to Use

1. **Download** the file `Blinkit_Analysis_Dashboard__Excel_.xlsx`
2. **Open** in Microsoft Excel (2016 or later recommended for full compatibility)
3. Navigate to the **DashBoard** tab for the visual overview
4. Use **slicers/filters** (if configured) to drill down by:
   - Outlet Location Type (Tier 1 / 2 / 3)
   - Outlet Size (Small / Medium / High)
   - Item Fat Content (Low Fat / Regular)
   - Outlet Type (Grocery Store / Supermarket Types)
5. Visit the **Sheet Design** tab to explore underlying pivot tables
6. Access **BlinkIT Grocery Data** for raw record-level exploration

---

## 📖 Data Dictionary

| Column | Description | Values / Type |
|---|---|---|
| `Item Fat Content` | Fat classification of the product | Low Fat, Regular |
| `Serial No` | Unique row identifier | Integer |
| `Item Identifier` | Unique product code | Alphanumeric (e.g., FDX32) |
| `Item Type` | Product category | 16 categories (Fruits, Snacks, Dairy, etc.) |
| `Outlet Establishment Year` | Year the outlet was founded | 2011 – 2022 |
| `Outlet Identifier` | Unique store code | Alphanumeric (e.g., OUT049) |
| `Outlet Location Type` | City tier classification | Tier 1, Tier 2, Tier 3 |
| `Outlet Size` | Physical size of the outlet | Small, Medium, High |
| `Outlet Type` | Business format of the outlet | Grocery Store, Supermarket Type 1/2/3 |
| `Item Visibility` | Shelf visibility score (0–1) | Float |
| `Item Weight` | Weight of the product (kg) | Float (some missing values) |
| `Total Sales` | Revenue generated by item (₹) | Float |
| `Rating` | Customer satisfaction rating | 1 – 5 scale |

---

## 📸 Screenshots

> _Open the **DashBoard** tab in Excel to view the interactive dashboard._

The dashboard includes visual representations of:
- KPI cards (Total Sales, Avg Sales, Items Count, Avg Rating)
- Donut chart — Sales by Fat Content
- Bar chart — Sales by Item Type
- Line/Area chart — Sales by Outlet Establishment Year
- Stacked bar — Fat Content by Outlet Tier
- Pie/Bar — Sales by Outlet Size & Location
- Summary table — All Metrics by Outlet Type

---

## 👤 Author

**Blinkit Sales Analysis Project**
Built as a data analytics portfolio project using Excel BI techniques.

---

## 📜 License

This project is for educational and portfolio purposes. The dataset is based on publicly available sample grocery data modelled after Blinkit's retail structure.

---

> *"Turning raw grocery data into actionable retail intelligence — one pivot table at a time."* 🛒
