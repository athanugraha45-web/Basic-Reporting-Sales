# Basic-Reporting-Sales
I created a simple project about sales results. In creating this project, I used Microsoft Excel to clean and process the data. I used POWER BI for data visualization. I generated graphs to analyze the results obtained.

# Makeup Sales Dashboard - Portfolio
**Role:** Data Analyst / Market Analyst
**Tools Used:** Power BI, Microsoft Excel

## Project Summary
Interactive sales dashboard showing GMV, top products, customer segments, and city level performance for a beauty store.

## Dataset Used
- <a href="https://github.com/athanugraha45-web/Basic-Reporting-Sales/blob/main/DummyDataExcel_TokoKecantikan.xlsx"> Dataset</a>

# Detailed Analysis — Makeup Sales Dashboard

This document records observations, insight, data checks and an action plan produced from the dashboard.

## Executive summary
- GMV: $322M — confirm net/gross & period.
- Average Rating: 2.98 — urgent: investigate root causes across product/platform/fulfillment.
- Buyer: ~80% female — strong signal for targeted marketing.
- Cities: mix of urban and remote high performers — check profitability by city.
- Platforms: revenue spread; focus on platform-level KPIs.
- Products: several top SKUs; opportunity for Pareto analysis & bundling.

## Per-chart analysis and recommended actions

### 1) Total Sales (KPI)
**Insight:** High GMV indicates traction.
**Data checks:** Verify if Net Sales (after returns) or Gross. Ensure timespan.
**Actions (Immediate):**
- Add Orders count, Unique Customers, AOV, Return Rate to dashboard.

### 2) Average Customer Rating (2.98)
**Insight:** Rating below 3 indicates problems (product quality, delivery, service).
**Actions (URGENT):**
- Extract recent low-rating orders (rating <=3) for manual review.
- Correlate low ratings with product_id, platform, city, courier.
- Run text mining on reviews and implement remediation (refunds, replacements).

### 3) Buyer by Gender
**Insight:** 80% female — tailor marketing & product display to female consumers.
**Actions:**
- Run female-targeted campaigns and measure uplift in conversion and AOV.

### 4) Most Purchased City
**Insight:** Yogyakarta & Surabaya top cities; remote cities also contribute.
**Actions:**
- Compute GMV per order & margin by city; evaluate fulfillment costs for remote regions.
- Consider local hubs or pickup options if margin suffers.

### 5) Total Sales by Platform
**Insight:** No single dominant channel — diversify optimizations.
**Actions:**
- Compute platform-level ROAS, CAC, conversion rate & returns.
- Run A/B promotions on channels with best CPA/ROAS.

### 6) Top Selling Product
**Insight:** Top SKUs units are close; assess GMV contribution and margins.
**Actions:**
- Pareto (top 20% by GMV) analysis.
- Create bundles & cross-sell opportunities; prioritize inventory for top GMV items.

- Dashbaord Interaction <a href="https://github.com/athanugraha45-web/Basic-Reporting-Sales/blob/main/Contoh%20Report%20Sales.pbit">View Dashborad </a>
