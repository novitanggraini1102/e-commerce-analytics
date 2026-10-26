# Home Goods E-commerce Analytics: End-to-End Data Analyst Project

An evidence based analysis of two years of online-store orders (Jan 2024 - Dec 2025): data audit, cleaning, SQL cross-check, statistical analysis, executive report, slide deck and an interactive dashboard.

## Business problem
Where is the business growing, where is it leaking value, and what should it do next? Questions: growth drivers, product and category performance, returns, customer value, acquisition-channel quality, promotions.

## Key findings (all verified from the data; see `reports/analytical_report.pdf`)
- Revenue $1,881,974 over two years; **+21.2% in 2025** (74% volume/mix, 28% from a 5% price rise).
- **Furniture returns** 12.1% of lines vs 4.6% elsewhere (p<0.001): 33% of returned value from 17% of revenue.
- **Paid social** is 23% of customers but 13% of revenue; 44% ever buy vs 59%-68% in main channels (spend data absent, so profitability is unknown).
- **Growth is acquisition-led**: active buyers +92%, revenue per buyer -37%.
- **Promotions**: HOLIDAY20 orders earn 37.9% margin vs 50.4% undiscounted; incremental effect untested.
- Null results reported: no free-shipping-threshold effect, no payment-method difference in cancellations.

## Tools
Python (pandas, SciPy, matplotlib, ReportLab), SQL (SQLite), pptxgenjs deck, pytest. Power BI.

## Data
Four CSVs: customers (3,600), orders (9,245 raw / 9,207 clean), order_items (15,608), products (90). Provenance/licence undocumented; no personal data. Put files in `data/raw/` (see its README).

