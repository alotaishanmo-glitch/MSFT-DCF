# MSFT DCF Valuation Model — Microsoft Corporation

Institutional-grade equity research valuation model built in Excel using 
SEC EDGAR 10-K data (FY2022–FY2024).

## Model Structure (9 Sheets)
- **Historicals** — Income statement, FCF bridge (FY2022–FY2024)
- **Assumptions** — Bear/Base/Bull scenario toggle, all key inputs with rationale
- **Projections** — 5-year financial projections driven by Assumptions sheet
- **DCF Valuation** — WACC build (CAPM), mid-year discounting, terminal value
- **Sensitivity** — 2D sensitivity table (WACC × TGR), implied EV/EBITDA
- **Comps** — Trading comps: GOOGL, AAPL, CRM, ORCL, ADBE
- **Summary** — Football field chart data, 12-month price target, verdict
- **Investment Memo** — Formal research note with scenario analysis & risk flags
- **Segments** — Azure vs M365 vs Other revenue segmentation

## Key Output
| Metric | Value |
|---|---|
| Implied Share Price (Base) | $327 |
| Market Price | $420 |
| Implied Upside / (Downside) | -22% |
| Verdict | STRONG SELL |
| WACC | 9.0% |
| Terminal Growth Rate | 3.0% |

## Methodology
- Unlevered Free Cash Flow (UFCF) discounted at WACC
- Mid-year convention
- Gordon Growth Model terminal value
- CAPM-derived WACC (Rf=4.38%, ERP=5.5%, β=0.9)
- Comparable company analysis with EV/EBITDA and P/E cross-check

*Built by Abdulrahman AlOtaishan — BSc Accounting & Finance, King's College London*
*For analytical and educational purposes only. Not investment advice.*
