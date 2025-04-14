# Heston Model — Stochastic Volatility Pricing

This notebook implements the Heston model for pricing European options using Monte Carlo simulation.  
The volatility is modeled as a stochastic process, allowing us to capture smile effects and other dynamics not handled by Black-Scholes.

The idea is to simulate multiple price/volatility paths and compute the expected payoff, then calibrate the model to fit observed market prices.

---

## What’s covered

- Simulation of the Heston SDE (Euler-Maruyama)
- Monte Carlo pricing for vanilla options
- Parameter calibration (minimize error vs market prices)
- Surface plots: implied vol vs strike / maturity

---

## Parameters used

- Spot = 100  
- Strike = 100  
- T = 1  
- r = 0.05  
- Initial vol = 0.2  
- Heston params:  
  - 𝜈 (vol of vol),  
  - ρ (correlation),  
  - κ (mean reversion),  
  - θ (long-term vol)

---

## Outputs

- Simulated paths (spot + vol)
- Monte Carlo estimated option price
- Calibration curve (error minimization)
- Optional: compare with Black-Scholes

---

## Data

Market prices (SPY, AAPL, etc.) can be pulled with `yfinance`.  
Implied vol data can be added manually or scraped from sources like [optionistics.com](http://optionistics.com) or [ivolatility.com](https://www.ivolatility.com).

---

## Author

Maysaa Rais  
This notebook is part of a broader exploration of pricing models with a focus on building them from the ground up, not just using libraries.
