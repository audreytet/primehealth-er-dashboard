# 🏥 PrimeHealth Medical Center — ER Analytics Dashboard

> **Emergency Room performance analytics** | KPI tracking · Patient flow · Wait time analysis · Doctor performance

![Dashboard Preview](preview.png)

---

## 📌 Project Overview

This project analyses Emergency Room (ER) data for **PrimeHealth Medical Center**, a healthcare provider in New York, USA. The analysis uncovers insights on patient flow, wait times, admission patterns, satisfaction scores, and doctor performance to support data-driven hospital management decisions.

Built as part of the **10Alytics Healthcare Data Analytics Programme** (Class C26-03), facilitated by Mark Olafare.

---

## 🎯 Business Problem

PrimeHealth ER faced:
- **Limited visibility** into patient flow and peak traffic periods
- **No tracking** of wait time trends over time
- **Fragmented insights** into admission, referral, and satisfaction patterns
- **No system** for evaluating doctor-level performance metrics

---

## 🛠️ Tools & Skills Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Analysis, pivot tables, charts, dashboard |
| HTML / CSS / JavaScript | Interactive web dashboard |
| Chart.js | Data visualisations |
| Python (openpyxl, pandas) | Excel workbook generation |

---

## 📊 Deliverables

### 1. Excel Workbook (`PrimeHealth_ER_Dashboard.xlsx`)
4 professionally designed sheets:

| Sheet | Contents |
|-------|---------|
| **ER_Data** | Full cleaned dataset (9,216 records) with formatted table |
| **Analysis** | 12 summary tables — KPIs, conditions, referrals, heatmap, demographics |
| **Dashboard** | 7 charts — admission, wait time, conditions, referrals, age, race, day of week |
| **Doctor_Analysis** | Top 20 doctor performance metrics + satisfaction chart |

### 2. Web Dashboard (`primehealth_er_dashboard.html`)
- Live KPI cards — total patients, avg wait, satisfaction, billing, LOS, admission rate
- Interactive filters — shift, admission, wait status, satisfaction, medical condition
- Patient flow heatmap — hour × day traffic matrix with heat colours
- 7 Chart.js visualisations
- Searchable and sortable patient records table
- Auto-generated insights panel

---

## 📐 Key Metrics (Full Dataset — 9,216 Patients)

| KPI | Value |
|-----|-------|
| Total ER Patients | 9,216 |
| Average Wait Time | 42.7 minutes |
| Average Satisfaction Score | 5.54 / 10 |
| Average Billing Amount | $7,497 |
| Average Length of Stay | 3.3 days |
| % Admitted | 50.04% |
| % Wait Delayed | 63.3% |
| % Dissatisfied | 59.1% |

---

## 💡 Key Insights

- **Seizures** is the most common condition (818 cases, 8.9%)
- **Saturday midnight (00–02)** is the single busiest ER slot across all days
- **63% of patients** experience delayed wait times — the most urgent improvement area
- **Night shift** handles the most volume (5,000 visits vs 1,941 Morning / 2,275 Afternoon)
- **General Practice** is the top referral department (1,840 referrals), but 5,400 patients (58.6%) receive no referral
- Satisfaction is nearly split: 30.8% Satisfied, 59.1% Dissatisfied, 10.1% Neutral

---

## 📁 Project Structure

```
primehealth-er-dashboard/
│
├── primehealth_er_dashboard.html    # Web dashboard (open in browser)
├── PrimeHealth_ER_Dashboard.xlsx    # Full Excel workbook with 4 sheets
├── README.md                        # This file
└── data/
    └── C26-03_Excel_2_Dataset.xlsx  # Original raw dataset
```

---

## 🚀 How to Run

**Web dashboard:**
```bash
open primehealth_er_dashboard.html    # macOS
start primehealth_er_dashboard.html   # Windows
```

**Excel dashboard:**  
Open `PrimeHealth_ER_Dashboard.xlsx` in Microsoft Excel → navigate to the **Dashboard** tab for charts.

---

## 🔗 Connect

- LinkedIn: [Audrey Tetteh](https://linkedin.com/in/audreytetteh)
- Portfolio: [yourwebsite.com](https://yourwebsite.com)

---

*Built with ❤️ by **Audrey Tetteh** as part of the 10Alytics Healthcare Data Analytics Programme*

`#HealthcareAnalytics` `#ExcelDashboard` `#DataAnalytics` `#ERAnalytics` `#WaitTimeAnalysis` `#DataVisualization` `#HospitalPerformance`
