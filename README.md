# Airbnb Seattle Project (Udacity - Data Scientist Nanodegree Program)
## by Data Camp 442


## Project Overview

Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. 
As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.

In this work we will analyse the Airbnb Seattle dataset of 2016.

## Libraries
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- os
- PIL
- wordcloud

## Content
#### listings.csv:
dataset that contains listings, including full descriptions and average review score

#### reviews.csv:
dataset that contains reviews, including unique id for each reviewer and detailed comments

#### calendar.csv:
dataset that contains the calendar, including listing id and the price and availability for that day

#### Exploration_Airbnb_datacamp442.ipynb:
Jupyter Notebook used to prepare the analysis

#### seattle_skyline.png:
picture of Seattle's silhouette for word cloud

## Summary of the results:
#### Do female hosts perform better than men when it comes to communication?
- In the majority of listed accommodations, the hosts are female with a 48.1% share and 40.8% are male. The next largest group is made up of couples with almost 10%, while professional companies form the clear minority with only 1% of the listed accommodations.
- On average, a host scores 9.82 points in the communication rating.
- Surprisingly, the female hosts actually score fewer points on average than the male ones. The couples clearly emerge as winners; they achieve above-average values.

#### Do female hosts respond to queries faster than other groups?
- If you respond within an hour you will usually receive very good communication values.
- Only the male hosts received slightly worse values ​​than women, couples and companies in almost all categories.
- However, if the host takes several days to respond, you will get very bad reviews. Women in particular do very poorly here.

#### Do female hosts pay more attention to cleanliness?
- In fact, on average, female hosts achieve a higher score in the cleanliness index than male hosts. While women are slightly above the general average cleanliness rating with 9.58 points, men are significantly lower with 9.50 points. The absolute leaders in the cleanliness category with a dream rating of 9.90 points are companies.

#### Are charging cleaning fees an indication of clean accommodation?
- If you  compare the fees and types of hosts, you can see that accommodations without a cleaning fee perform significantly worse, especially with male hosts, than if a fee is charged. The only exception are couples: They do better in the lower segment of cleaning fees than in the higher areas.
Cleanliness is rated best by professional companies.

#### What features have the most impact on the listings price?
- Four neighborhoods, namely Magnolia, Queen Anne, Downtown and Cascade, achieve above-average prices. The lowest prices can be found in Delridge.
  
- Internet, heating and a kitchen are “must haves” that hardly any guest has to go without. I find it surprising that more than 25% of all accommodations do not have a TV. Smokers have a hard time on Airbnb. Smoking is only allowed in very few accommodations. Exclusive features such as a pool, a hot tub, or the presence of a doorman are also rarely found.
  
- Basically, having your own apartment for yourself or even a whole house influences the price, this is not very surprising.
  
- Further up, there are exclusive features, such as a fireplace. But there are also things that the host itself can influence that obviously affect the price, namely a response time within a few hours and a strict cancellation policy.
  
- A downside of this method is that it doesn’t provide any information about the direction of the relationship between the feature and the target.
- If you compare the features host respose time and cancellation policy with the average price, the accommodations with a strict policy achieve a higher price on average, but if you allow several hours to answer a request, this is an indication of a lower priced accommodation. Both features seem to be relevant to the price assessment, but in different directions.

## Medium blog post


## Acknowledgements
I would like to thank Kaggle and Airbnb for providing the dataset, as well as Udacity for the support.

## References
https://seaborn.pydata.org/generated/seaborn.FacetGrid.html

https://github.com/mwaskom/seaborn/issues/1853

https://stackoverflow.com/questions/55104819/display-count-on-top-of-seaborn-barplot

https://stackoverflow.com/questions/51891370/draw-a-line-at-specific-position-annotate-a-facetgrid-in-seaborn

https://forecastegy.com/posts/feature-importance-in-random-forests/

