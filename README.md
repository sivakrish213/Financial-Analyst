# 💹 Forecasting India's Pharma Opportunity Using OECD Health Data

This project analyzes global pharmaceutical spending patterns using **OECD healthcare data** (1970–2016) to **forecast India's future market trajectory**. We apply these insights to simulate revenue potential, breakeven points, and strategic opportunities for healthcare startups like **Karkinos**, operating in the Indian oncology space.

---

## 🌍 What is OECD Data?

The **Organisation for Economic Co-operation and Development (OECD)** collects standardized healthcare spending metrics across 30+ developed countries.

This project leverages:
- **Pharmaceutical spending per capita** (in USD PPP)
- Historical data across 40+ years
- Countries including USA, Germany, Turkey, Mexico, Japan, and the OECD average

By comparing India's estimated current spending (~$90) to countries like Turkey (~$195) and the OECD average (~$580), we simulate a **realistic, data-driven path for India's growth**.

---

## 🎯 Project Objective

To use OECD health data to:
- Benchmark India's pharma expenditure trajectory
- Forecast per capita spending through 2030
- Simulate total market size and revenue opportunity
- Model ROI, breakeven, and profitability for a hypothetical player like Karkinos

---

## 📊 Dataset Overview

- **Source:** [OECD Health Statistics](https://data.oecd.org/)
- **Metric Used:** `Pharmaceutical sales (USD PPP per capita)`
- **Time Span:** 1970–2016
- **Scope:** 30+ countries, annual values
- **File:** `OECD_pharma_spending.csv`

---

## 📈 Key Features & Insights

| Feature | Description |
|---------|-------------|
| 📊 **CAGR Modeling** | Uses historical growth from Turkey and Mexico to forecast India's trend |
| 💡 **Benchmarking** | India’s current per capita pharma spend is far below global norms |
| 🧮 **Market Sizing** | Forecasts India’s total pharma market to reach $220B+ by 2030 |
| 💸 **Scenario Modeling** | Simulates revenue from 0.25%, 0.5%, and 1% market capture |
| 🧾 **Financial Model** | Includes CapEx, OpEx, ROI, and breakeven year |
| 📉 **Inequality Gap** | Visualizes disparities in access and affordability between countries |

---

## 📁 Project Structure

```bash
karkinos-oecd-pharma-analysis/
├── data/
│   └── OECD_pharma_spending.csv
├── notebooks/
│   └── oecd_india_forecast_model.ipynb
├── dashboards/
│   └── financial_forecast_model.xlsx
├── reports/
│   └── market_forecast_summary.pdf
├── README.md
└── requirements.txt
