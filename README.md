# DCF Valuation Tool — Python

A discounted cash flow (DCF) valuation model built in Python that pulls live financial data and values any publicly listed company.

## What it does
- Accepts any stock ticker as input (e.g. AAPL, TSLA, MSFT)
- Pulls real financial data via Yahoo Finance API
- Calculates WACC automatically using CAPM, live US Treasury yield, and company financials
- Projects Free Cash Flow over 5 years
- Calculates intrinsic value per share
- Generates a WACC vs Growth Rate sensitivity analysis
- Visualises projected FCFs as a bar chart
- Visualises sensitivity analysis as a heatmap
- Built with error handling for missing data across different companies

## Tools Used
- Python, Pandas, yfinance, Matplotlib, Seaborn

## How to Run
1. Open the notebook in Google Colab
2. Run all cells in order
3. Enter any stock ticker when prompted
4. View the valuation summary, charts, and sensitivity table

## Sample Output (Apple Inc.)
Intrinsic Value: $118.01 | Market Price: $298.87 → Overvalued (-60.5%)

Calculated WACC: 10.24% (Beta: 1.06, Risk Free Rate: 4.48%)

![FCF Forecast](sample_projected_fcf.png)

![Sensitivity Heatmap](sample_dcf_sensitivity.png)
