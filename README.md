# London Bike Rides Data Analysis

## Introduction
This project aims to analyze bike ride data in London to uncover patterns and insights. The data is fetched from Kaggle, manipulated for specific needs, and visualized using Tableau. The visualizations help in understanding the trends and usage patterns of bike rides in London.

## Aim
The main aim of this project is to perform data manipulation and visualization to gain insights into the bike riding patterns in London. This includes analyzing the total rides, moving averages, and the impact of weather on bike rides.

## Data Extracted & Ingested
The dataset used in this project is obtained from Kaggle. You can find the dataset [Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)

## Data Manipulation
The data manipulation process involves cleaning and transforming the data to make it suitable for analysis and visualization. This includes handling missing values, transforming date-time fields, and creating new features.

## Data Visualization in Tableau
The Tableau dashboard created for this project includes five main charts:

* Total Rides Number: This chart shows the total number of bike rides over the selected period.
  
![TotalRidesCount](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/TotalBikeRidesCount.png)

* Moving Average Chart: This curved line chart displays the moving average of bike rides. It includes toggles to select the time frame (days, weeks, months) and an input to filter the moving average by a specific number (e.g., 10 days, 10 weeks).
![MAC](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/MovingAverage.png)

* Weather Heatmap: This heatmap visualizes the temperature (in Celsius) against wind speed (in kph), providing a visual representation of weather conditions.
![WeatherHeatmap](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/WindTempHeatmap.png)

* Weather Conditions Chart (Tooltip): A bar chart showing various weather conditions such as clear, broken clouds, scattered clouds, rain, cloudy, and snowfall. This chart is displayed as a tooltip within the main charts.
![WeatherBar](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/WeatherBar.png)

* Hourly Rides Chart (Tooltip): A bar chart displaying the number of rides taken per hour in a 24-hour format. This chart is also displayed as a tooltip within the main charts.
![HourBar](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/HourBar.png)

## Result
The entire dashboard provides a comprehensive view of the bike riding patterns in London. It combines various charts to show total rides, moving averages, weather impact, and hourly distribution of rides.

* Example 1
![Example1](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/Dashboard.png)

* Example 2
![Example2](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/Dashboard1.png)

* Example 3
![Example3](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/Dashboard2.png)

* Example 4
![Example4](https://github.com/shovit504/LondonBikeRidesAnalysis/blob/main/images/Dashboard3.png)

Here is Link to [Tableau Public](https://public.tableau.com/app/profile/shovit.prusty/viz/londonBikeRides/BikeRidesLondon)

## Conclusion
Using this dashboard, we can gain valuable insights into bike riding behavior in London. The analysis helps in understanding how weather conditions and time of day affect bike rides, which can be useful for urban planning, bike-sharing schemes, and improving transportation infrastructure.
