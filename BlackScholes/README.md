# Black-Scholes Option Pricing

Notebook built to implement and test the Black-Scholes model for European call and put options.  
Everything is coded from scratch, including the approximation of the normal CDF. No pricing libraries used.

The goal is to revisit the core formula, make sure it's coded cleanly, and explore how option prices and sensitivities behave across different parameters.

---

## What’s covered

- Analytical pricing formula (call/put)
- Manual approximation of Φ(x) (no scipy)
- Greeks: Delta, Gamma, Vega, Theta, Rho
- Sensitivity curves and 3D visualizations

---

## Parameters used

- Spot = 100  
- Strike = 100  
- σ = 0.2  
- T = 1 (year)  
- r = 0.05  

Parameters can be edited directly in the first few cells of the notebook.

---

## Outputs

- Call/Put price  
- Delta / Gamma / Vega curves  
- Surface plots: price vs volatility & time

---

## Notes

Optional: I might later compare this to a Monte Carlo simulation or extend to American options (numerical methods).

---

## Author

Maysaa Rais  
Built this as part of a broader portfolio around pricing models and market-focused ML.
