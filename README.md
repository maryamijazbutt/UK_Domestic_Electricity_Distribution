# UK Domestic Energy Consumption Trends (2015–2024)
### Power BI Analytics Project

---

## Overview

This Power BI project analyses domestic electricity consumption patterns across the UK over the past ten years (2015–2024). It explores the relationship between the growing number of electricity meters (i.e. customer base) and actual energy consumption, identifies key drivers of change, and forecasts future trends.

---

## Objectives

- How has domestic electricity consumption varied over the last 10 years?
- How has the domestic customer base changed over the same period?
- What trend can be forecasted based on available data?
- What constraints affect the accuracy of these predictions?

---

## Data Source

**Publisher:** UK Government (GOV.UK)  
**Dataset:** Domestic Electricity Consumption Distribution 2015–2024  
**URL:** [https://assets.publishing.service.gov.uk/media/69426ec31ec67214e98f3058/Domestic_electricity_consumption_distribution_2015-2024.xlsx](https://assets.publishing.service.gov.uk/media/69426ec31ec67214e98f3058/Domestic_electricity_consumption_distribution_2015-2024.xlsx)

### Original Data Structure

The source dataset contained three columns:

| Column | Description |
|---|---|
| Upper consumption band | Upper boundary of the kWh consumption range |
| Lower consumption band | Lower boundary of the kWh consumption range |
| Number of meters | Count of domestic meters recording consumption within that band |

The energy consumption unit throughout is **kilowatt-hours (kWh)**. The meter count covers **all domestic meters in the UK** for each year.

The original xlsx file has ten pages, one for each year. The tables were first appended to make a single consolidated long table in PowerBI.
Additional columns and DAX measures were created in Power BI to support the analysis.

---

## Key Findings

- The **customer base has grown steadily**, with a consistent year-on-year increase in the number of meters installed — particularly in the lowest energy consumption band.
- Despite the growing customer base, **total electricity consumption declined from 2015 to 2019**.
- There was a **sharp spike in 2020** (from ~104 bn kWh to ~110 bn kWh), attributed to the COVID-19 work-from-home period.
- Consumption **stabilised in 2021–2022**, then declined again, likely influenced by rising energy tariffs following the war in Ukraine.
- From **2023 onwards**, consumption is showing renewed growth.
- Year-on-year consumption growth is **volatile and sensitive to external factors** such as energy tariffs and weather, making short-term forecasting inherently uncertain.

---

## Visuals Included

The report contains the following Power BI visuals:

1. **Bar chart — Meters by consumption band (per year):** Shows how the number of meters in each energy band has changed, highlighting large growth in the lowest consumption band.
2. **Bar chart — Total consumption by energy band (per year):** Illustrates that rising meter counts do not directly correspond to rising total consumption.
3. **Line chart — Total meters over time:** Demonstrates steady, consistent growth in the UK domestic customer base.
4. **Line chart — Total energy consumption over time:** Shows the overall downward trend punctuated by the 2020 spike and post-2022 recovery.
5. **YoY growth charts — Meters and consumption:** Compares year-on-year percentage change for both metrics, highlighting the divergence between customer base growth and consumption trends.
6. **Forecast — Customer base:** Extrapolated growth in meter numbers, supported by population growth and new housing development.
7. **Forecast — Energy consumption:** Projects a potential decline in per-household consumption despite a growing customer base, driven by cost-of-living pressures and improved building energy efficiency.

---

## Conclusions

- The **customer base will continue to grow** in line with population growth and new housing.
- However, this **will not necessarily translate to higher total consumption** — newer homes are more energy-efficient, and cost-of-living pressures are encouraging lower usage per household.
- Short-term consumption trends remain **difficult to predict** due to the influence of external shocks (pandemics, geopolitical events, tariff changes).

---

## Limitations

- The dataset captures meter-level consumption bands rather than individual household data, limiting granularity.
- External factors (policy changes, energy prices, weather) has not been taken into account. For example, the general trend towards warmer weather will decrease use of electricity but the Clean Power 2030 Action Plan will increase the domestic electricity usage. These factors have not been taken into account.
- Forecasts are extrapolations based on historical trends and should be treated as indicative rather than definitive.
---

## Tools Used

- **Power BI Desktop** — data modelling, DAX measures, and visualisations
- **Data source:** UK Government open data portal

---

## How to Use This Report

1. Open the `.pbix` file in **Power BI Desktop**.
2. If needed, the orginal data can be viewed from the link provided above.
3. The Power Point report is also uploaded in tthis repository.

---

## Author

*Maryam Ijaz Butt*

---

## Licence

**
