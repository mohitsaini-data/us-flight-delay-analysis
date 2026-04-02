# US Flight Delay Analysis
### Power BI Dashboard — 5.7 Million Flight Records

## Project Overview
Interactive Power BI dashboard analysing 5.7 million US domestic 
flight records from 2015 to identify delay patterns across 14 airlines, 
12 months, and multiple origin airports. Built using Power Query for 
data transformation, DAX for custom measures, and dynamic slicers 
for interactivity.

## Key Findings
- **Spirit Airlines (NK)** had the worst average departure delay 
  at **15.91 mins** — nearly double the best performing carriers
- **United Airlines (UA)** was second worst at **14.38 mins**
- **June** recorded peak delays across all airlines — driven by 
  summer travel congestion and afternoon thunderstorms
- **Late Aircraft Delay** was the biggest delay cause at **10.08%** 
  — indicating a cascade effect where one late plane delays the next
- Dataset covers **5.7 million flights** across 14 US airlines

## Tools Used
- Power BI Desktop — dashboard development
- Power Query — data cleaning, custom date column creation
- DAX — On-Time Performance measure, custom calculations
- Dynamic Slicers — Airline, Month, Origin Airport filters

## Files in this Repository
- `airlines.csv` — airline code reference data
- `airports.csv` — airport code and location reference data
- Note: Main flights.csv (195MB) too large for GitHub — 
  available at kaggle.com/datasets/usdot/flight-delays

## Dashboard Visuals
- KPI Card — Total Flights (5.73M)
- Bar Chart — Average Departure Delay by Airline
- Line Chart — Monthly Delay Trend across 12 months
- Donut Chart — Delay Cause breakdown
- Interactive Slicers — Airline, Month, Origin Airport

## Data Source
US Department of Transportation — Bureau of Transportation Statistics
2015 Flight Delays and Cancellations Dataset
Available at: kaggle.com/datasets/usdot/flight-delays
