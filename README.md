# Crime-Rate-Dashboard-MongoDB-

This repository hosts the code and resources for analyzing global crime rates and creating interactive visualizations. The project leverages MongoDB Charts to build insightful dashboards and analyze crime-related metrics such as the crime index, safety index, and various criminality scores.

## Project Overview
The dashboard provides an intuitive and interactive way to analyze crime data across countries, highlighting key metrics like:

**Crime Index by Country:** Compare the perceived crime levels across different countries.
**Safety Index:** Visualize the perceived safety of each country.
**Criminality Scores Breakdown:** Understand the contribution of various factors such as criminal markets and actors.
**Resilience Score:** Assess a country's ability to combat crime and maintain order.
**Heatmap Analysis:** Identify high and low values for multiple crime dimensions across countries.

## Dashboard
👉 https://charts.mongodb.com/charts-project-0-wdxwsyh/public/dashboards/c610ef56-ddc6-4205-b775-15669953e22a

This dashboard is created using MongoDB Charts. It supports filtering, sorting, and interactive exploration of crime metrics for the top 10 countries.

## Dataset
👉 https://www.kaggle.com/datasets/shahriarkabir/crime-rate-by-country-2024?select=crime-rate-by-country-2024.json

|  Field          |  Type          |  Description          |
|  **country**          |  (String)          |  Name of the country.          |
**crimeRateByCountry_crimeIndex**	(Float)	: Overall crime index for the country.
**CrimeRate_OverallCriminalityScoreGOCI**	(Float)	: Overall criminality score (GOCI metric).
**CrimeRate_CriminalMarketsScore**	(Float)	: Criminal markets' contribution to crime.
**CrimeRate_CriminalActorsScore**	(Float)	: Criminal actors' contribution to crime.
**CrimeRate_ResilienceScore**	(Float)	: Resilience score, indicating the ability to combat crime.
**CrimeRateSafetyIndex**	(Float)	: Safety index, representing perceived safety.

The dataset is stored in JSON format for seamless integration with MongoDB.

## Features
* Interactive Visualizations: Analyze crime metrics via bar charts, heatmaps, pie charts, and scatter plots.
* Top 10 Insights: Focus on the top 10 countries for each metric, enabling detailed comparisons.
* Customizable: Easily extend the visualizations or dataset with additional data.
