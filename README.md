# Personal Finance: Wholelife Financial Plan (Excel + Analysis)

## About this repo
This repository contains my personal finance analysis and the Excel workbook I use to model the plan. The goal is practical: make assumptions explicit, show how cashflows and balance sheets evolve, run simple Monte Carlo scenarios, and produce clear recommendations you can reuse or adapt.
This README explains what's included, how to use the files, the main findings, and suggestions for presenting the project on GitHub or externally.

---
## Repository contents
* `Analysis.pdf`: full written analysis with profile, financial goals, assumptions, traditional & holistic balance sheets, cashflow statements, budget, asset allocation by life stage, Monte Carlo results, insurance analysis, and recommendations.
* `Calculation.xlsx`: Excel workbook with all calculations, inputs and outputs (assumptions, balance sheets, cashflow, Monte Carlo, allocation tables, charts). Use Excel (recommended) or Excel Online / Google Sheets (note: some formulas may not behave identically).

---
## Workbook structure
The workbook is organized around these main sheets:
1. **Assumptions:** all model inputs (ages, inflation, salary growth, rates, retirement age, etc.).
2. **BalanceSheet_Traditional:** assets & liabilities in conventional format.
3. **BalanceSheet_Holistic:** economic net worth (including human capital / present value of future earnings).
4. **CashFlow:** yearly income, taxes, expenses, savings and net cashflow.
5. **Budget:** recurring and one-off spending targets (home, car, kids, travel).
6. **AssetAllocation:** recommended asset mixes by time horizon / life stage.
7. **MonteCarlo:** simulation inputs and outputs (percentiles, success rate).
8. **Insurance:** needs analysis, premium estimates, recommended coverage.
9. **Outputs:** summary charts and tables for screenshots / slides.
10. **Appendix:** CPI series, reference rates and raw tables used in calculations.

---
## Key results (snapshot — June 2025, TP HCM)
* **Total financial assets (approx.):** 245,000,000 VND.
* **Reported income:** ~365,000,000 VND / year.
* **Short-term liquidity:** cash buffer ≈ 3.65 months of expenses.
* **Economic net worth (holistic):** approximately **-1,700,000,000 VND** (driven by present-value assumptions about future consumption and liabilities).
* **Monte Carlo result (with current assumptions):** success rate reported as **100%** under the modeled scenario.
> ⚠️ These numbers are model outputs based on the assumptions in `Assumptions`. They are illustrative of the workbook’s structure — update assumptions before reuse.

---
## Tools
* Microsoft Excel (primary): formulas, tables, charts.
    * Basic Monte Carlo implemented inside Excel (see `MonteCarlo` sheet for details).
* Microsoft Word: analysis document.
  


