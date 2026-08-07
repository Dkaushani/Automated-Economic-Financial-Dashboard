# Automated Economic Financial Dashboard-Data Wrangling, Time-Series & API Integration
Founded key macro relationship using S&P 500, Crude Oil and 10-Year Treasury Yield.

Macro Economic Dashboard (2020–Present)
This repository sets up a Python pipeline that pulls and analyzes market data for three core economic indicators: S&P 500 (stocks), WTI Crude Oil (energy/inflation), and the 10-Year Treasury Yield (interest rates).

What the Code Does
Pulls Live Market Data: Uses yfinance to fetch daily historical closing prices directly from Yahoo Finance starting from January 2020.

Cleans & Engineers Features: Cleans up calendar mismatches across asset classes and calculates key indicators like a 30-day moving average for oil and year-over-year percentage returns for the S&P 500.

Builds Interactive Plots: Generates clean, interactive Plotly charts to compare price trends, spot market shifts, and evaluate asset relationships.

Economic Events Captured in the Data
Because the timeline runs from 2020 to the present, the dataset clearly picks up three major market shifts:

The 2020 Market Crash: The sudden drop in stock and oil prices during early COVID lockdowns, alongside a flight to safe-haven bonds.

The 2021–2022 Inflation Surge: Energy prices spiking above $120/barrel following post-lockdown demand surges and the outbreak of war in Europe.

The Fed Rate Hikes: Treasury yields climbing toward 5% as the central bank worked to curb inflation, placing noticeable pressure on equity markets.
