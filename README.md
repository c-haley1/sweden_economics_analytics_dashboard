# Sweden Economics Dashboard (Power BI)

A Power BI dashboard analyzing Sweden's economic growth and standing among Nordic/EU economies, built on World Bank economic indicator data. The report spans three pages: a country comparison overview, an economics deep dive, and a supplemental notes page with narrative findings.

## Objective

Provide in-depth analysis of Sweden's current and historic levels of economic growth using key indicators like GDP, inflation, and cost of living — and assess how Sweden stacks up against other Nordic countries and EU benchmarks.

## Data

Sourced from the **World Bank**, covering a range of economic indicators for Sweden and comparison countries:

- GDP growth (% annual) and GDP per capita
- Government revenue, expense, and tax revenue (% of GDP)
- Inflation (CPI %)
- Public debt (% of GDP)
- Unemployment rate (%)
- Cost of Living Index and Local Purchasing Power Index (Nordic country comparison)

**Tables:** `world_bank_data_2025`, `Fact_Indicators`, `Cost of Living Index`

## Methodology

Data from the World Bank was modeled and visualized across a multitude of chart types to surface both Sweden's strengths and weaknesses from an economic standpoint, comparing current-year snapshots against 10+ years of historical trends.

## Dashboard Pages

**1. Sweden Country Comparison**
- Cost of Living Index by country (clustered column)
- Nordic countries: Cost of Living Index vs. Local Purchasing Power Index (scatter)
- Total GDP growth year-over-year for Sweden (scatter)
- Annual GDP growth vs. unemployment rate over the last 10 years (scatter)
- 2024 Total GDP (USD) — KPI
- Government spending vs. government revenue vs. tax revenue (clustered column)

**2. Sweden Economics Deep Dive**
- Average GDP growth vs. average inflation (combo chart)
- Average government revenue vs. average government expense (area chart)
- GDP per capita — card
- Purchasing power — card
- Public debt (% of GDP) by year (line chart)
- Year slicer for interactive filtering

**3. Supplemental Dashboard**
- Data overview, objective, methodology, and key insights, in narrative form (see below)

## Key Insights

- 2020 (the COVID pandemic) was the only year in the last five that the Swedish government spent more than it collected in revenue.
- Sweden's GDP has risen steadily, and increasingly rapidly, since 2000.
- Low unemployment rates in Sweden consistently coincide with high annual GDP growth.
- Sweden ranks among the best Nordic countries on both cost of living and local purchasing power.
- Sweden has kept public debt well below the EU-recommended 60% of GDP threshold.

## Conclusion

Sweden ranks among the strongest countries from an economic growth standpoint: a fast-growing GDP, low living costs, high purchasing power, and government spending that has stayed disciplined even as inflation has risen. Based on these trends, Sweden is well-positioned to remain one of the most successful economies over the next 20 years.

## Repo Contents

| File | Description |
|---|---|
| `Power_BI_Final_Project.pbix` | Full Power BI report — data model, measures, and all three dashboard pages |

## Tools

Power BI · DAX · World Bank economic indicator data

## Author

Colin Haley — August 2026
