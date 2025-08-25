# Executive Summary (1 page)

**Objective:** Build a simple, data-driven FP&A forecast for a simulated SaaS business.

**Key Findings:**
- Revenue shows a steady upward trend with mild seasonality.
- Gross margin improves over time due to declining COGS%.
- Operating margin remains negative but trending toward breakeven.
- Cash runway is approximately _X_ months at current burn.

**Recommendations:**
- Accelerate net revenue retention by reducing churn and increasing expansion.
- Monitor S&M efficiency (CAC payback) and R&D productivity.
- Consider a modest pricing/packaging update to lift ARPA.

---

# Analysis (1 page)

## Data & Methodology
- **Data**: Synthetic monthly dataset (2022-01 to 2025-07).
- **Approach**:
  - Time-series forecast of Revenue using Exponential Smoothing (Holt-Winters).
  - Forecast COGS using a % of Revenue model with a mild improving trend.
  - Forecast OpEx using driver-based assumptions (headcount × cost per employee) and a simple time-series model as a cross-check.
  - Compute Operating Income, Cash Flow, and Cash Balance.
  - Run three scenarios: Base, Upside, Downside.

## Highlights
- Chart: Revenue (Historical vs. Forecast)
- Chart: OpEx by Function
- Table: Scenario Summary (Revenue, Gross Margin %, Operating Margin %, Months of Runway)

---

# Insights & Actions (≤1 page)

- **Pricing & Packaging**: Evaluate ARPA uplift opportunities with minimal churn impact.
- **Churn Reduction**: Prioritize customer success motions in at-risk segments.
- **Hiring Plan**: Align R&D and S&M hiring with growth efficiency (LTV/CAC, payback).
- **Cash Planning**: If downside materializes, consider a 10–15% OpEx rebalance to extend runway.

> Notes: Replace placeholder “_X_” values with those from your model. Insert charts exported from the notebook (`output/` folder).
