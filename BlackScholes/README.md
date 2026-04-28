# Black-Scholes Pricing Engine

Analytical implementation of the Black-Scholes-Merton model for pricing European options and calculating risk sensitivities. This project serves as the baseline for the more complex stochastic models in this repository.

### Implementation Focus
- **Analytical Solver:** Exact solution for European Call and Put prices using the BSM formula:
  $$C = S_0 N(d_1) - K e^{-rt} N(d_2)$$
- **The Greeks:** Manual derivation and implementation of Delta, Gamma, Vega, Theta, and Rho to monitor portfolio risk.
- **Implied Volatility (IV):** A Newton-Raphson solver to back out IV from market prices, identifying where the market deviates from BSM assumptions.
- **Visualization:** 3D plotting of Greeks across varying spot prices and time-to-maturity.

---
[Link to Notebook](LINK) | [Link to Code](LINK)
