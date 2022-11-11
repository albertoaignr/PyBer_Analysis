# PyBer_Analysis

## Overview 

In this challenge, we will be using python and pandas library to create a summary dataframe where we can visualize some important data from the ride-sharing data of an app. Sorting data for a better visualization can give useful information to make analyses of, the weekly fares for different types of cities are going to be displayed on a line chart through the first quarter of the year 2019 and an evaluation of directions related to that data will be summarized.

Pandas library will be helpful to organize our dataset and present it in a clear way, also with 'matplotlib.pyplot' functions to make a graphical interpretation of the data. By means of 'groupby()' function and some styling properties, results will be acknowledged.  

# Results 

It will be presented the summary table from the data, where it can be easy to view some information for the different city types.

![Summary_table.png](/Analysis/Summary_table.png)

From this summary, we could say that Urban cities have more amassed volume of clients than the Rural or Suburban. also the difference in total drivers and rides represents the competitivity in the market for the usage of the app.

Though it is a nice representation of the results, this 'fare' value is fluctuating over time. To get a better view of how this value changes, a cropped representation will be shown. Where data was filtered to display the first quarter of the year 2019 and a line chart showing the timelapse of the fares per city types is plotted. 

![PyBer_fare_summay.png](/Analysis/PyBer_fare_summary.png)

In this plot similarly evident the usage of the app in Urban cities and that theres is a continuity in the variability over time that follows a similar trend for every type of city.

# Summary

Final words can be said in regards of this findings, considerations can be made in the following aspects:

- Address disparity of drivers/rides, maybe it can be that people are doing it as a part time and some people making a career out of it. Evaluating a better approach for the app depending on the city, giving more focus to the Urban type as is the one with greater demand.
- As Rural ciies are the ones are the bottom of the chart, indicating that the revenue is lower, it can be designed a strategy with users to increase the usage of the app, maybe with partnerships and discounts that have direct impact in the average fare.
- Suburban cities follow a kind of stable trend (as offer-demand, represented in Drivers-Rides summarized data), where a survey within the users/drivers might help identify this trend and even serve as an example on the way of addressing disparities. 


