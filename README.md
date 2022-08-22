# Surfs-Up
## Overview & Background
After a vacation to Hawai'i, I wanted to come up with an idea that would allow me to return and work there permenantly. Surf n' Shake shop is a small business idea that would rent surf boards and serve ice cream. Local Hawaiian surfer, W. Avy, has expressed interest and invested early on, however, his concern is weather. He's had a surfshop get destroyed by rain in the past and would like to run a weather analysis on Oahu, where the shop would live. After analyzing and providing the initial run down on the dataset, W. Avy would like to gather temperature data specifically for June and December in order to determine if the business is sustainable year round. 

### Resources
- SQLite
- SQLAlchemy

## Results
The analysis provides three key differences in weather between June and December. 

1) The data counts are different. For some reason the data set has more data for the months of June than December. We have almost 200 more results for June than December. 
2) There is only a 3 degree difference in the average temperatures between June and December. 
3) When looking at minimum temperatures, December can get much colder than June. About a 10 degree difference. 

Below are images of the data tables with key information for June and December. 

<img width="343" alt="Screen Shot 2022-08-21 at 8 42 17 PM" src="https://user-images.githubusercontent.com/107595127/185834332-5e928763-67fe-4325-8223-f16d79f8cc28.png">

<img width="390" alt="Screen Shot 2022-08-21 at 8 44 52 PM" src="https://user-images.githubusercontent.com/107595127/185834392-fbdb2567-7812-4ff0-9cb7-cfc8b2d7e2e1.png">

## Summary
Overall, I've successfully run a weather analysis on the months of June and December as requested. I've organized the results in a coherent table and we can go from there. But in order to make this analysis better, especially if weather condition is the main concern, it would be worth adding that to the analysis. Precipitation and the effects that heavy percipitation has on small businesses could be a useful factor to look at. Adding precipitation will tell us how much rain we can expect in those months, the damage to prepare for, and how rain effects the surf. Surf reports and forecasts is another major factor to consider and run an analysis on for the months of June and December. 
