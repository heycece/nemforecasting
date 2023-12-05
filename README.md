# NEM Research Project

## Project highlights

### Webscraper
- 🥫 Use of BeautifulSoup in Python to collect:
  - 🔋 Actual PV (Photovoltaic) energy generated (solar energy generated)
  - 🌬 Dispatch SCADA value (wind energy generated)

- 🔌 Use of actual PV from AEMO archive and current data (as of November 22, 2023)

- 📈 Use of RRP from AEMO price data (from Oct 2022 - Nov 2023)

- 🗂️ Data cleaning done in local drive

- 🌞 ***8am to 6pm***, 7am to 7pm

### OLS Regression

#### Objective:
- To answer the question "What affects spot prices?"

#### Models done on:
- PV (where power generated only explained 3% of spot price)
- PV/Total demand (where power generated only explained 4% of spot price across all regions)
- PV + PV/Total demand (where power generated over total demand only explained 3% of spot price, same as PV)
- ***PV/Total demand (where power generated over total demand only explained 2.6% of spot price, only considered NSW region)***

### Currently working on:

- 🛠️ Wind OLS and Rooftop + Solar / Demand
- 



