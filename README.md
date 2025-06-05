# Manufacturing Performance Dashboard  
*Official Submission – Emerson x DAPH National Data Challenge 2025*

![Power BI](https://img.shields.io/badge/Built with-Power%20BI-darkblue) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

A Power BI report that transforms raw production data into clear, actionable insights for real-time plant operations.  
Created as my first Power BI competition entry—with guidance from **DataSense Analytics** and the **Data Analytics Philippines** community.

---

## ✨ Key Features
| Section | What It Shows | Why It Matters |
|---------|---------------|----------------|
| **Header & Slicers** | Report date range, plant / line filters | One-click navigation |
| **Single Big Numbers (SBNs)** | Total batches, production time, downtime, avg. batch time, overall efficiency | Instant health check |
| **Production Analysis** | Batch trends, top SKUs, flavor mix | Spot demand patterns |
| **Operator Analysis** | Batches, downtime, efficiency per operator | Identify top & low performers |
| **Downtime RCA** | Product downtime, downtime factors, operator-factor heatmap | Pinpoint root causes |
| **Current vs Target** | Live production rate vs 80 % goal | Track progress toward optimal efficiency |

---

## 📊 Main KPIs
- **Total Downtime** and **Downtime by Product / Factor / Operator**  
- **Current Production Rate** vs **80 % Target**  
- **Average Batch Time** & **Operator Efficiency**

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling & visualizations |
| **DAX** | Custom measures (efficiency %, downtime calculations) |
| **Python (optional)** | Pre-processing CSVs (Jupyter) |

---

## 🔥 Insights Delivered
1. **Batch Change** and **Machine Adjustment** are the top downtime drivers.  
2. **CO 600** records the highest product downtime—priority for process review.  
3. **Mac** (batch tasks) and **Charlie/Dennis** (machine tasks) show the largest operator downtime gaps.  
4. Reaching the **80 % line-efficiency benchmark** requires cutting ≤ 494 minutes of downtime per 2 470-minute batch.

---

