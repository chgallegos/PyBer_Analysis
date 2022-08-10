# PYBER ANALYSIS
----
## Overview
The purpose of this analysis is to describe the differences in ride sharing by comparing urban, suburban and rural types of cities compared to the fares being generated by drivers.
The data was subcategorized by extracting total rides, total drivers, total fares, average fare per ride and average fare per driver. This data was finally put into a multiple line chart in order to provide a visual analysis of the different ride types.
----
## Results

The analizis began by extracting the data for total rides, total drivers, total fares, average fare per ride and average fare per driver using the groupby() method.

![Screenshot](https://github.com/chgallegos/PyBer_Analysis/blob/main/resources/total_drivers.png)
![Screenshot](https://github.com/chgallegos/PyBer_Analysis/blob/main/resources/average_fare_per_driver.png)

This was put together on the following summary dataframe:

![Screenshot](https://github.com/chgallegos/PyBer_Analysis/blob/main/resources/summary_df.png)

Once the data was summarized, a portion of the data from January 2019 to April 2019 was sampled in order to create a multiple line chart that shows the differences in how much fare revenue is being brought in by different city type. 

![screenshot](https://github.com/chgallegos/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

The plot indicates that the urban portion of the business has the highest fare revenue overall, followed by suburban and lastly rural rides. Another interesting pattern shows that there is a consistent spike increase towards the end of February across all city types.

![screenshot](https://github.com/chgallegos/PyBer_Analysis/blob/main/analysis/fare_summary_annotated.png)

----
## Summary 

Based on the results of the analysis, there are three recommendations to provide:

- Urban type of cities have the most potential for business, however, it seems that the average fare per driver seems to be lower than average fare per ride. An incentive for multiple rides could be put in place in order to get more drivers on the streets gettigng more customers, therefore increasing the revenue for urban areas.

- Given the spike at the end of February, marketing efforts to incetivize customers during this high demand time could also increase revenue accross the board. It could be either a discount or referral programs for recommending the app to new users.

- It seems that rural cities do have less rides that are more expensive, therefore more distance is covered by the rides. An incentive to drivers with electric vehicles could be an interesting direction as longer distances driven by electric vehicles are more efficient overall in the total cost per mile, therefore the drivers could make more money and the fares could be more accessible for rural customers.