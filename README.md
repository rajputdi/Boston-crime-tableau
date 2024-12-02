# Boston Crime Incidents Analysis Dashboard

## Overview

This Tableau project provides a comprehensive analysis of crime incidents across Boston neighborhoods. The dashboard visualizes key metrics and trends to help users understand the patterns and frequency of crimes over time, by location, and by hour of the day. With interactive features and insightful metrics, this tool is designed to support data-driven decision-making for enhancing community safety and planning resource allocation.

![image](https://github.com/user-attachments/assets/4ddec05b-d4a4-4aba-9193-27612032bb08)


## Features

1. **Moving Average of Crimes**:
   - The dashboard displays a 3-day moving average of crime incidents, smoothing daily variations to reveal overall trends.
   - The moving average identifies periods of heightened crime activity, such as spikes in late September.

2. **Crime Distribution by Zip Code**:
   - A donut chart shows the distribution of crimes across Boston zip codes.
   - **Insights**:
     - **Zip Code 2124 (Dorchester)**: Reports the highest number of incidents at **10,220 crimes**, indicating a significant hotspot.
     - Other zip codes like **2125 (2,208 crimes)** and **2122 (1,655 crimes)** also highlight areas with notable criminal activity.

3. **Hourly Crime Patterns**:
   - An interactive tooltip reveals the hourly breakdown of crimes when hovering over the moving average bands.
   - **Insights**:
     - Crime activity peaks during evening hours (e.g., **17:00–18:00**) and dips in the early morning hours (e.g., midnight and 1:00 AM).

4. **Interactive Parameters**:
   - The dashboard includes parameters for flexible analysis:
     - **Moving Average Duration**: Adjust the number of days, weeks, or months to calculate trends.
     - **Moving Average Period**: Toggle between time frames (e.g., day, week, month) for granular or aggregated trend views.

5. **Reference Bands for Moving Average**:
   - Shading is used to dynamically highlight the selected moving average range, making it easier to focus on specific periods of interest.

6. **Expandable Donut Chart for Zip Code Analysis**:
   - Hovering over a segment of the donut chart expands the section and displays detailed information, such as the specific neighborhood, crime count, and percentage contribution to overall crimes.
   - This dynamic visualization enhances user engagement and exploration of location-specific crime data.

## Data Source

The crime-related dataset is sourced from the [Boston Police Department's Crime Hub](https://boston-pd-crime-hub-boston.hub.arcgis.com/datasets/d42bd4040bca419a824ae5062488aced_0/about). The dataset includes detailed information on crime incidents, including location, date, time, and type of crime.

## Recommendations

As an analyst, the following insights and recommendations can be derived from the dashboard:

1. **Neighborhood Focus**:
   - Areas like **Dorchester** (10,220 crimes) and **Roxbury** (5,450 crimes) should be prioritized for increased police patrols and community safety initiatives.
   - Deploy additional resources to zip codes such as **2124** and **2125** to address crime hotspots effectively.

2. **Time-Based Resource Allocation**:
   - Reinforce police presence during peak crime hours, particularly in the late afternoon and early evening (e.g., **17:00–18:00**).
   - Reduce patrolling resources during early morning hours when crime rates are consistently low.

3. **Community Engagement**:
   - Conduct community outreach programs in high-crime neighborhoods to foster trust and encourage reporting of suspicious activities.
   - Collaborate with local organizations to implement neighborhood watch programs.

4. **Seasonal and Periodic Trends**:
   - Prepare for seasonal crime spikes by analyzing moving average trends over specific periods.
   - Leverage historical data to anticipate high-crime periods and proactively deploy resources.

## Conclusion

The Boston Crime Incidents Analysis Dashboard provides actionable insights to help law enforcement and policymakers reduce crime rates and enhance public safety. By using the dashboard, stakeholders can identify crime hotspots, allocate resources effectively, and implement data-driven safety measures.
This tool not only highlights where crime is occurring but also provides the "when" and "why," making it an indispensable resource for tackling Boston's crime challenges.
