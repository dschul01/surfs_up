# Surfs Up
Analysis on weather data utilizing SQLAlchemy, SQLite, Jupyter Notebook, Python and Pandas

## Overview of Surf's Up Analysis
The purpose of this project is to utilize SQLAlchemy to query a SQLite database containing weather data from weather stations across Oahu, HI.  The two key elements to be analyzed are precipitation amounts and temperatures within the months of June and December over multiple years to determine if it's viable to open up a surf and ice cream shop in Oahu, HI.

## Results
The first deliverables requires using Python, Pandas, and SQLAlchemy to retrieve all temperatures for the months of June and December across multiple years, and then providing summary statistics.  Summary statistics for precipitation amounts were later combined to provide more robust analysis for the viability of the shop.  The resulting stats for June and December are below and indicate the following:

* The difference between mean temperatures across June and December is nominal at 3.9 degrees; 5% of June's mean.
* The difference between mean precipitation amounts across June and December is 0.08 inches; 59% of June's mean.
	- Despite the significant increase over June, the average rainfall per day in December is just over 0.2 of an inch.  
* The largest weather variance between June and December is the minimum temperature with a low of 56 in December compared to 64 in June.


<img src="https://github.com/dschul01/surfs_up/blob/main/Resources/Jun_Temp_Precip_Stats.png" width="300" height="200"> | <img src="https://github.com/dschul01/surfs_up/blob/main/Resources/Dec_Temp_Precip_Stats.png" width="300" height="200">



## Summary
Based on the temperature and precipitation statistics, it seems a surf and ice cream shop in Oahu would be open for business most of the year.  It is important to ensure the weather is consistent across the island and whether elevation has impacts on temperatures or precipitation.  Additional analysis was performed to review weather at the stations across Oahu.  The chart below indicates elevation doesn't appear to be a major factor in weather patterns.  For instance the highest station, Upper Wahiawa's average temperature and precipitation amounts is between other stations' at lower elevations.  The same is true for the station at the lowest elevation, Honolulu Observatory.  Therefore other factors should be considered when choosing the exact location.    



![Temp_Precip_Station.png](https://github.com/dschul01/surfs_up/blob/main/Resources/Temp_Precip_Station.png)

There are many other factors such as demand, financing, competition, etc. that should be reviewed to make a final decision which should be considered before opening the shop.


