# PyBer Analysis

## Project Overview

Conduct an exploratory analysis on data for very large CSV files. The exploratory analysis includes several types of visualizations to tell a compelling story about the data. The visualizations are made using python scripts using Panda's libraries, the Jupyter Notebook, and MatPlotlib to create a variety of charts that showcase the relationship between the type of city and the number of drivers and riders, as well as the percentage of total fares, riders and drivers by type of city. The analysis and visualizations provided will help PyBer improve access to ride sharing services and determine affordability for underserved neighborhoods.

## Resources
**Resources:** All data used in this analysis is found inside of the [Resources](https://github.com/pfrivas/PyBer_Analysis/tree/main/Resources) folder.

**Software:** Python Data, Anaconda, Jupyter Notebook

**Language:** Pandas, NumPy, and Matplotlib

**Code:** [PyBer Challenge](https://github.com/pfrivas/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## Results

### Average Fare vs Total Number of Rides Bubble Chart
- Bubble size is based on the total number of drivers for each city type, including urban, suburban, and rural.
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Fig1.png>

If we compare the average number of rides between each city type, we'll notice that the average number of rides in the rural cities is about 3.5 and 2.5 times lower than urban and suburban cities, respectively.

### DataFrame Summary
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/PyBer_Summary_DataFrame.png>

### Box-and-whisker plots to determine if there are any outliers:
- **The number of rides for each city type.**
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Fig2.png>

- **The fares for each city type.**
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Fig3.png>

- **The number of drivers for each city type.**
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Fig4.png>

- **Findings:**
There is one outlier in the urban ride count data. Also, the average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities. The outlier for the urban_ride_count is 39. From the combined box-and-whisker plots, we see that there are no outliers. However, the average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities. The average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities

### Pie chart that visualizes each of the following data for each city type:
- **The percent of total fares.**
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Fig5.png>

- **The percent of total rides.**
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Fig6.png>

- **The percent of total drivers.**
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Fig7.png>

- **Findings:**
Urban cities make up 62.7% of total Fares, 68.4% of total rides, and has 80.9% of total drivers.
Suburban cities make up 30.5% of total Fares, 26.3% of total rides, and has 16.5% of total drivers.
Rural cities make up 6.8% of total Fares, 5.3% of total rides, and has 2.6% of total drivers.

### Line Chart for Total Fare by City Type 
<img src = https://github.com/pfrivas/PyBer_Analysis/blob/main/Analysis/Pyber_fare_summary.png>

- **Findings:**
There is a larger amount of both drivers and users in urban cities, thus the majority of PyBer's revenue occurs in urban cities, followed by suburban and then rural, respectively.

## Summary (Buisness Reccomendations) 

### Identifying and Predicting Trends
- Theres is an opportunity to expand the analysis by adding more data points throughout the entire year that could provide insights to yearly trends in order to predict trends for future years and see if all city types have the same trends and determine other factors that contribute tot the high ride costs in rural  cities and loe drive fares in urban cities. Once the other factors are determined fares could be adjusted accordingly.

### Demographics of users
- Theres is an opportunity to expand the analysis by including data that provides insights on the demographics of users in order to target marketing strategies to consumers according to the demographic environment of each of the different city types in order to increase revenue in suburban and rural cities to those of urban cities which has the highest usage of the ridesharing services.

### Rewards Program
- Theres is an opportunity to expand the analysis by providing a rewards program that not only rewards loyal riders and drivers but also attracts new ones. The data from the rewards program can provide insights on usage of the ridesharing services and see if any trends had changed.
