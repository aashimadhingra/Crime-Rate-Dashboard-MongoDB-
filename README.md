# Crime-Rate-Dashboard-MongoDB-

This repository hosts the code and resources for analyzing global crime rates and creating interactive visualizations. The project leverages MongoDB Charts to build insightful dashboards and analyze crime-related metrics such as the crime index, safety index, and various criminality scores.

## Project Overview
The dashboard provides an intuitive and interactive way to analyze crime data across countries, highlighting key metrics like:

* **Crime Index by Country:** Compare the perceived crime levels across different countries.
* **Safety Index:** Visualize the perceived safety of each country.
* **Criminality Scores Breakdown:** Understand the contribution of various factors such as criminal markets and actors.
* **Resilience Score:** Assess a country's ability to combat crime and maintain order.
* **Heatmap Analysis:** Identify high and low values for multiple crime dimensions across countries.

## Dashboard

![Screenshot 2024-11-23 114015](https://github.com/user-attachments/assets/9881b710-f583-4990-b314-883059878a0d)

For more detailed view:- 👉 [Link](https://charts.mongodb.com/charts-project-0-wdxwsyh/public/dashboards/c610ef56-ddc6-4205-b775-15669953e22a)

This dashboard is created using MongoDB Charts. It supports filtering, sorting, and interactive exploration of crime metrics for the top 10 countries.

## Dataset
👉 [Link](https://www.kaggle.com/datasets/shahriarkabir/crime-rate-by-country-2024?select=crime-rate-by-country-2024.json)

![image](https://github.com/user-attachments/assets/b114db01-9175-4822-b474-8b2d857974bf)


The dataset is stored in JSON format for seamless integration with MongoDB.

## Features
* Interactive Visualizations: Analyze crime metrics via bar charts, heatmaps, pie charts, and scatter plots.
* Top 10 Insights: Focus on the top 10 countries for each metric, enabling detailed comparisons.
* Customizable: Easily extend the visualizations or dataset with additional data.

* ![image](https://github.com/user-attachments/assets/0b1f65ec-a6be-4e68-9d82-17cde013da41)


* ## Pie Chart for Overall Criminality Scores
* **Implications:**

Visualizes proportional contributions of crime types to overall criminality, helping prioritize interventions.
Large segments (e.g., drug trafficking) demand immediate action, while smaller segments provide emerging threats to monitor.

* **Managerial Insights:**

Allocate funding and resources proportionally based on crime type dominance.
Prepare contingency plans for smaller crime segments with growth potential.


![image](https://github.com/user-attachments/assets/068ba31e-293a-491c-8425-78ef01fc2eae)


**Implications:**

Highlights interrelations between crime categories (e.g., property crimes and violent crimes). Strong correlations can suggest systemic criminal ecosystems.
Weak or negative correlations (e.g., safety index vs. crime index) might indicate differing societal priorities or inaccuracies in data reporting.

**Managerial Insights:**

Use strong correlations to design integrated interventions, such as addressing both property and violent crimes simultaneously.
Encourage uniform reporting standards to improve reliability in low-correlation data.

![image](https://github.com/user-attachments/assets/10a51da4-c240-4bc7-ad4f-6e0edbacbf96)


**Implications:**

Tracks how the crime index and safety index correlate over time or across regions.
Diverging trends may reflect societal resilience or a disconnect between perceptions and realities.

**Managerial Insights:**

Align policies to simultaneously improve safety perceptions and reduce actual crime rates.
Tailor interventions to bridge the gap between reported safety concerns and measurable crime reductions.

![image](https://github.com/user-attachments/assets/5004c6f2-4de2-42db-a4dc-38ad173f714a)

## Crime Index by Country (Bar Chart)
* **Implications:**

The chart ranks countries by crime index, spotlighting regions with critical crime concerns.
Mid-range countries can show promising trends or areas requiring moderate interventions to avoid escalation.

* **Managerial Insights:**

Concentrate anti-crime efforts on top-ranking countries to achieve maximum impact.
Leverage insights from mid-level crime countries to build scalable crime-prevention programs.

![image](https://github.com/user-attachments/assets/c87c2936-362f-4d0b-8d63-5f616c7ee5a6)

## Regional Comparison of Crime and Safety Indices (Grouped Bar Chart)
* **Implications:**

Compares multiple regions on crime and safety metrics, showing disparities that may relate to governance, infrastructure, or socioeconomic factors.
Regional differences indicate where to focus localized interventions.
* **Managerial Insights:**

Develop tailored, region-specific policies for high-crime, low-safety areas.
Use high-performing regions as templates for replication in struggling areas.

![image](https://github.com/user-attachments/assets/6db370ac-e36d-45ff-b361-425361c1ae43)

## Crime Rate vs. Resilience Score (Scatter Plot)
* **Implications:**

Shows whether resilience factors (e.g., law enforcement capacity, social policies) are effectively reducing crime rates.
Outliers (e.g., high crime but high resilience) indicate inefficiencies or other external factors.
* **Managerial Insights:**

Investigate high-crime, high-resilience outliers for underlying issues, such as corruption or economic inequality.
Increase resilience scores in low-resilience, high-crime areas to address systemic vulnerabilities.

![image](https://github.com/user-attachments/assets/4a04d3d6-c36f-412a-b6d3-4947bd6d1884)

## Criminality Score Breakdown (Stacked Bar Chart)
* **Implications:**

Provides a detailed view of crime category dominance (e.g., cybercrime, drug trafficking).
Regional or country-specific dominance indicates focused crime networks.
* **Managerial Insights:**

Allocate resources to disrupt dominant crime categories in specific regions.
Monitor smaller categories for potential growth trends, which may require future interventions.

![image](https://github.com/user-attachments/assets/e1a5ef53-78b1-4968-a675-62c5551d93d1)

## Distribution of Criminality Scores (Histogram)

* **Implications:**

Identifies common criminality score ranges, helping to understand patterns across countries.
Extreme scores may reflect chronic issues or strong mitigation success stories.

* **Managerial Insights:**

Use clusters of countries with similar scores to design regional programs.
Examine outliers to identify best practices or significant gaps in governance.






