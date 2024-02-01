# NEM Research Project

## Project highlights

### Webscraper
- 🥫 Use of BeautifulSoup in Python to collect:
  - 🔋 Actual PV (Photovoltaic) energy generated (solar energy generated)
  - 🌬 Average MWH reading (wind energy generated)

- 🔌 Use of actual PV from AEMO archive and current data (as of November 22, 2023)

- 📈 Use of RRP from AEMO price data (from Oct 2022 - Nov 2023)

- 🗂️ Data cleaning done in local drive

- 🌞 ***8am to 6pm***, 7am to 7pm

### OLS Regression

#### Objective:
- To answer the question "What affects spot prices?", "What affects the spike in spot prices?"

#### Models done on:
- PV (where power generated only explained 3% of spot price)
- PV/Total demand (where power generated only explained 4% of spot price across all regions)
- ***PV*** (same as above)
- ***PV/Total demand (where power generated over total demand only explained 2.6% of spot price, only considered NSW region)***
- AveMWH_Reading (where wind energy generated explained <1% of spot price)
- AveMWH_Reading/Total demand (where wind energy generated explained .9% of spot price)

- (Wind + Solar) / Demand


### Data visuals
- **7-Day Forecast from PASA Data with Temperature data**
- **7-Day Recent Data from Different Energy Sources**
- **7-Day Historical Data on Demand and Price**

### Currently working on:
- **City Temperatures and LOR**



