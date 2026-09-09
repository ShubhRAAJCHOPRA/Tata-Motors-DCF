

# Tata Motors — DCF Valuation & Financial Analysis

## Overview

This project presents a Discounted Cash Flow (DCF) valuation of Tata Motors based on historical financial performance and forward-looking operating assumptions.

The model forecasts revenue, operating profitability and Free Cash Flow to the Firm (FCFF), calculates Enterprise Value and Equity Value, and derives an implied share price using a WACC-based DCF methodology.

The project also includes a financial dashboard to summarize the company's historical performance, forecast assumptions, cash flows, debt position and valuation outputs.

---

## Objectives

The main objectives of this project were to:

- Analyze Tata Motors' historical financial performance
- Build forward-looking revenue and profitability forecasts
- Calculate EBIT, EBITDA and NOPAT
- Forecast Free Cash Flow to the Firm (FCFF)
- Calculate Weighted Average Cost of Capital (WACC)
- Estimate Terminal Value using the Perpetual Growth Method
- Derive Enterprise Value and Equity Value
- Calculate implied share price
- Analyze valuation sensitivity to WACC and terminal growth
- Present the key outputs through a financial dashboard

---

## Model Structure

The DCF model follows the following structure:

### 1. Historical Financials

Historical financial data is used to establish the company's operating performance and identify trends in:

- Revenue
- EBIT
- EBITDA
- Operating margins
- Taxes
- NOPAT
- Capital expenditure
- Working capital
- Free Cash Flow

### 2. Forecasts

Financial projections are developed for the forecast period using assumptions for:

- Revenue growth
- EBITDA margins
- EBIT margins
- Tax rate
- Capital expenditure
- Depreciation
- Working capital requirements

### 3. FCFF Calculation

Free Cash Flow to the Firm is calculated as:

FCFF = NOPAT + D&A - Capex - Change in NWC

The resulting FCFF is used as the primary cash flow measure for the DCF valuation.

### 4. WACC

The Weighted Average Cost of Capital is calculated using:

- Risk-free rate
- Beta
- Equity risk premium
- Cost of equity
- Cost of debt
- Effective tax rate
- Debt and equity weights

### 5. Terminal Value

Terminal Value is calculated using the perpetual growth method:

Terminal Value = FCFFₙ × (1 + g) / (WACC - g)

where:

- g = Terminal Growth Rate
- WACC = Weighted Average Cost of Capital

### 6. Enterprise Value

The present value of forecast FCFF and Terminal Value are combined to calculate Enterprise Value.

Enterprise Value is then adjusted for relevant debt and cash items to arrive at Equity Value.

### 7. Implied Share Price

The implied equity value is divided by the relevant shares outstanding to calculate the DCF-implied share price.

---

## Sensitivity Analysis

A sensitivity analysis is included to evaluate how the implied valuation changes under different:

- WACC assumptions
- Terminal growth assumptions

This helps assess the robustness of the DCF valuation and highlights the impact of changes in key assumptions.

---

## Financial Dashboard

The Excel dashboard summarizes the key outputs of the model, including:

- Revenue
- EBITDA
- EBIT
- NOPAT
- FCFF
- Revenue growth
- EBITDA and EBIT margins
- Debt position
- Net debt
- DCF valuation
- Enterprise Value
- Equity Value
- Implied Share Price
- WACC
- Terminal Growth Rate
- Valuation sensitivity

The dashboard is designed to provide a quick overview of both operating performance and valuation.

---

## Key Financial Concepts Used

- Discounted Cash Flow (DCF)
- Free Cash Flow to the Firm (FCFF)
- Enterprise Value
- Equity Value
- Weighted Average Cost of Capital (WACC)
- Cost of Equity
- Cost of Debt
- Terminal Value
- Perpetual Growth Method
- NOPAT
- EBITDA
- EBIT
- Net Debt
- Sensitivity Analysis

---

## Tools Used

- Microsoft Excel
- Financial statement analysis
- Corporate valuation
- DCF modelling
- Financial dashboarding

---

## Project Files

```text
Tata-Motors-DCF/
│
├── Tata_Motors_DCF.xlsx
└── README.md
