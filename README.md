# bikesharing

## Overview

The purpose of this analysis was to determine if a bike sharing service would be feasible in Des Moines, Iowa. Data from the bike sharing service Citi Bike in New York City is used in this analysis. Factors such as gender breakdowns of riders, how long bikes were rented, when bikes were rented, bike use in customers vs subscribers, total rental time of each bike, etc. were examined. 

Data was downloaded from the Citi Bike website in a csv format. It was then loaded into python and data types were changed using Pandas and downloaded into a modified csv file. The modified csv was loaded into Tableau, where various visualizations and a data story were created. 

## Results 

The following link shows the full story created for this challenge in Tableau: 

[link to dashboard](https://public.tableau.com/app/profile/emarie.covey/viz/NYCcitibike_16592842809790/NYCStory?publish=yes "link to dashboard")

The following are visualizations from the story, and include the main results of the images in the comments on each image: 

![gender](https://github.com/emariecovey/bikesharing/blob/main/Story_images/gender.png)

![rentalduration](https://github.com/emariecovey/bikesharing/blob/main/Story_images/rentalduration.png)

![rentaldurationgender](https://github.com/emariecovey/bikesharing/blob/main/Story_images/rentaldurationgender.png)

![rentaltiming](https://github.com/emariecovey/bikesharing/blob/main/Story_images/timing.png)

![rentaltiminggender](https://github.com/emariecovey/bikesharing/blob/main/Story_images/timinggender.png)

![subvscust](https://github.com/emariecovey/bikesharing/blob/main/Story_images/subscribersvscustomers.png)

![bikeuse](https://github.com/emariecovey/bikesharing/blob/main/Story_images/bikeuse.png)

## Summary
Here is a summary list of the analysis: 
- About 2/3 of all riders are male. 1/4 of riders are female, and the rest are unknown. Rider gender is usually known more for subscribers than for customers, who are more temporary.
- The vast majority of bikes are returned within 20 minutes of being checked out. This is the same for both genders, though "unknown" genders (who are typically customers instead of riders) tend to take bikes out for longer times (typically 10-30 minutes).
- Most bikes are rented during commuting hours (around 8am and also 5-6pm on weekdays). These bikes are generally used by subscribers. On the weekends, bikes are rented generally after 9am and before 6pm, with most of the rentals occurring in the middle of the day. These bikes are generally used by customers.
- Most bikes have light to moderate use, but a few bikes have had significantly longer trip durations. These few bikes may be pinpointed and may require additional bike maintenance or replacement. 

Two additional visualizations that would be beneficial to this analysis are: 
- visualizing birth year and user type. This would help to see if there are age differences between customers and subscribers, and could help with marketing the bikes. This is because avertisements to subscribers would be different from advertisements to customers, and advertizing is also age-depedent. Perhaps subscribers are young working professionals commuting to work, and customers are older tourists visiting the city on weekends.
- visualizing start station ID and end station ID. This would help to see where bikes are going. Are bikes flowing evenly, or are they pooling or running out in certain stations? If so, bikes would potentially need to be transported to even out availability throughout the stations. 
