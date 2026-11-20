# USA Sales Performance & Financial Health Dashboard (2014–2018)

An end-to-end exploratory data analysis and Power BI visualization of **64,000+ B2B sales transactions** across **175 companies** in the United States from 2014 to 2018. This project evaluates multi-year revenue trends, product profitability, distribution channel efficiency, and geographic market dynamics to guide executive decision-making.

---

## 📊 Executive KPI Summary

| Metric | Performance |
| :--- | :--- |
| **Total Revenue** | $1.24B |
| **Total Profit** | $461.80M |
| **Overall Profit Margin** | 37.36% |
| **Total Orders** | 64,000 |
| **Average Order Value (AOV)** | $19.28K |
| **Active Client Base** | 175 Companies |

---

## 🎯 Project Objectives & Northstar Metrics

* **Sales Trends:** Track multi-year revenue velocity, order volume, and Average Order Value (AOV) to identify cyclical seasonality and market anomalies.
* **Product Performance:** Evaluate revenue generation versus profit margin efficiency across SKUs to optimize product mix.
* **Channel Distribution:** Compare revenue share and margin stability across Wholesale, Distributor, and Export routes.
* **Geographic Insights:** Assess state- and region-level demand alongside localized cost structures and profit margins.

---
## 🔍 Key Analytical Findings

### 1. Sales Revenue & Seasonality (2014–2018)
<img width="989" height="602" alt="Screenshot 2026-11-13 085808" src="https://github.com/user-attachments/assets/f86bc31f-49cf-4a68-90d3-2b5afc899166" />

* **Consistent Baseline:** Monthly revenues oscillate steadily within a healthy **$22M–$26M** band across the four-year timeline, demonstrating predictable cyclical waves rather than random volatility.
* **Peak & Trough Anomalies:** Performance peaked in **March 2016 ($26M)**, whereas the sharpest downturn occurred in **February 2017 ($21M floor)**—followed immediately by an aggressive rebound back to **$26M in March 2017**, highlighting strong operational resilience.
* **Seasonal Cycles:** Revenue reliably dips every **January** (post-holiday cooldown) and surges during **May and June**.

---

## 🗂️ Data Structure & Modeling

The Power BI data model follows a star-schema architecture comprising **5 relational tables** across **64,000 transaction records**:
* **Fact Table:** `Sales Data` (64,000 rows)
* **Dimension Tables:** `Product`, `Customer`, `Region`, `State`

<img width="859" height="489" alt="Screenshot 2026-11-13 085251" src="https://github.com/user-attachments/assets/6601ef1a-248e-439b-ba8a-08f7814c581f" />

---

### 2. Product Performance (Volume vs. Margin)
<img width="324" height="263" alt="Screenshot 2026-11-13 092104" src="https://github.com/user-attachments/assets/1cb62a70-a49a-4aad-8596-f268feaa29a8" />
<img width="317" height="259" alt="Screenshot 2026-11-13 092026" src="https://github.com/user-attachments/assets/b218a0f7-1117-4bc7-9405-4447543ec493" />

* **Top Revenue Driver:** **Product 26** leads overall top-line performance, consistently generating **$117.3M** year-over-year.
* **Margin Leaders:** While Product 25 drives scale, **Product 9 (40.03%)**, **Product 30 (39.05%)**, and **Product 28 (38.94%)** deliver the highest profit margin efficiency.
* **Underperformer:** **Product 3** generates the lowest revenue across the catalog and requires portfolio review.

### 3. Channel Dominance & Efficiency
<img width="957" height="197" alt="Screenshot 2026-11-13 092233" src="https://github.com/user-attachments/assets/29bf9001-7648-492f-9169-3e931e5cb77d" />

* **Wholesale Backbone:** **Wholesale** is the primary engine of the business, commanding **54.06% of total revenue ($668.20M)** and **53.56% of total profit ($247.30M)**.
* **Consistent Route Efficiency:** Profit margins remain tightly balanced across all channels—**Wholesale (38.01%)**, **Distributor (37.65%)**, and **Export (37.02%)**—proving that operational cost structures scale predictably with volume.

### 4. Geographic & Account Insights
* **Top 5 States by Revenue:** **California ($228.79M)** dominates national sales—more than doubling runner-up **Illinois ($111.05M)**, followed by **Florida ($90.20M)**, **Texas ($84.01M)**, and **New York ($55.53M)**.
* **Regional Revenue vs. Margin Twist:** While the **Midwest** and **West** command massive scale, regional profit margins vary noticeably (ranging from **27% to 46%**), indicating localized logistics and fulfillment cost disparities.

---

## 🚀 Strategic Recommendations

1. **Protect Core Revenue Drivers:** Safeguard supply chain continuity and inventory availability for flagship SKUs (**Product 25** and **Product 26**) while conducting a root-cause audit on the **February 2017** revenue dip to prevent future Q1 disruptions.
2. **Cross-Sell High-Margin SKUs via Wholesale:** Introduce tiered product bundling to push high-margin leaders (**Product 9** and **Product 30**) through the high-volume **Wholesale** channel, capitalizing on its 38.01% margin stability.
3. **Protect & Upsell High-Margin Accounts:** Prioritize executive account management and expansion strategies for top-margin clients such as **Neutrogena Ltd** and **Avamba Company** (44%–45% margins).
4. **Optimize Regional Logistics & Replicate Midwest Playbook:** Audit fulfillment and distribution nodes in high-volume markets (**California, Illinois, Florida**) to prevent logistics costs from eroding regional margins, while scaling the **Midwest's** operational model into underperforming regions.

---

## 🛠️ Tools & Technologies
* **Power BI Desktop:** Data modeling (Star Schema), DAX measures, and interactive executive dashboards.
* **Data Cleaning & ETL:** Power Query.

---

## 📸 Dashboard Preview

<img width="997" height="561" alt="executive" src="https://github.com/user-attachments/assets/bb83310a-aa22-4e51-9a3d-770e25f68238" />
<img width="998" height="563" alt="product main" src="https://github.com/user-attachments/assets/67c98feb-3be8-42c0-b12c-d800b7960610" />
<img width="994" height="562" alt="geo" src="https://github.com/user-attachments/assets/16c569ff-da4a-41ba-95d5-a1cf72990c5b" />



