# 🌿 PAHSUS UN-SDG Sustainability Analytics Portal

An interactive, responsive, and data-driven Web Analytics Dashboard developed for **Punyashlok Ahilyadevi Holkar Solapur University (PAHSUS)** to track, monitor, and visualize United Nations Sustainable Development Goals (UN-SDGs) metrics sourced from university AQAR and Green Audit records.

---

## 📌 Project Overview

This sub-project transitions traditional static SDG reporting into a modern, dynamic web platform. It processes **198 master spatial & analytical records across 6 worksheets** (Academic Years 2022–23 & 2023–24) to provide real-time campus sustainability insights.

### Key Goals & Features:
* **7 Dedicated Modules:** Tailored analytics tabs for SDG 6 (Clean Water), SDG 7 (Clean Energy), SDG 12 (Responsible Consumption & Waste Mgmt), SDG 13 (Climate Action), SDG 15 (Life on Land), SDG 17 (Partnerships & Directory), and Executive Overview.
* **Global Academic Slicers:** Instant dynamic filtering across `2022-23`, `2023-24`, and `All Years`.
* **Department Benchmarking:** Integrated **Compare Mode** allowing facility-to-facility and department-wise metrics comparison.
* **Instant Export Suite:** One-click high-contrast **PDF report generation** (with dynamic developer metadata) and structured **Excel (.xlsx) data export**.
* **Fully Responsive UI:** Optimized using lightweight CSS Media Queries for desktop, tablet, and mobile browsers.

---

## 📂 Repository Structure

```text
PAHSUS-SDG-dashboard/
│
├── index.html          # Main HTML structure, layout grids, modal components, and script anchors
├── styles.css          # EVS-themed UI styling, flexbox/grid containers, and mobile media queries
├── app.js              # Business logic, Chart.js instances, DataTables config, and export tools
├── data.js             # JSON dataset containing 198 structured AQAR & Green Audit records
└── LICENSE             # MIT License
