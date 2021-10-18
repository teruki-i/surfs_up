# Analysis of Weather in Oahu
## Overview
This analysis used SQLite to examine temperature data collected in Oahu, Hawaii from 2010 to 2017 to compare temperatures in June and December. More specifically, based on the change in temperature between June and December, this analysis saught to determine whether a surf and ice cream shop business can feasibly operate year round.

## Results
![June_temp_stats](https://github.com/teruki-i/surfs_up/blob/main/Resources/June_temps.png)
![Dec_temp_stats](https://github.com/teruki-i/surfs_up/blob/main/Resources/Dec_temps.png)

The summary statistics suggest that overall, the temperature doesn't drastically change between June and December. The average June temperature 74.9°F and the average December temperature was 71.0°F. The 25th percentile for June was 73.0°F and the 75th percentile was 77.0°F while the 25th percentile for December was 69.0°F and the 75th percentile was 74°F.

For June, the lowest recorded temperature was 64.0°F and the higest was 85.0°F. However, with an interquartile range of 4.0°F, any temperatures below 67.0°F (73.0°F - 6.0°F) or above 83.0°F (77.0°F + 6.0°F) are outliers in June.

On the other hand, for December, the lowest tempeature was 56.0°F and the highest was 83.0°F. However, these temperatures are also outliers. With an interquartile range of 5.0°F, anything below 61.5°F (69.0°F - 7.5°F) or above 81.5°F (74.0°F + 7.5°F) is an outlier.

These results suggest that we can expect the temperature in Oahu to generally be in the mid-70°F range in June while it would be a few degrees lower, generally in the low-70°F range in December.

## Summary
Based on this analysis, the surf and ice cream shop business should be able to operate year round. The temperature data shows that we can expect Oahu to have mildly warm weather throughout the year. Though the data also suggests that June is slightly warmer, in general, there isn't a large difference between June and December weather.

This conclusion is further backed up by precipitation data for both June and December. 

An average June day has 0.14 inches of rain while an average December day has 0.21 inches of rain. This suggests that there is an increase in rain between June and December. However, the median daily precipitation is only 0.02 inches in June and 0.03 inches in December. Furthermore, histograms for both months show that there is a right skew in the data for both. While days with no rain far outnumber days with any rain at all in both months, a few data points of extreme weather pull the averages up. In other words, in both months, we should expect mild weather with little to no rain.

![June_precip_hist](https://github.com/teruki-i/surfs_up/blob/main/Resources/June_precip_hist.png)
![Dec_precip_hist](https://github.com/teruki-i/surfs_up/blob/main/Resources/Dec_precip_hist.png)
