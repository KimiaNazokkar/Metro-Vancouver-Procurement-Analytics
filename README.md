# Metro Vancouver Procurement Analytics
### A governed procurement intelligence project — Python ETL pipeline · Tableau dashboards · 2023– March 2026
---
## Project Summary
This project analyzes Metro Vancouver's publicly disclosed procurement award data from 2023 through March 2026 to examine procurement spending patterns, supplier concentration, competition structure, and market participation across a major regional public utility.

The project covers the full analytical lifecycle: automated PDF extraction, multi-stage data cleaning and normalization, vendor entity resolution, data quality governance, and a four-dashboard Tableau analytics suite designed for executive and operational audiences.

The final governed dataset contains 2,133 vendor-competition records representing 679 awarded competitions and $4.7B in disclosed procurement activity between 2023 and March 2026.

> **Data source:** Metro Vancouver Awarded Bids Register (public procurement records published by Metro Vancouver)
> Official source: https://metrovancouver.org/bidding-opportunities/awarded-bids
---
## Key Findings

### 1. Metro Vancouver disclosed $4.7B in procurement activity across 679 awarded competitions
Metro Vancouver's Awarded Bids Register discloses approximately $4.7B in procurement spending across 679 awarded competitions between 2023 and March 2026. This represents the full disclosed procurement footprint of a major regional public utility operating across water, wastewater, solid waste, and regional parks infrastructure. The governed analytical dataset contains 2,133 vendor-competition records representing 494 normalized suppliers, providing visibility into supplier participation, competition outcomes, and procurement activity across the organization.

### 2. Eleven vendors account for half of normalized procurement spending
Across 494 active suppliers, the top 11 vendors collectively represent approximately 50% of normalized procurement spending. The largest supplier accounts for approximately 11.4% of normalized spend. Most leading vendors appear in only one reporting year, suggesting that concentration is driven primarily by individual large contract awards rather than persistent supplier dominance.

### 3. Single-bidder participation peaked in 2024
Across competitive procurement instruments, 21.9% of competitions received only one vendor response during the study period. The rate peaked at 28.2% in 2024 before declining to 17.5% in 2025, meaning that more than one in four competitive procurements received a single bid at the peak of the study period.

### 4. Direct awards increased from 15.7% to 51.9% of competitions
Direct award competitions represented 15.7% of competitions in 2023 and 51.9% of competitions in the partial 2026 reporting period. Direct awards are a legitimate procurement instrument and may reflect sole-source requirements, emergency procurement, standing agreements, contract renewals, or other operational considerations.

### 5. Deep bidder participation was the exception rather than the norm
Among competitive procurements with recorded bidder counts, 100 competitions received a single bid, 110 received two bids, and 102 received three bids. Competitions attracting six or more bidders represented a minority of the competitive procurement portfolio, indicating that deep market participation was the exception rather than the norm — limiting competitive price discovery for a meaningful share of procurement activity across the study period.

---
## Dashboard Suite

The analytical results are presented through a four-dashboard Tableau suite designed for executive, operational, and governance audiences.

### Dashboard 1 — Executive Summary

Provides a high-level view of Metro Vancouver's procurement portfolio, including total awarded spend, a normalized baseline that excludes two generational infrastructure projects to enable operational comparison, competition outcomes, supplier participation, and year-over-year spend trends.

<img width="1200" height="800" alt="Executive Summary" src="https://github.com/user-attachments/assets/af1a2388-8034-4f1e-867c-3e3a01e3bed5" />

---

### Dashboard 2 — Vendor Concentration & Supplier Dependence

Examines supplier concentration, vendor rankings, cumulative spend concentration, and supplier recurrence across reporting years. The concentration curve highlights the degree to which procurement spending is concentrated among a relatively small group of suppliers.

<img width="1200" height="800" alt="Vendor Concentration   Supplier Dependence" src="https://github.com/user-attachments/assets/7bf715e3-b178-41d4-b379-8abae4ea22bb" />

---

### Dashboard 3 — Competition Structure & Bid Depth

Analyzes procurement instrument mix, direct award utilization, bidder participation, single-bidder rates, and bidder depth distributions. Tracks direct award utilization over time, bidder depth distributions, and single-bidder rates by year and competition type — including a 2024 peak in which more than one in four competitive procurements received a single vendor response.

<img width="1200" height="800" alt="Competition Structure   Bid Depth" src="https://github.com/user-attachments/assets/7069349e-6f4d-471d-ad41-bb7eaf595012" />

---

### Dashboard 4 — Methodology & Data Governance

Documents analytical methodology, KPI definitions, data lineage, known data quality items, governance controls, limitations, and reproducibility considerations supporting the analysis.

<img width="1200" height="800" alt="Methodology   Data Governance" src="https://github.com/user-attachments/assets/b7c604b0-4738-4a2e-accc-1745c32151fd" />

---
