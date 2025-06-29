# Predicting Dutch Election Votes with Spatial Autoregression

## Overview

This project was completed as Part 2 of the individual assignment for the course **RS: Spatiotemporal Data Analysis**.  
The task involves analyzing spatially structured data from the 2023 Dutch general elections and predicting the percentage of votes received by a political party at the municipality level.

Tasks: 
- Explore spatial autocorrelation
- Visualize geographic distributions
- Fit spatial econometric models
- Predict vote shares using cross-validated regression

## Dataset

Two key datasets were used:
- `2112066_spatial.csv`: Contains voting results and socio-economic features per municipality
- Shapefile: Dutch municipality boundaries (`gemeenten 2023 v1.shp` from `wijkbuurtkaart_2023_v1.zip`)

Features used include:
- Average house price  
- Average household income  
- Population density  
- Population increase  
- Total votes cast  
- Province code (`GrootOuderRegioCode`)
