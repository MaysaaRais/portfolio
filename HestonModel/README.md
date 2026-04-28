# Heston Model: Stochastic Volatility Pricing

Implementation of the Heston model to address the limitations of Black-Scholes, specifically the "Volatility Smile" and "Skew." This project uses Monte Carlo methods to price options under stochastic volatility.

### Implementation Focus
- **SDE Simulation:** Discretizing the price and variance processes using the **Euler-Maruyama** method:
  $$dS_t = r S_t dt + \sqrt{v_t} S_t dW_t^S$$
  $$dv_t = \kappa(\theta - v_t)dt + \sigma \sqrt{v_t} dW_t^v$$
- **Monte Carlo Engine:** Simulating 100,000+ paths to estimate option payoffs and ensure convergence.
- **Model Calibration:** Minimizing the RMSE between model-generated prices and market-observed volatility surfaces.
- **Risk Dynamics:** Capturing the leverage effect via the correlation ($\rho$) between price and volatility.

---
[Link to Notebook](LINK) | [Link to Code](LINK)
