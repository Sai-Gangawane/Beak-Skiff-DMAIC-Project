# 🍎 Beak & Skiff Apple Orchards — DMAIC Process Improvement Project

**Tools:** Power BI · Microsoft Excel · Minitab · Lean Six Sigma (Black Belt) · DMAIC

> A real operations problem. A structured solution. Measurable results.
> End-to-end DMAIC process improvement project on live production data from Beak & Skiff Apple Orchards, LaFayette, NY.

---

## 📊 Business Impact

| Metric | Before | After | Result |
|--------|--------|-------|--------|
| Annual Labor Cost | Baseline | Optimized | **$73,104 saved** |
| Productivity (Units/Hr/Person) | 47.0 | 58.0 | **+23.4%** |
| Cost Per Packet | $0.43 | $0.34 | **-21%** |
| Worker Speed Variation | 4.0x | 1.5x | **-63% variance** |
| Monthly Recurring Savings | — | $6,092 | **Ongoing** |

---

## 🎯 The Business Problem

Beak & Skiff Apple Orchards processes thousands of apple packets per shift across a multi-station production floor. Despite consistent staffing, labor costs were rising and throughput was inconsistent week over week.

**Root causes were unknown. Nobody had measured the process.**

Management had no visibility into which stations were creating bottlenecks, whether workers were assigned to tasks that matched their speed, or how much time was lost to unnecessary movement between stations. This project was initiated to answer those questions with data — and fix what we found.

---

## 🔬 DMAIC Framework — What We Did

### 📌 Define
- Mapped the full production workflow from apple intake to packaged output
- Conducted stakeholder interviews with production supervisors
- Established project charter with measurable targets: reduce labor cost ≥15%, increase throughput ≥20%
- Identified 7 workers across 3 core task types: cleaning, packing, stickering

### 📏 Measure
- Ran structured time studies across all workers and stations
- Collected 9 weeks of baseline production data (Weeks 10–18)
- Established current state: **$0.43 cost per packet, 47 units/hr/person**
- Quantified week-over-week productivity variance

### 🔍 Analyze
- Built Pareto analysis identifying top bottlenecks by delay frequency
- **Two issues drove 70% of all production delays:**
  - Cleaning Process Bottlenecks: **43%** of delays
  - Worker Movement to Fetch Materials: **27%** of delays
- Applied Value Stream Mapping (VSM) to visualize waste
- Used Fishbone diagram and 5-Why analysis to trace root causes

### ⚙️ Improve
- Redesigned station layout to eliminate cross-floor worker travel
- Reallocated all 7 workers to roles matched to their measured task speed
- Standardized cleaning → packing → stickering sequence with written SOPs
- Ran a 3-week controlled pilot (Weeks 16–18) to validate before full rollout

### 📋 Control
- Built control charts in Minitab to detect regression
- Documented standard work instructions for each station role
- Established weekly KPI tracking framework handed off to supervisors

---

## 📈 Power BI Dashboard

Built a 4-page interactive dashboard to communicate findings to operations leadership.

| Page | What It Shows |
|------|--------------|
| **Executive Summary** | $73K / 23.4% / $0.43→$0.34 KPI cards + weekly productivity trend + worker task time comparison |
| **Worker Performance** | Task time by worker (cleaning, packing, stickering) + rankings table + suggested role assignments |
| **Bottleneck Analysis** | Pareto chart (frequency % + cumulative %) + full bottleneck detail table |
| **Financial Summary** | Before vs after comparison across all metrics + financial impact summary table |

📥 Download `Beak_Skiff_DMAIC_Dashboard.pbix` from the `/dashboard` folder to explore interactively in Power BI Desktop.

---

## 📁 Repository Contents

```
Beak-Skiff-DMAIC-Project/
│
├── README.md
├── dashboard/
│   └── Beak_Skiff_DMAIC_Dashboard.pbix
├── data/
│   ├── weekly_production.csv
│   ├── worker_performance.csv
│   ├── bottleneck_analysis.csv
│   └── financial_summary.csv
└── docs/
    ├── DMAIC_Project_Charter.md
    ├── Bottleneck_Analysis.md
    ├── Process_Improvement_Playbook.md
    └── Beak_Skiff_DMAIC_OnePager.pdf
```

---

## 🛠️ Tools & Methods

| Category | Tools |
|----------|-------|
| Data Visualization | Power BI Desktop |
| Statistical Analysis | Minitab, Excel Solver |
| Process Mapping | Value Stream Mapping (VSM) |
| Root Cause Analysis | Pareto, Fishbone Diagram, 5-Why |
| Methodology | DMAIC · Lean Six Sigma Black Belt |
| Data Processing | Microsoft Excel (Advanced) |

---

## 👥 Project Team

| Name | Role |
|------|------|
| **Sai Santosh Gangawane** | Project Lead — DMAIC facilitation, data analysis, Power BI dashboard |
| Meet Patel | Time study data collection, process mapping |
| Katherine Rodrigues Acosta | Stakeholder liaison, SOP documentation |
| Meghanath Somarowthu | Statistical analysis, Minitab, control charts |

**Executive Sponsor:** Bryanna Cortese, COO — Beak & Skiff Apple Orchards
**Institution:** Syracuse University — MS Engineering Management

---

## 🔗 Related Work

**AI Supply Chain Intelligence Hub** — https://sc-ai-dashboard.streamlit.app

A companion project extending this DMAIC work using ML anomaly detection (Scikit-learn Isolation Forest) and Llama 3.3 70B for automated root cause analysis. Reduces exception identification from days to 30 seconds. Built with Python, Pandas, Plotly, and Streamlit.

---

## 📬 About the Author

**Sai Santosh Gangawane**
MS Engineering Management — Syracuse University
Lean Six Sigma Black Belt (CSSC) · CSCMP Certified · Agile PM (Atlassian)

Targeting: Supply Chain Analyst · Operations Analyst · Process Improvement Engineer · Demand Planner
Work Authorization: F-1 OPT (STEM eligible — 3-year extension available)
Location: New York · Open to relocation anywhere in the US

- LinkedIn: https://www.linkedin.com/in/sai-gangawane
- GitHub: https://github.com/Sai-Gangawane
- AI Dashboard: https://sc-ai-dashboard.streamlit.app
