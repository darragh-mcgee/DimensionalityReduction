# NYC Shootings: PCA and Spatial Analysis

This project applies principal component analysis (PCA) and spatial PCA (sPCA) to explore the relationships between structural disadvantage, residential instability, and firearm-related violence in New York City census tracts.

Negative binomial regression models are used to assess the relationship between these structural dimensions and shooting incident counts, incorporating spatial diagnostics and visualizations.

## Contents

- `NYC_Shootings_PCA_Analysis_Code.Rmd`: Full analysis in R Markdown
- `Final_Report.pdf`: Completed paper write-up
- `ACS Data/`, `tl_2020_36_tract/`, `NYPD_Shooting_Incidents.csv`: Data sources

## Methods Overview

- Construction of concentrated disadvantage and residential instability indices from ACS variables
- Principal component analysis (PCA) and spatial PCA (sPCA)
- Negative binomial regression with robust standard errors
- Spatial diagnostics using Moran’s I
- Thematic mapping of PCA scores and model residuals

## Data Sources

[1] U.S. Census Bureau. American Community Survey (ACS) 5-Year Estimates, 2019–2023.  
https://data.census.gov/
[2] NYPD Historic Shooting Incident Data (2019–2023). NYC OpenData.  
https://data.cityofnewyork.us/Public-Safety/NYPD-Historical-Shooting-Incident-Data-2023/833y-fsy8
[3] U.S. Census Bureau. TIGER/Line Shapefiles: 2020 Census Tracts, New York State.  
https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html
