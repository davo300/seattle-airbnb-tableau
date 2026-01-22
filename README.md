# Seattle Airbnb Data Analysis (Tableau)

## Overview
This project analyzes Seattle Airbnb listings using Tableau. 
The goal is to explore pricing, availability, and listing characteristics
across neighborhoods and bedroom counts.

## Dashboard
🔗 **Live Tableau Dashboard:**  
https://public.tableau.com/app/profile/matt.davies6123/viz/AirBnBPricesDashboardforSeattle/Dashboard1?publish=yes

## Data
- Source: Seattle Airbnb Open Data (Kaggle)
- Files used:
  - listings.csv
  - calendar.csv
  - reviews.csv
- Data snapshot: [month/year downloaded]

## Data Cleaning
Cleaning was performed without Excel to ensure reproducibility:
- Filtered listings with bedrooms outside 1–6
- Removed inactive listings (availability_365 = 0)
- Excluded extreme price outliers
- Used COUNTD(id) to avoid duplicates

## Key Insights
- 1–2 bedroom listings dominate the market
- Larger listings (5–6 bedrooms) are rare and priced significantly higher
- Central neighborhoods show higher price density

## Tools
- Tableau Public
- CSV data (no Excel preprocessing)

## Notes
Counts may differ from older tutorials due to newer data snapshots
and explicit cleaning rules.

