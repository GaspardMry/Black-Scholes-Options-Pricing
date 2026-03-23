# Black-Scholes Options Pricing & Volatility Smile

## Overview
Implementation of the Black-Scholes model (1973) for European options pricing, 
with implied volatility extraction and volatility smile/surface analysis on AAPL.

## Concepts Covered
- **Black-Scholes formula** — theoretical pricing of European call & put options
- **Implied Volatility** — reverse-engineering σ from market prices (σ_implied ≠ σ_historical)
- **Volatility Smile** — empirical anomaly where implied vol varies across strikes
- **Term Structure** — implied vol variation across maturities

## Key Results
![Volatility Smile](6-Black_Scholes_Options%20copie/smile_AAPL_2026-03-11.png)
![Term Structure](6-Black_Scholes_Options%20copie/term_structure_AAPL.png)

## Libraries
`numpy` `pandas` `scipy` `matplotlib` `yfinance`

## Context
Personal project
