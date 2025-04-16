# Black-Scholes Option Pricing Engine — Clean Quantitative Implementation

This notebook implements the Black-Scholes model from scratch for European call and put options, with full analytical Greeks and custom normal CDF approximation. The focus is on transparency, readability, and reproducibility — no pricing libraries are used.

It is part of a larger initiative to revisit and master core models in quantitative finance, with emphasis on self-contained, production-grade implementations.

---

## 📌 What’s Covered

- Full pricing formula for European calls and puts  
- Manual implementation of the standard normal CDF Φ(x)  
- Complete Greeks: Delta, Gamma, Vega, Theta, Rho (analytical)  
- Sensitivity plots across spot, volatility, time  
- 3D visualizations of option price and sensitivities

---

## ⚙️ Default Parameters (modifiable)

- Spot: 100  
- Strike: 100  
- Volatility (σ): 0.2  
- Time to maturity (T): 1 year  
- Risk-free rate (r): 5%

These can be edited in the first few notebook cells.

---

## 📈 Outputs

- Option prices (call/put)  
- Sensitivity curves for each Greek  
- 3D surface plots for price vs volatility / time

---

## 🧭 Roadmap / Extensions (Optional)

- Compare to Monte Carlo simulation  
- American options via binomial tree or PDE methods  
- Calibration to implied vol surfaces

---

## 🧑‍💻 Author

**Maysaa Rais**  
Quantitative Finance — Model Risk, Pricing, and Data Science  
Part of a research portfolio revisiting foundational quant models with a modern coding standard.

---

📁 Notebook: `BlackScholes.ipynb`  
📄 HTML Export: `BlackScholes.html`  
📦 Core functions: `bs_model.py`  
📊 Data: `stock_data_multi.csv`
