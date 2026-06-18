# Fund Monitoring Dashboard

Dashboard for tracking a VC fund portfolio — built with OTV-style reporting needs in mind (fintech/insurtech fund, single LP, quarterly reporting cycle).

Takes a CSV of portfolio companies and outputs fund-level KPIs, per-company performance, and LP-ready charts.

## What it tracks

- Fund-level IRR, MOIC, TVPI, DPI
- Per-company performance — invested amount, current valuation, unrealized/realized gains
- Exit tracker — proceeds, return multiple, exit date
- Portfolio breakdown by sector, stage, geography, vintage year

## Stack

Python, Pandas, Streamlit, Matplotlib.

## Usage

```bash
pip install -r requirements.txt
streamlit run dashboard.py
```

Input is a CSV with the following columns:

| Column | Description |
| :--- | :--- |
| `company` | Company name |
| `sector` | e.g. InsurTech, Fintech, PropTech |
| `stage` | Series A / B / C / D |
| `geography` | Europe / North America / Asia |
| `investment_date` | YYYY-MM-DD |
| `invested` | Amount invested (€M) |
| `valuation` | Current valuation (€M) |
| `status` | active / exited |
| `exit_proceeds` | Exit proceeds if exited, else 0 |
| `exit_date` | YYYY-MM-DD if exited, else empty |

Sample data modelled on a fintech/insurtech fund structure is included.

## Contact

📧 [maysaa.rais@gmail.com](mailto:maysaa.rais@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/maysaarais)
🌐 [maysaarais.github.io](https://maysaarais.github.io)
