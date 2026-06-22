# PE Performance & Benchmarking

Performance analysis of CalPERS' private equity portfolio using their public quarterly reporting data (as of September 2025, 300+ active fund commitments).

Calculates fund-level and portfolio-level IRR, MOIC, and Kaplan-Schoar PME benchmarked against MSCI World. Breaks down performance by vintage year, strategy, and geography.

## What it covers

Fund-level: net IRR, investment multiple (MOIC), DPI, RVPI

Portfolio-level: capital deployed vs distributed, realized vs unrealized value

Benchmarking: Kaplan-Schoar PME vs MSCI World by vintage year

Vintage analysis: J-curve effect across fund generations, top/bottom quartile dispersion

## Data source

CalPERS Private Equity Program Fund Performance Review. Publicly available quarterly at calpers.ca.gov. Columns: fund name, vintage year, capital committed, cash in, cash out, cash out & remaining value, net IRR, investment multiple.
https://www.calpers.ca.gov/investments/about-investment-office/investment-organization/pep-fund-performance-print

## Files

analysis.ipynb — full analysis and charts

analysis.html — open in browser to view output
