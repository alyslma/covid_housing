# Property Values & COVID
## Purpose
To examine the impact of COVID on property values within the nation.

## Deployment
Website deployed on [Heroku](https://housing-covid.herokuapp.com/)

## Data Sources
- Property value data from January to August 2020 from [Zillow](https://www.zillow.com/research/data/)
- Number of COVID cases and deaths at the state and county level from [New York Times](https://github.com/nytimes/covid-19-data)
- Census data to standardize COVID data per population from [Census.gov](https://www.census.gov/data.html)
- Rural-Urban Commuting Area (RUCA) codes for classification purposes from [USDA ERS](https://www.ers.usda.gov/data-products/rural-urban-commuting-area-codes/)

## Visualizations
- Percent change in property value vs. COVID cases per 1000 people (Jan - Aug 2020) for a state (selection made from a dropdown menu)
- Average property value, cumulative COVID cases/deaths (Jan - Aug 2020) for a state or a particular county within the state (selections made from a dropdown menu)
- Two chloropeth maps, one depicting COVID cases per 1000 (as of August 31, 2020) and the other displaying the percent change in property values (Jan - Aug 2020)

## Findings and Takeaways
- Overall, property values increased across the nation from January to August 2020 alongside the increase in COVID cases.
- Next steps: 
(1) A time-series analysis may reveal more telling trends about spikes in COVID cases and property values,
(2) Controlling for decreases in interest rates,
(3) A bivariate choropleth map for the entire United States to show COVID cases per 1000 and percent change in property values together. This is a sample bivariate choropleth map for New Jersey by county made in Tableau available on [Tableau Public](https://public.tableau.com/profile/alysma#!/vizhome/NJCOVIDvs_PropertyValueChange-BivariateChoroplethMap/Dashboard1).

More details can be found on the [documentation page on Heroku](https://housing-covid.herokuapp.com/documentation).
