# Fund Monitoring Dashboard

VC portfolio monitoring tool built in Python and Streamlit. You load a CSV of portfolio companies and it gives you fund-level performance metrics and charts — the kind of thing you'd put in a quarterly LP report.

Sample data is modelled on a fintech/insurtech fund (Series A to D, Europe/North America/Asia).

## What it covers

Fund KPIs: IRR, MOIC, TVPI, DPI

Per company: amount invested, current valuation, realized vs unrealized value

Exits: proceeds, return multiple, exit date

Portfolio breakdown: by sector, stage, geography, vintage year

## Run it

```bash
pip install -r requirements.txt
streamlit run dashboard.py
```

## Input format

A CSV with these columns: company, sector, stage, geography, investment_date, invested (€M), valuation (€M), status (active or exited), exit_proceeds, exit_date.

## Contact

📧 [maysaa.rais@gmail.com](mailto:maysaa.rais@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/maysaarais)
🌐 [maysaarais.github.io](https://maysaarais.github.io)
