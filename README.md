# Reliance Industries Ltd: Equity Valuation (DCF · Trading Comps · SOTP)

Three-method valuation of Reliance Industries (NSE: RELIANCE) built in Excel from FY2022-FY2026 consolidated annual-report data. Academic project, not investment advice.

| | |
|---|---|
| Valuation date | 22 Oct 2026 |
| Share price | ₹1,184.5 |
| Market capitalisation | ₹16,02,921 cr |
| Net debt (FY2026) | ₹1,24,717 cr (0.6x EBITDA) |
| Enterprise value (market) | ₹17,27,638 cr |

## Executive summary
- The three methods bracket the market value rather than converge on it: base-case DCF is **55% below** market cap and SOTP is **30% above**.
- DCF is dominated by terminal value (**77% of EV**), so the result is driven by WACC, terminal growth and terminal reinvestment, not by the five forecast years.
- Reliance trades at **8.3x EV/EBITDA** against peers at 3.9x (Indian Oil), 10.0x (Bharti Airtel) and 37.0x (DMart). The peer spread is too wide for a single multiple to anchor the valuation.
- The model's known weak points (terminal-year reinvestment, placeholder WACC, unvalidated SOTP multiples) are listed below with planned fixes.

## Business and historical performance
FY2026 segment revenue mix (before eliminations): Oil-to-Chemicals 50.4% · Retail 28.2% · Digital Services 13.4% · Other 6.1% · Oil & Gas 1.8%.

| ₹ crore | FY2022 | FY2026 | 4-yr CAGR |
|---|---|---|---|
| Gross revenue | 7,88,743 | 11,75,919 | 10.5% |
| EBITDA | 1,23,684 | 2,07,911 | 13.9% |
| EBITDA margin | 15.7% | 17.7% | |

## Valuation summary (₹ crore)
| Method | Equity value | vs market cap |
|---|---|---|
| DCF (base case) | 7,16,044 | -55% |
| SOTP | 20,77,051 | +30% |
| Market capitalisation | 16,02,921 | |

## DCF
**Base case:** revenue growth 8% (FY2026 actual ~9.8%) · EBITDA margin 17.5% · tax 25% · capex 10.5% and D&A 4.9% of revenue · working capital 5% of revenue growth · WACC 10% · terminal growth 4% · explicit forecast FY2027E-FY2031E.

Unlevered FCF rises from ₹44,191 cr (FY2027E) to ₹60,121 cr (FY2031E). Enterprise value of ₹8,40,761 cr less net debt of ₹1,24,717 cr gives equity value of ₹7,16,044 cr.

**Sensitivity: equity value (₹ crore), WACC × terminal growth**

| WACC \ g | 2% | 3% | 4% | 5% | 6% |
|---|---|---|---|---|---|
| 9% | 6,43,684 | 7,45,093 | 8,87,064 | 11,00,022 | 14,54,951 |
| 10% | 5,44,945 | 6,18,273 | **7,16,044** | 8,52,923 | 10,58,241 |
| 11% | 4,68,232 | 5,23,238 | 5,93,959 | 6,88,254 | 8,20,266 |
| 12% | 4,06,935 | 4,49,389 | 5,02,456 | 5,70,685 | 6,61,657 |
| 13% | 3,56,846 | 3,90,368 | 4,31,338 | 4,82,552 | 5,48,397 |

No cell in the grid reaches the market cap, which points to the terminal cash flow rather than the discount rate (see limitations).

## Trading comparables
| Company | EV/Revenue | EV/EBITDA |
|---|---|---|
| **Reliance** | 1.47x | 8.31x |
| Indian Oil | 0.33x | 3.88x |
| Bharti Airtel | 5.73x | 9.97x |
| DMart | 3.03x | 37.04x |

Peers differ sharply in business mix, growth and capital intensity, so direct comparability is limited.

## Limitations and planned fixes
1. **Terminal reinvestment.** Terminal-year capex stays at 10.5% of revenue against 4.9% D&A, roughly 2.1x, which understates terminal cash flow. Fix: tie terminal reinvestment to growth ÷ ROIC.
2. **WACC** is an assumed 10%. Fix: CAPM build with dated risk-free rate, beta and equity risk premium.
3. **SOTP multiples** are illustrative. Fix: peer-based multiples per segment.
4. **Comps set** is three companies. Fix: widen the peer set per segment.

## Repository contents
- `Reliance_Valuation_Analysis_oct2026.xlsx`: Cover, Assumptions, Historical_financials, Segment_analysis, Forecast, DCF, Trading_comps, SOTP_valuation, DCF sensitivity

## Sources
Reliance Industries annual reports FY2021-22 to FY2025-26; peer annual reports and market prices as of the valuation date.

   *Built by Amrita Vidhu · [LinkedIn]www.linkedin.com/in/amritavidhu*
