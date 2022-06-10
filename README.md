# surfs_up

## Overview of Project
The purpose of this project is to analyze weather data in Hawaii and decide if it makes sense to open a surf/ice cream shop on the beach. We want to make sure the weather is decent year-round from a temperature and precipitation perspective. For this challenge we analyze the months of June and December. The source of the data is SQLLITE, and we use python sqlalchemy and pandas modules.

## Results
![June](https://user-images.githubusercontent.com/103381098/173100316-2523749f-f2fe-4e65-ac61-6bb7ba7c23e2.png)
![December](https://user-images.githubusercontent.com/103381098/173100343-f5ec8582-b3fe-410d-9757-ee46d6b37098.png)

### Mean
It’s implied that the hotter the temps the more likely success an ice cream shop would have. The mean for June is 74.9 and December is 71.0. At the surface this doesn't appear to be a major difference. However, when we dig deeper we can see there are significant differences in temps for these months.

### Range
June has a min temp of 64 and max of 85 while, December has a min of 56 and max of 83. This is a significant difference in minimum values. The max value difference isn’t too significant between months.

### Percentiles 
June's 25th, 50th, and 75th percentiles are all in low to mid 70s. December’s percentiles are in high 60s to low 70s. Once again when we dig deeper, we can see that the temperature has lower lows in December.

## Summary
June's temperatures are high enough to suggest likely ice cream sales through the month. On the other hand, there is significant variability in December to raise concern. It might be helpful to close the ice cream shop on certain days/hours in December when it is colder. Another query about rain fall would be helpful. it's assumed that ice cream sales would be minimal if it’s raining. It would be beneficial to get another data set that has temperatures and ice cream sales. We can run a regression analysis and determine an inflection point where given a temperature ice cream sales could drop off.
