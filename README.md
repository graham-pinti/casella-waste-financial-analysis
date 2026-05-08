# Casella Waste Systems: Financial Analysis (CWST)

An independent financial analysis of Casella Waste Systems, Inc. (NASDAQ: CWST) 
built from publicly available SEC filings. This project examines the apparent 
contradiction between Casella's strong operational growth and declining GAAP net 
income, and explains why understanding the difference matters for evaluating 
acquisition-driven companies.

> **Data Source:** All figures sourced from Casella Waste Systems' 10-K Annual Report 
> (FY2025, filed February 20, 2026) and 8-K Earnings Release (February 19, 2026), 
> both publicly available via SEC EDGAR. No proprietary or non-public information 
> was used.

## Overview

Casella Waste Systems is a regional, vertically integrated solid waste company 
headquartered in Rutland, Vermont, operating across eleven states in the Northeast. 
Since 2018, Casella has acquired 76 businesses representing over $925M in annualized 
revenue, quite an aggressive land-grab strategy designed to build a dominant regional 
network before competitors can replicate it.

This project analyzes whether that strategy is working, what it costs on the income 
statement, and what the numbers actually mean for the health of the business.

## The Central Analytical Question

In FY2025, Casella grew revenue 18.0% and Adjusted EBITDA 17.3%, which are strong numbers by 
any measure. Yet GAAP Net Income fell 41.9%. How can a company grow strongly and 
see profits collapse simultaneously?

This project answers that question.

## Analytical Questions

1. What is driving the gap between GAAP Net Income and Adjusted EBITDA?
2. Is Casella's declining net income a sign of business deterioration or an 
accounting artifact of acquisition activity?
3. How has D&A expense grown relative to revenue, and what does that imply for 
future profitability?
4. What does Casella's acquisition strategy look like at scale, and what risks does 
it carry?
5. What does FY2026 guidance imply about the trajectory of the business?

## Key Findings

| Metric | FY2024 | FY2025 | YoY Change |
|---|---|---|---|
| Revenue | $1.557B | $1.837B | +18.0% |
| Adjusted EBITDA | $360.6M | $422.8M | +17.3% |
| GAAP Net Income | $13.5M | $7.9M | -41.9% |
| D&A Expense | $234.9M | $306.8M | +30.6% |
| Adjusted Free Cash Flow | $158.3M | $179.9M | +13.6% |

**The answer to the central question:** D&A expense grew $71.9M (+30.6%) in FY2025, 
nearly 10x the decline in net income ($5.7M). This is a non-cash accounting charge 
driven entirely by acquisition activity, not operational deterioration. The underlying 
business is healthy. GAAP earnings are being obscured by the accounting treatment of 
an aggressive M&A strategy.

**FY2026 guidance** of $1.97–1.99B revenue and $455–465M Adjusted EBITDA implies 
meaningful growth deceleration (~8–9% vs 18% in FY2025), suggesting Casella may be 
shifting emphasis from acquisition volume toward integration and organic execution.

## Workbook Structure

- **Summary Dashboard** — KPI scorecard and six analytical findings
- **Revenue & EBITDA Trend** — Three-year trend with YoY variance analysis and 
FY2026 guidance range
- **GAAP vs Adjusted Reconciliation** — Line-by-line walk from revenue to net income 
to Adjusted EBITDA, explaining each adjustment
- **Acquisition Analysis** — M&A volume, D&A burden, balance sheet impact, and 
risk register
- **FY2026 Outlook** — Guidance vs. historical trend with growth moderation analysis

## Key Terms

- **EBITDA (Earnings Before Interest, Taxes, Depreciation & Amortization)** — A 
measure of core operating profitability that removes non-cash and financing charges. 
Preferred over net income for evaluating acquisition-heavy companies.
- **Adjusted EBITDA** — EBITDA further adjusted to exclude one-time or non-recurring 
items such as acquisition transaction costs.
- **D&A (Depreciation & Amortization)** — Non-cash accounting charges that spread 
the cost of acquired physical assets (depreciation) and intangible assets like customer 
contracts (amortization) across their useful lives.
- **Free Cash Flow (FCF)** — Cash generated after capital expenditures. Often a more 
reliable indicator of business health than GAAP net income for capital-intensive, 
acquisition-driven businesses.
- **Net Leverage Ratio** — Total net debt divided by Adjusted EBITDA. Measures 
debt load relative to earnings capacity. Casella's 2.34x ratio is considered 
conservative for an acquisitive company.
- **GAAP** — Generally Accepted Accounting Principles. The standard accounting 
framework required for public company reporting in the US.
- **Goodwill** — The premium paid above book value when acquiring a company, 
recorded as an asset on the balance sheet.
- **Vertical Integration** — Owning multiple stages of the supply chain — in 
Casella's case, collection routes, transfer stations, and landfills — which drives 
cost efficiency and competitive moats.

## Tools Used

Excel — financial modeling, multi-year trend analysis, GAAP reconciliation, 
variance analysis, KPI dashboard

## Data Sources

- Casella Waste Systems 10-K Annual Report, FY2025 (filed February 20, 2026) — SEC EDGAR
- Casella Waste Systems 8-K Earnings Release, February 19, 2026 — SEC EDGAR
