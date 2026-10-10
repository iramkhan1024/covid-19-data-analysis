# covid-19-data-analysis
The project is about Covid - 19 Cases Data Analysis and forecasting.

# COVID-19 Data Analysis & Forecasting

## Overview
This repository contains a comprehensive data analysis and time-series forecasting pipeline based on Covid-19 pandemic datasets. Using Python, Pandas, Plotly, and Facebook Prophet, the project cleans historical metrics, performs global aggregations, and provides interactive visualizations.

## Dataset
* **File Used:** `covid_19_clean_complete.csv`.
* **Key Columns:** `Province/State`, `Country/Region`, `Lat`, `Long`, `Date`, `Confirmed`, `Deaths`, `Recovered`, `Active`, `WHO Region`.

## Project Workflow
1. **Data Accumulation & Cleaning:** Loaded multiple data records using Pandas, converted date attributes to standard datetime objects, and handled regional differences by aggregating global totals over time.
2. **Interactive Visualizations:** Built interactive visual dashboards using Plotly to display daily trends across confirmed cases, active cases, recoveries, and fatalities..
3. **Time-Series Forecasting:** Applied Facebook Prophet to track time patterns and forecast upcoming COVID-19 trends..

