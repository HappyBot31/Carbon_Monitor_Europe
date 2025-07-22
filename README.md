# CO2 Emissions in Europe – Data Analysis & Visualization

This project explores CO₂ emissions across European countries using real-world data. We analyze emission trends over time, compare different countries and sectors, and uncover patterns that help us understand where and how emissions can be reduced.

## Dataset

The dataset comes from **Carbon Monitor Europe** and contains daily CO₂ emissions by country and sector from 2019 to 2023.  
It includes emissions from:
- **Power**
- **Industry**
- **Transport**
- **Residential**
- **Aviation**


Specifically, the this project asks and answers the following 3 Research Questions (RQ):
#### RQ1: How did COVID-19 affect CO2 emissions in Europe, especially in transport and aviation?
#### RQ2: Which countries produce the most CO2, and how are their emissions different?
#### RQ3: Which sectors cause most of the changes in emissions over time?

## Tools and libraries used:
- Jupyter Notebooks: https://jupyter.org
- Python 3: https://www.python.org
- Pandas: https://pandas.pydata.org
- Numpy: https://numpy.org

### To run the notebook, install the required libraries:

```bash
pip install pandas matplotlib seaborn
```
## Files:
- `carbonmonitor-eu_datas.csv` dataset about daily CO₂ emissions across European countries, that can be downloaded and reserched from: https://figshare.com/articles/dataset/Carbon_Monitor_Europe_a_near-real-time_and_country-level_monitoring_of_daily_CO2_emissions_for_European_Union_and_the_United_Kingdom/20219024
- carbon_monitor_analysis.ipynb Original Jupyter Notebook file, needs Jupyter Notebooks installed: https://jupyter.org

## Project Structure:
```bash
CO2-Emissions-Europe/
│
├──  data/
│     └── carbonmonitor-eu_datas.csv # Used Dataset
├──  images/                    # Saved plots and graphs
├──  carbon_monitor_analysis.ipynb   # Main Jupyter Notebook
└──  README.md                  # Project documentation
```

## Visualizations Used
- **Line plots:** Show trends in CO₂ emissions over time.

- **Bar plots:** Compare total emissions between countries or sectors.

- **Stacked area plots:** Visualize sector contributions to total emissions.

- **Heatmaps:** Show correlations between sectors.



## Results short Version:
**RQ1:** CO₂ emissions dropped sharply in 2020, especially in transport and aviation, due to lockdowns and travel restrictions.<br/>
**RQ2:** Germany has the highest emissions (mainly power and industry), while France emits less (due to nuclear energy), and Italy has a more balanced mix<br/>
**RQ3:** Transport and power show the biggest changes. Residential stays stable. Aviation dropped in 2020 and is slowly rising again.<br/>

## Results long Version:
**RQ1:** During 2020, when COVID-19 lockdowns were in place across Europe, there was a major drop in CO₂ emissions. This was most visible in the transport and aviation sectors, where emissions fell quickly as people stopped traveling, flights were canceled, and public transport was reduced.
After lockdowns ended, emissions started to rise again in 2021 and 2022. This shows that although the pandemic caused a temporary drop, lasting change requires structural actions, like switching to clean energy and reducing dependence on fossil fuels — not just temporary shutdowns.<br/>

**RQ2:** In the data, Germany is the biggest emitter in Europe, especially due to its power generation and industry sectors. France emits much less CO₂ from power because it uses nuclear energy, which doesn’t release carbon. Italy shows a more balanced distribution across sectors, including transport and residential use.
These differences tell us that each country has unique energy sources and industrial patterns. So, every country needs its own strategy to cut emissions effectively.<br/>

**RQ3:** Using line plots and stacked area charts, we saw that transport and power are the most variable sectors over time. Transport emissions rise in warmer months and drop in winter or during lockdowns. Power emissions change with energy demand and production sources.
The residential sector is more stable but still shows seasonal trends (like more heating in winter). The aviation sector dropped sharply in 2020 and is gradually returning to previous levels.
This tells us that if we want to reduce emissions quickly, transport and power are the sectors we should focus on first.
<br/>

## What You’ll Learn
### By studying this project, you’ll gain skills in:

- Working with real-world CSV data.

- Cleaning and transforming datasets.

- Plotting time-series and categorical data.

- Asking and answering real analytical questions.

- Structuring a GitHub project.

###  Author: 
# Said Shokirov.