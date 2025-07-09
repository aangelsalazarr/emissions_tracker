# Emissions Tracker
Purpose: to develop software tools for the analysis of emissions across the United States. 


## Bakken Emissions Tracker
### Context
- The Bakken Region contributed ~9% of total U.S. crude oil production (2024, EIA). The play spans across North Dakota and Wyoming, and the majority of Oil and Gas development exists in the Fort Berthold Reservation area. 
    - In this area, there exists both public and private operators.
    - Top 5 Public Operators: Chord Energy, ConocoPhillips, Hess, Devon and Exxon
    - Top 5 Private Operators: Continental Resources, Kraken Resources, Petro-Hunt, Slawson, and Lime Rock

### Projects Goals
- Automate the retrieval of monthly oil and gas production files and load into a master dataset that can be used for analysis. 
- Create functions aimed that processing and analyzing oil and gas data, focusing on:
    - Flaring
    - Production Trends (Growth)
    - Identifying Public and Private operators

## Notebooks
1. [Bakken Formation](bakken_ET.ipynb)
    - Focused on Bakken Play and Fort Berthold Reservation

## Datasets/Sources
- [Environmental Protection Agency](https://www.epa.gov/enviro/envirofacts-web-services)
- [North Dakota](https://www.dmr.nd.gov/oilgas/)
- [USA County Map](https://public.opendatasoft.com/explore/dataset/georef-united-states-of-america-county/export/?flg=en-us&disjunctive.ste_code&disjunctive.ste_name&disjunctive.coty_code&disjunctive.coty_name)
    - specifically, we will be downloading the .geojson file

## Required Packages
- Located in [requirements.txt](requirements.txt)