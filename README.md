# Strategic Investment Analytics & Quantitative Finance — Maysaa Rais

Technical portfolio focused on **Private Markets performance**, **institutional risk monitoring**, and **stochastic modeling**. 

All models are manually implemented from first principles using **NumPy** and **SciPy**—avoiding pre-built pricing libraries to ensure full transparency, mathematical rigor, and institutional-grade risk reporting.

---

## Projects Overview

| Project | Description |
| :--- | :--- |
| [**PE Performance & Benchmarking**](./PE-Performance/README.md) | Python engine calculating **IRR**, **MOIC**, and **Kaplan-Schoar PME**. Benchmarks private fund performance against public indices (MSCI World). |
| [**Portfolio Look-Through & Risk**](./Portfolio-Analytics/README.md) | Risk framework tracking concentration (Sector, Geography, Vintage) for multi-asset and Fund-of-Funds mandates. Mimics Aladdin-style risk aggregation. |
| [**LBO Scenario Simulator**](./LBO-Simulator/README.md) | Monte Carlo-based LBO modeling to determine the probability of hitting target IRRs across variable exit multiples and EBITDA growth. |
| [**Heston Monte Carlo Framework**](./HestonModel/README.md) | Stochastic volatility pricing and parameter calibration for assets with non-constant risk regimes. |
| [**Volatility Forecasting (GARCH vs RNN)**](./Volatility-Forecasting/README.md) | Volatility prediction comparing traditional GARCH(1,1) models with custom-built Recurrent Neural Networks. |
| [**Black-Scholes Pricing Engine**](./BlackScholes/README.md) | Analytical option pricing and Greeks derivation used as a baseline for complex simulation models. |

---

## Technical Scope

- **Performance Attribution:** Internal Rate of Return (IRR) and Multiple of Invested Capital (MOIC) for illiquid assets.
- **Benchmarking:** Public Market Equivalent (PME) analysis to quantify the Private Market Premium.
- **Institutional Risk:** Manual implementation of VaR (Value at Risk), BPV sensitivity, and duration tracking.
- **Simulation:** Monte Carlo methods for modeling cash flow uncertainty in long-term investment cycles.

---

## 🛠 Tools & Stack

- **Python:** First-principles implementation using NumPy, SciPy, and Pandas.
- **Visualization:** Matplotlib and Seaborn for risk-surface plotting and concentration heatmaps.
- **Data Engineering:** Processing irregular PE cash flow data and large-scale institutional datasets.

---

## 📬 Contact

- 📧 [maysaa.rais@gmail.com](mailto:maysaa.rais@gmail.com)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/maysaarais)  
- 🌐 [Portfolio](https://maysaarais.github.io)
