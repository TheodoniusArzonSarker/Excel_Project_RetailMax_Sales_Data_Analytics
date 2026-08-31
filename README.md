<h1 align="center">📊 RetailMax Global — Executive Analytics Dashboard</h1>

<p align="center">
  <b>End-to-end Excel BI solution</b> built on 50K+ transactions across 5 business segments.<br>
  <i>Zero VBA · Full DAX time intelligence · Production-ready security</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Excel-365-green?logo=microsoftexcel" alt="Excel 365" />
  <img src="https://img.shields.io/badge/Power_Query-ETL-yellow?logo=microsoft" alt="Power Query" />
  <img src="https://img.shields.io/badge/DAX-Time_Intelligence-blue?logo=microsoft" alt="DAX Time Intelligence" />
  <img src="https://img.shields.io/badge/Dashboards-5-orange" alt="Dashboards" />
</p>

---

## ⚡ Quick Stats

| Metric | Value |
| :--- | :--- |
| **🗃️ Records** | 50K transactions · 500 products · 50 reps · 2K customers · 500 reviews |
| **📑 Sheets** | 18 total (5 dashboards · 5 pivot layers · 5 raw tables · 1 simulator · 1 landing page) |
| **🛠️ Tech Stack** | Power Query · Power Pivot · DAX · PivotTables · Data Validation · Conditional Formatting |

---

## 🖼️ Dashboard Gallery

* **Executive Command Center:** Features **5 live KPIs** paired with dynamic YoY trend indicators, 4 macro filter slicers, and an integrated navigation matrix for rapid routing across analytical blocks.
* **Sales Performance:** Tracks commercial velocity using revenue trend timelines, interactive country geo-maps, a Top 10 products leaderboard, and structural category breakdowns—entirely slicer-driven.
* **Team Analytics:** Evaluates workforce efficiency via a custom **revenue vs. profit margin combo chart** ("Who sells big vs. who sells smart") alongside comprehensive Top 10 rep rankings.
* **Product Deep-Dive:** Delivers granular inventory and catalog exploration powered by cascading, multi-level pivot slicers: `Category` ➔ `Subcategory` ➔ `Brand` ➔ `Country` ➔ `Timeline`.

---

## 🛠️ What I Built (Skills Breakdown)

### 1️⃣ Power Query — ETL Pipeline
* Extracted and normalized **6 disconnected raw tables** from a single source workbook.
* Executed data cleaning protocols: text standardization, column splitting, explicit null-value management, and whitespace trimming.
* Loaded optimized datasets into the native Excel **Data Model** with data relationships automatically mapped.

### 2️⃣ Data Modeling — Star Schema
* Engineered a robust **Star Schema** linking a central `Sales_Transactions` fact table to 4 unique dimension tables (`Products_Master`, `Customers_Master`, `Employees`, and `Marketing_Campaigns`).
* Generated a dedicated, continuous **Date Table** to safely host advanced time-intelligence calculations.
* Formed standard **1-to-many relationships** across core identity keys (`Product_ID`, `Customer_ID`, `Employee_ID`, `Campaign_ID`).

### 3️⃣ DAX — Time Intelligence & KPIs  
 Built a dynamic KPI engine with DAX time intelligence.  
 Five live metrics + automatic YoY comparisons that recalculate across any date, country, or category filter. Zero hardcoded values. Zero manual updates.  

### 4️⃣ Dashboard UI/UX Design
* Designed a contemporary **dark navigation sidebar** using icon-based hyperlinks for a seamless app-like interface.
* Replaced chunky default filters with sleek, horizontal **pill-style slicers** matching modern dashboard aesthetics.
* Configured rounded-corner container blocks utilizing strict, consistent spacing rules and deliberate typographic hierarchies.
* Integrated conditional context cues, including real-time `LIVE` status badges and responsive Red/Yellow/Green border alerts.

### 5️⃣ Security & Delivery
* Locked and protected all underlying formula cells, chart assets, and spatial layouts against unauthorized structural modification.
* Hidden backend raw data storage sheets and applied password protection to the root workbook structure.
* Isolated operational user access by restricting data input capabilities solely to designated **yellow input cells** within the Pricing Simulator.
* Implemented background query properties to trigger an **automatic data refresh** upon file initialization.

---
---

## 🚀 How to Use

1. **Open:** Initialize the workbook file; database connections and internal queries refresh automatically on load.
2. **Navigate:** Move between sheets using the left sidebar menu or the Executive Dashboard quick links.
3. **Filter:** Narrow down analytical scopes by interacting with the custom pill-style slicers (`Year` · `Quarter` · `Country` · `Category`).
4. **Simulate:** Model variable business outcomes by inputting custom values **exclusively within the yellow cells** inside the Pricing Simulator.
5. **Drill Down:** Jump to targeted segments instantly via specialized sub-dashboards.

> ⚠️ **Production Security:** Formula sheets, chart architecture, and background data sheets remain locked. Production parameters require administrative credentials to unlock.

---

## 💡 Key Business Insights

| Insight | Evidence Source |
| :--- | :--- |
| **📈 Revenue grew +23.4% YoY** despite volume dropping -7.3%. A sharp rise in Average Order Value (AOV) drove the overarching growth strategy. | `Executive KPIs` |
| **🏆 Electronics leads all business segments**, generating **$4.5M** (accounting for 24.6% of gross enterprise revenue). | `Sales Dashboard` (Category Bars) |
| **👑 Elizabeth Thompson dominated gross sales volume ($7.2M)**, while **Sarah Lee led the field in margin optimization (22.1%)**. | `Team Dashboard` (Dual Cards) |
| **📧 Email marketing proved the most efficient acquisition medium**, securing a **340% ROI** across active marketing channels. | `Marketing Dashboard` |
| **⚠️ 312 key accounts flag a high churn probability**, despite maintaining a healthy 4.2★ average satisfaction score. | `Customer Analytics` (Churn Engine) |

---

<p align="center">
  <b>Built for portfolio demonstration</b><br>
  Dataset: RetailMax Global e-commerce Records (2023–2025)
</p>
