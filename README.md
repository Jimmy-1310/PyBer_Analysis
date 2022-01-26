# PyBer_Analysis

## Overview

During this module, I was tasked with the job of creating visualizations based on the data of a small driving company. During the module, I was able to create a variety of graphs such as pie charts, box plots and sactter plots. This visualizations helped us understand the relation and how the data correlate with each other. It was pretty clear to contrast and compare the diference between the apps performance in the different types of cities it worked on.
The challenge consisted of creating a graph that helped understand the performance of each city type in terms of total fare through several weeks. For this I needed to devide and store the total fare for each city type and store it by weeks, in order to be avaible to graph it. Once the data was stored in a data frame with the week as the index, the city type as the columns and the total fare as the values, I was able to create a graph that will facilitate decision making in the future.

For this project I learned to use Matplotlib.pyplot to create visualizations. I was also able to costumize this visualizations to make them easier to read and tell the real storie the data is telling us. Laslty, I was also able to build upon previous python and pandas knowledge to calculate means, group dataframes,etc. With this experience, it is now easiero to understand the value libraries like pandas or numpy bring to a data analyst.

## Results

There were 3 types of cities, Rural, Suburban and Urban. To make the analysis easier and the data more manegable, we can group all the citites based on their type and see how they behave as a group. To give a general idea of how the cities behave, I first created a bubble chart.

![fig1](https://user-images.githubusercontent.com/95836718/151262135-700ef8f4-6694-40fb-bd30-910619d95578.png)

**Comment:** The size of the dots corresponds with the average ammount of drivers in each city

We can easily see how each type of city groups and performs relatively the same, so we did good in decided to group the data by city type. We can see how Urban cities have a cheaper fare and a grater number of rides compared with suburban and rural city types.

There is an obvious question by looking at this graph, what type of city contributes more in terms of fare? Some might say that rural might be the one because of it has the highest fares, but also urban might be the one that contributes more because of its ride ammount.

![Fig5](https://user-images.githubusercontent.com/95836718/151262953-27547367-76b5-4584-b798-b06939eca8e7.png)

Looking at this pie chart, it is clear to see that Urban cities contribute a lot more than rural or suburban types. This will also be the case in terms of ammount of drivers and ride share.

![Fig6](https://user-images.githubusercontent.com/95836718/151263339-70b87b28-b8c2-4aaa-b074-c5901a8397f8.png)

![Fig7](https://user-images.githubusercontent.com/95836718/151263351-85664e49-1ac1-4870-b8fd-6b91996cb846.png)

This outcomes are expected, because it is obvious that Urban cities have more population density and need of transportation than a rural or suburban city. It is also easier to use PyBer at an urban city because there are more drivers available.

It would be more helpful if we could look on performance based on time, instead of as a whole, to see if we can identify trends and value each data individually.

![PyBer_fare_summary](https://user-images.githubusercontent.com/95836718/151263635-018496e8-af08-4cdd-b63d-cd9779aa1367.png)

In this graph we see the expected diferences in the ammount of fares each city has, we see how each line bhaves somewhat equally.

## Summary
- Even that it is expected to see Rural cities underperforming comparing to other city types, there still some other factors that could improve the apps performance in this type of cities. First would be the fare, we see the average price of the rural citites, and it is abusive to be charging 35 to 45 dollars in some cities. We do not want to rush things and implement this right away, we need more data to determine if there is a considerable ammount of population to even consider reducing the fares. 
- To improve the suburban cities performance, we might need to create a promotion that mantains reasonable fares and lets you travle to urban cities. This will make the app more atractive to people that need to go to work to the urban cities. More data needs to be adressed, like average income, to set a reasonable fare for people to consider two trips a day from their house and from their work.
- There also needs to be an increase in driver disponibility in suburban cities. Taking into account that we would focuse more on workers going to their jobs, puntuality needs to be on point. Making more drivers available in this areas will help people find rides more easily and arrive to their jobs on time. We do not need a lot of drivers all the time in suburban areas, we might encourage nearby urban cities drivers to start their day in a suburban city and take trips back to the city in order to still fulfill the ride demand of the high cities.
