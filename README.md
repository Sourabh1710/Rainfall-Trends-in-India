# Rainfall Trends Analysis in India (1901-2025)

## Project Overview

This project aims to analyze rainfall trends in India from 1901 to 2025, focusing on seasonal variations, yearly trends, and the impact of climate change using Python. The analysis is based on historical rainfall data, examining patterns across different regions and timeframes.

## Dataset

The dataset used in this project contains:
- Year
- Month
- Region
- Rainfall (mm)
- Temperature (°C)

## Objective

The primary objectives of this project are:
- To analyze yearly and seasonal rainfall trends in India.
- To identify regions with significant fluctuations in rainfall.
- To explore the correlation between temperature and rainfall.
- To assess long-term patterns and anomalies due to climate change.
- To visualize trends and provide insights for agricultural and policy decisions.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- plotly

## Data Cleaning and Preprocessing

The **Rainfall (mm)** column was cleaned and converted into numeric format to ensure accurate analysis. Missing values were handled using appropriate imputation techniques.

## Rainfall Distribution by Season

The analysis indicates that the monsoon season contributes the highest rainfall, with significant variations across different years.
  
![Rainfall Distribution by Season](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Seasonal_Rainfall_Distribution_in_India.png)

## Yearly Rainfall Trends

A declining trend in annual rainfall is observed in certain regions, indicating possible climate change effects.

  
![Yearly Rainfall Trends](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Trend_in_Annual_Rainfall_in_India.png)

## Rainfall Trends by Month

Monsoon months (June-September) show the highest rainfall, while winter months record minimal precipitation.

  
![Rainfall Trends by Month](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Average_Monthly_Rainfall_in_India.png)

## Top Regions by Rainfall

| Region          | Average Rainfall (mm) | Peak Rainfall (mm) | Year of Peak |
|----------------|----------------------|--------------------|--------------|
| Meghalaya      | 9000                  | 12000              | 1986         |
| Kerala        | 4000                  | 7500               | 2018         |
| Assam         | 3500                  | 6800               | 2004         |
| Maharashtra   | 3200                  | 6000               | 2019         |
| West Bengal   | 3000                  | 5600               | 1999         |

Assessing the Impact of Climate Change in the Rainfall Trends in India

A 10-year rolling average of annual rainfall is calculated to identify long-term trends and smooth out short-term variations. This helps assess the potential impact of climate change on rainfall patterns.

This graph shows the annual rainfall trends in India (blue line) and a 10-year rolling average (red line) to identify long-term patterns. While annual rainfall exhibits significant variability, the 10-year rolling average indicates a slight downward trend post-1960, suggesting a possible impact of climate change on rainfall distribution.

![Annual Rainfall Trends](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Impact_of_Climate_Change_on_Rainfall_Patterns.png)

Detecting Anomalies in the Rainfall Trends in India

Using the Isolation Forest algorithm, anomalies in both annual and monthly rainfall are identified to highlight years or months with unusual rainfall patterns.

This graph highlights years with significant rainfall anomalies, where annual rainfall deviated substantially from the mean. Drought years (e.g., 1905, 1965, 2002) and extreme rainfall years (e.g., 1917, 1961) are marked as red points, showcasing outliers in rainfall patterns.

![Annual Rainfall Anomalies](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Annual_Rainfall_Anomalies_in_India.png)

Now, let’s identify anomalies in monthly rainfall.

The variability is most pronounced during the monsoon months (June to September), which reflects the critical role of these months in India’s rainfall dynamics. Anomalies in non-monsoon months, while less frequent, highlight unusual weather patterns potentially linked to climate variability or regional disturbances.

![Monthly Rainfall Anomalies](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Monthly_Rainfall_Anomalies_in_India.png)

Correlating Seasonal Rainfall with Annual Totals

The correlation coefficients between seasonal rainfall and annual rainfall totals are calculated to understand how much each season contributes to the overall yearly rainfall.

This graph shows the correlation between monsoon rainfall and rainfall during other seasons. The October-December season has the highest correlation (0.29), suggesting a moderate relationship, possibly due to post-monsoon retreat rains. The January-February (0.14) and March-May (0.10) seasons exhibit weaker correlations, indicating minimal dependence on monsoon rainfall.

![Seasonal Rainfall Correlation](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Correlation_Between_Monsoon_Rainfall_and_Other_Seasons.png)

Grouping Years Based on Rainfall Patterns

Using k-means clustering, years are grouped into three categories: Dry, Normal, and Wet, based on rainfall patterns.

The clusters reveal that most years fall into the Normal category, while Wet years (above-normal rainfall) are sporadically distributed throughout the timeline, with a concentration in the early and mid-20th century. Dry years (below-normal rainfall) are more frequent in the latter half of the timeline, indicating a potential shift in rainfall patterns over time.

![Rainfall Clustering](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Clustering%20of%20Years%20Based%20on%20Rainfall%20Patterns.png)

Forecasting Future Rainfall

Using the Prophet library, annual rainfall is forecasted for the next 20 years.

The blue line represents the model’s forecast trend, while the shaded area indicates the confidence interval. The trend reveals a slight decline in annual rainfall over time, with notable year-to-year variability (black dots representing actual data points). This forecast highlights the need for adaptive strategies to manage potential water resource challenges.

![Rainfall Forecast](https://github.com/Sourabh1710/Rainfall-Trends-in-India/blob/main/images/Annual%20Rainfall%20Forecast%20Using%20Prophet.png)

## Conclusion

The analysis reveals that:
- Monsoon contributes the highest rainfall.
- Northeast India receives the most rainfall, while Rajasthan and Gujarat remain the driest.
- A decline in rainfall is noticeable in certain regions due to climate change.
- Temperature rise correlates with decreasing rainfall in some areas.

This project provides insights into India's changing rainfall patterns, helping policymakers and researchers address climate concerns.


## Author

Sourabh Sonker  
Data Science Enthusiast

