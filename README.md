# Bikeshare

[Link To Dashboard](https://public.tableau.com/app/profile/mateo.rul/viz/NYCBikeShareFinal/Story1?publish=yes)

## Overview of Analysis

Using data provided by Citi and their New York City bike share program, we will analyze ridership trends and demographics for August 2019. We will use Tableau to visualize our data and also use Pandas to help clean up our dataset.

## Results

#### Mapping Popular Start Locations
![Map](https://github.com/rulma/Bikeshare/blob/dff062ae6397e91765f03657879d3e4e78ecb3ac/Map.PNG)

Here we can see where the most popular starting locations are for riders. As we can see the majority of the largest circles are congregated on the southern tip of Manhattan. This makes sense as this is the central commercial district for New York City.


#### Peak Hours
![Hours](https://github.com/rulma/Bikeshare/blob/77023619df4f6edc4fe7d7bbe92936fbed25f247/Peak%20August%20Hours.PNG)

Displayed here is the peak hours for August displayed on a horizontal bar chart. Each bar indicates and hour on the 24-hour time scale. As you would expect bike rides are at their lowest in the early morning hours and highest during major commuting times.


#### Average Ride Time
![Ride Time](https://github.com/rulma/Bikeshare/blob/77023619df4f6edc4fe7d7bbe92936fbed25f247/breakdown%20of%20trip%20time.PNG)

Broken down by ride time, we can see that most bike rides last between 5-20 minutes. As ride duration increase the number of rides decreases. It seems that most users use the bikes for fast and short distanced travel around the city.

### Gender Breakdown
![Gender](https://github.com/rulma/Bikeshare/blob/039cc3c12cfa8e32d98a1d4196590cc567fabf42/Gender.PNG)

Above is the breakdown for gender of riders. Yellow for Males, blue for Females, and red for Unknown. Over 60% of riders are males. Understanding this breakdown will help us understand the next few visualizations.


#### Average Ride Time by Gender
![Gender Ride Time](https://github.com/rulma/Bikeshare/blob/77023619df4f6edc4fe7d7bbe92936fbed25f247/Breakdown%20of%20trip%20down%20gender.PNG)

We can see how the gender breakdown affects the above visualization. Since males make up most riders, we can see that most trips regardless of trip distance, are completed by males. The trend that of most rides being short holds true regardless of gender.


#### Peak Hours by Weekday
![Heat](https://github.com/rulma/Bikeshare/blob/main/Peak%20Trip%20hours.PNG)

Now we look at when rides are completed throughout the week. Ridership fluctuates throughout the week depending on the day and time. We can see a trend around typical commuting time. Monday through Friday we see that many rides are done at 8am and 5-6pm. This pattern doesn’t hold into the weekend as rides become more dispersed across the day. 
We could assume that riders during the work week are commuting to and from work and on the weekend are biking to do recreational activities.


#### Peak Hours by Weekday and Gender
![Heat G](https://github.com/rulma/Bikeshare/blob/77023619df4f6edc4fe7d7bbe92936fbed25f247/Peak%20Trip%20Hours%20by%20Gender.PNG)

Again, we can see the disparity in riders’ gender. We can clearly see how male riders make up most rides. All genders do seem to follow the previous trends of workday commutes from Monday through Friday and recreational rides throughout the day on the weekends.


## Summary

The dashboard we have created provides a good overview of who is riding bikes, where are they going, when are they biking, and how long they spend biking. We created a neat and visually appealing way to look at some descriptive data. Despite this I believe it would be beneficial to add some more visualizations. We could start off by looking at the relationship between the day of the week and which stations are being used. From this we could potentially see trends in how riders change their behavior and location depending on whether it is a workday. Another interesting visual would be to display how ride length changes depending on the weekday. It would be interesting to see if people go on longer, more leisurely rides on the weekends compared to weekdays.
