# 🏕️ Category Revenue Performance Dashboard

This is an interactive Power BI report analyzing revenue, profitability, and sales channels across three product categories — **Camping Equipment**, **Mountaineering Equipment**, and **Outdoor Protection** — selectable via a chiclet slicer at the top of the report.

---

## 📑 Table of Contents

1. Project Overview
2. Business Problem
3. Project Objectives
4. Datasets
5. Dashboard Preview
6. KPIs
7. Business Questions & Insights
8. Business Insight
9. Strategic Recommendations
10. Future Improvements

---

## 📌 Project Overview

This project is a single-page Power BI dashboard covering three related product lines — **Camping Equipment**, **Mountaineering Equipment**, and **Outdoor Protection**. A chiclet slicer at the top lets the user click between the three categories, and every visual on the page — KPIs, monthly trend, top products, urgency split, retailer city table, and retailer type chart — updates instantly to reflect the selected category.

The report is also filterable by **Year**, so a stakeholder can move from a company-wide category view down to a specific month, product, or retailer city in a few clicks. The screenshot and figures in this document capture the dashboard with **Outdoor Protection** selected as the example view; the same layout and logic apply when Camping Equipment or Mountaineering Equipment is selected instead.

## ❗ Business Problem

Revenue across the Camping, Mountaineering, and Outdoor Protection lines is generated across many products, retailer cities, and channel types, making it hard for the business to answer questions like:

- Is revenue growing or shrinking month to month, and is that seasonal — and does it differ by category?
- Which products are actually driving revenue and profit within each category?
- Are customers buying proactively or only when the need is urgent?
- Which retailer cities and retailer types deserve more marketing and inventory investment?

Without a consolidated, category-switchable view, decisions on assortment, channel, and regional investment were being made without clear visibility into where revenue and profit were actually concentrated in each product line.

## 🎯 Project Objectives

- Track core financial performance: Revenue, COGS, Profit, and Profit Margin — for any of the three categories via the chiclet slicer.
- Identify the top-performing products within each selected category.
- Understand seasonality in monthly revenue by category.
- Segment revenue by purchase urgency (urgent vs. non-urgent) to understand buying behavior.
- Benchmark performance across retailer cities and retailer types.
- Provide a single, filterable view (by Year and Category) for self-service exploration.

## 🗂 Datasets

The report is built from retail sales data for outdoor and camping-related product categories. Core data points include:

| Table / Entity | Key Fields |
|---|---|
| **Sales / Orders** | Product Name, **Category (Camping Equipment / Mountaineering Equipment / Outdoor Protection)** — drives the chiclet slicer, Revenue, COGS, Profit, Month, Year |
| **Retailers** | Retailer City, Retailer Type, Revenue, Profit |
| **Purchase Context** | Urgency (Urgent / Not Urgent), Revenue by Method type |

## 🖼 Dashboard Preview

*Shown with the **Outdoor Protection** chiclet selected — clicking Camping Equipment or Mountaineering Equipment refreshes every visual on the page for that category instead.*

![Revenue Dashboard – Outdoor Protection view](Revenue-report-dashboard.png)

## 📊 KPIs

*Figures below reflect the **Outdoor Protection** category (the chiclet selected in the preview above). Selecting a different category updates these KPIs accordingly.*

| KPI | Value (Outdoor Protection) |
|---|---|
| Revenue | $7.51M |
| COGS | $2.86M |
| Profit | $4.65M |
| Profit Margin % | 61.91% |

## ❓ Business Questions & Insights

*The findings below are drawn from the **Outdoor Protection** chiclet as a worked example. The same questions can be asked of Camping Equipment or Mountaineering Equipment by clicking their chiclet instead.*

**1. Which month drives the most revenue?**
July is the peak month at $0.74M, with revenue trending steadily downward through the year to a low of $0.49M in September — a clear seasonal pattern.

**2. Which product leads the Outdoor Protection category?**
The top product (Bugshield) generates $1.75M — more than double the next best performer, Sun Shelter 30 ($0.86M).

**3. Are purchases mostly urgent or planned?**
Non-urgent purchases dominate at $4.93M (65.6%) versus $2.58M (34.4%) for urgent purchases — most customers are buying proactively rather than reactively.

**4. Which retailer cities perform best?**
Calgary leads with $259,029 in revenue and $165,093 in profit, followed by Beijing ($236,464 revenue / $141,282 profit) and Berlin ($188,426 revenue / $120,133 profit).

**5. Which retailer type contributes the most revenue?**
Warehouse Store leads at $2.25M, ahead of Direct Marketing ($1.79M), Outdoors Shop ($1.36M), and Sports Store ($1.33M).

## 💡 Business Insight

- **Strong profitability.** A 61.91% profit margin signals healthy pricing power and cost control in the Outdoor Protection category.
- **Clear seasonality.** Revenue peaks in July and steadily declines into September, suggesting demand is tied to the outdoor/camping season rather than staying flat year-round.
- **Product concentration risk.** The top product alone accounts for a disproportionate share of top-10 product revenue, meaning a supply or demand shock to that single product would meaningfully impact category revenue.
- **Buying behavior is planned, not reactive.** With roughly two-thirds of revenue coming from non-urgent purchases, customers are largely stocking up ahead of need rather than buying in an emergency.
- **Warehouse stores are the primary channel**, generating more revenue than Direct Marketing, Outdoors Shops, and Sports Stores combined with room to grow in the smaller channels.

## 🧭 Strategic Recommendations

1. **Plan inventory and promotions ahead of the July peak.** Build pre-season marketing pushes in the months leading up to peak demand, and manage stock levels to avoid mid-season shortages.
2. **Reduce single-product dependency.** Actively promote mid-tier products (Sun Shelter 30, Bugshield Natural) to diversify revenue away from the top SKU.
3. **Lean into planned-purchase behavior.** Since most buying is non-urgent, use early-bird discounts and bundle offers to pull forward purchases before peak season.
4. **Prioritize investment in top retailer cities.** Calgary and Beijing are the strongest performers — consider loyalty programs or expanded shelf space in these markets.
5. **Grow underweight channels.** Warehouse Store leads by a wide margin; test targeted campaigns to lift Direct Marketing, Outdoors Shop, and Sports Store performance.

## 🚀 Future Improvements

*Longer-term moves the business could pursue based on what this dashboard reveals — beyond the immediate actions in Strategic Recommendations above.*

- **Reduce seasonal dependency** by expanding into complementary outdoor categories (e.g., winter or water sports gear) that peak in different months than the current July high point.
- **Cut product concentration risk** by developing 2–3 more "hero" products so the category isn't overly reliant on a single SKU for revenue.
- **Build a direct-to-consumer channel** (e-commerce/DTC) to complement Warehouse Store and Direct Marketing, capturing more margin and first-party customer data.
- **Launch a loyalty or subscription program** aimed at the ~66% of customers who buy proactively, encouraging repeat, pre-season purchases rather than one-off transactions.
- **Deepen presence in underperforming but promising retailer cities** — use Calgary and Beijing's success as a playbook for cities further down the list.
- **Explore private-label or bundled outdoor-protection kits** to improve margin further on top of the already-strong 61.91% profit margin.
- **Strengthen supplier partnerships** to secure better costs and supply reliability heading into the seasonal peak, protecting margin during ramp-up months.
- **Test category cross-selling** (e.g., bundling Outdoor Protection items with Camping Equipment purchases) to lift average order value across categories.

---

*Built with Power BI · Chiclet slicer for Camping Equipment / Mountaineering Equipment / Outdoor Protection, filterable by Year, with drill-down visuals for monthly trend, top products, urgency, retailer city, and retailer type.*
