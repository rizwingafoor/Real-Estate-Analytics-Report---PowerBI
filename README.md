# 🏙️ Real Estate Analytics Report — Power BI Dashboard

A comprehensive Power BI dashboard analyzing real estate performance across **5 major US cities** — New York, Miami, Los Angeles, Chicago, and Houston.

---

## 📌 Project Overview

This dashboard transforms raw real estate transactional data into actionable business intelligence. It covers **5 interconnected data domains** — Properties, Clients, Agents, Sales, and Visits — enabling data-driven decisions across the entire sales funnel.

| Dataset | Records |
|---|---|
| Properties | 1,000 |
| Clients | 1,500 |
| Agents | 100 |
| Sales Transactions | 2,000 |
| Property Visits | 5,000 |

Real estate dataset representing business operations across 5 major US cities. **Time Period: 2023 – 2025**

**Cities Covered:** New York · Miami · Los Angeles · Chicago · Houston  
**Property Types:** Apartment · Villa · Retail · Warehouse · Office

---

## 🧩 Data Model

This project adopts a **Star Schema** structure with two Fact Tables and four Dimension Tables.


| Component | Details |
|---|---|
| **Fact Tables** | Sales and Visits — store all transactional data |
| **Dimension Tables** | Properties, Agents, Clients, Date — provide context and filtering |
| **Relationships** | One-to-many connections via surrogate keys |
| **Shared Date Dimension** | Connected to both fact tables for consistent time-based analysis |


---

## 🗂️ Dashboard Structure

Each page is connected via a shared navigation sidebar and filter panel (Year, Month, Property Type, Location) for seamless cross-page analysis.

| Page | Title | What It Shows |
|---|---|---|
| 1 | **Sales Overview** | Revenue KPIs, YoY trend, weekend vs weekday split, monthly performance |
| 2 | **Visit Analysis** | Visit volume, location & property type breakdown, price segment visits, size impact |
| 3 | **Agent Overview** | Top agents by revenue & sales count, tier distribution, visits per agent |
| 4 | **Agent Performance** | Full agent ranking table with revenue, clients, and closed deals |
| 5 | **Property Portfolio** | Property count by type and location, price distribution, size segments, top expensive properties |

---

## 💡 Key Insights

### Sales Performance
- **$1.5B total revenue** across 2023–2025 in 5 US cities
- **21.4% YoY growth** — from $474M in 2023 to $793M in 2024 (2025 is partial)
- **40% visit-to-sale conversion rate** across 2,000 closed deals
- **71.9% of sales close on weekdays** — clear weekday-dominant pattern

### Visit Highlights
- **56.8% YoY visit growth** — 5,000 total visits, avg 5.05 per property
- **Miami leads** with 1,052 visits; Houston trails at 945
- **Apartments are the most visited** property type at 1,079 visits
- **Larger properties (350–500 m²)** attract 3× more visits than properties under 80 m²
- **$100K–$200K price segment** has the highest visit volume (615) — strong entry-level demand

### Agent Insights
- Top 6 agents (6% of workforce) account for a disproportionate share of revenue — classic 80/20 pattern
- **Elite agents make up only 11%** of the workforce — significant upskilling opportunity

| Agent | Revenue | Deals |
|---|---|---|
| Samantha Vargas ⭐ | $24.2M | 28 |
| Francisco Williams | $24.2M | 29 |
| Gordon Wilson | $23.3M | 28 |
| Robert Miller | $21.4M | 23 |
| Mark Lopez | $21.0M | 24 |
| Laura Martin | $20.9M | 25 |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development & data modelling
- **DAX** — Measures, KPIs, YoY calculations, time intelligence
- **Star Schema** — Data modelling approach
- **Power Query** — Data transformation and loading
