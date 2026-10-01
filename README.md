# PJM Power Market Explorer

Exploratory analysis of PJM Day-Ahead and Real-Time power market data, focusing on price behavior, congestion, system load, load forecast accuracy, DA/RT spreads, and generation mix.

## Project Overview

This project analyzes hourly PJM electricity market data to better understand how prices behave across hubs and how system conditions affect Day-Ahead and Real-Time market outcomes.

The analysis focuses primarily on August 18, 2026 and includes 12 major PJM hubs.

## Key Questions

- How does Day-Ahead LMP change throughout the day?
- How do average prices differ across PJM hubs?
- How does congestion vary across locations?
- How strongly is system load related to Day-Ahead LMP?
- How accurate was the selected pre-operating-day load forecast?
- When did Day-Ahead and Real-Time prices diverge the most?
- How did generation by fuel type co-move with Day-Ahead LMP?

## Data Used

The project uses PJM market data covering:

- Day-Ahead Locational Marginal Prices
- Real-Time Hourly Locational Marginal Prices
- Metered RTO Load
- Historical Load Forecasts
- Generation by Fuel Type

## Key Findings

- Average Day-Ahead LMP across the selected hubs peaked at approximately **115.92 USD/MWh at 19:00**.
- The lowest average Day-Ahead LMP occurred at approximately **25.47 USD/MWh at 03:00**.
- **Dominion Hub** had the highest daily average Day-Ahead LMP, while **Chicago Gen Hub** had the lowest.
- Actual PJM system load and average Day-Ahead LMP had a correlation of approximately **0.77**.
- The selected load forecast produced an **MAE of approximately 2.54 GW** and a **MAPE of approximately 2.23%**.
- The largest hourly mean absolute DA/RT spread occurred at **19:00**, at approximately **91.98 USD/MWh**.
- Hydro, Storage, Gas, and Oil generation showed strong positive correlations with average Day-Ahead LMP during the analysis day.

## Skills Demonstrated

- Python
- pandas
- Data cleaning
- Data merging
- Time-series analysis
- Correlation analysis
- Electricity market analysis
- LMP and congestion analysis
- Load forecast evaluation
- Data visualization with Matplotlib

## Repository Structure

```text
PJM-Power-Market-Explorer/
│
├── README.md
├── PJM_Power_Market_Explorer.ipynb
└── figures/
