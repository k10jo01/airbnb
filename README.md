# An Analysis of AirBnB in Washington, D.C.

This repository is for the capstone project I am currently preparing as a Data Science Immersive student at General Assembly. 

---

## Executive Summary
Have you ever stayed in an AirBnB? Have you ever left a review? What prompted you to leave one? What factors about your stay made it into the review or influenced the review that you left? 

Are you an AirBnB host? Have you considered listing a room in your house or secondary property? What separates a good host from an 'okay' one? Or worse, a bad one? Do bad hosts continue to get bookings? Do previous reviews or events in the city affect the price of your listing? 

If you have used AirBnB, what prompted your need to book a place to stay? Were you traveling to a new city as a tourist simply to explore? Were you traveling for work and opted out of a traditional hotel? Were you visiting due to a special event (political, social, sport) happening in that city? Did price play a role in your decision?

If you have been a host on AirBnB, what is the story around the space you are hosting? Is it a spare bedroom in your home? Is it your apartment while you are out of town? Are you a landlord with space(s) in between tenants? Do you own many apartments/homes that are designated specifically for AirBnB? 

There is a lot to be explored around the AirBnB data of Washington, D.C. I'd like to incorporate several data science techniques to analyze the dataset that I have found: EDA (of course), Natural Language Processing, sentiment analysis, and time series predictions.  

---

## Problem Statement
What is the relationship between factors about an AirBnB (neighborhood, room type, availability) and review sentiment? What trends or patterns can be found in AirBnB data for Washington, D.C. over time? Does review sentiment have an impact on price of an AirBnB listing? Using past price and calendar information and sentiment analysis of reviews, can you predict the price of listings for future significant events in the District? For example, the price of AirBnB listings during the Women's March, Trump inauguration, Obama inauguration, Cherry Blossom festivals, Kavanaugh hearing, Rock n Roll and Marine Corp Marathons, Caps Stanley Cup games, Nats World Series games, conferences, etc. 

*I know this problem statement is quite broad and needs more specificity. I discuss how I will refine this in the Roadmap section below.*

Something about predicting price or listings after new regulation in DC? or when short term rental exacerbating housing shortages started? 

More focused questions:
-factors that differentiate good reviews and bad reviews (and by proxy, good hosts and bad hosts) - helpful for airbnb to market to their hosts or helpful for hosts or helpful for guests
-factors that influence daily renting price and/or predict daily renting price? - helpful for hosts, guests, airbnb
-is review sentiment a good predictor of price? 

---

## Table of Contents
* Included in this repository:
    * [Data Dictionary](./code/01-data-dictionary.ipynb)
    * [Data](./data)
    * [Code](./code)
* [Tools](Tools)
* [Data Description](Data-Description)
* [Methodology](Methodology)
    * ollecting and cleaning data
    align lifelines
    mapping
* [Conclusions](Conclusions)
* [Improvements & Next Steps](Improvements-&-Next-Steps)
* [Resources](Resources)

---

## Intended Audience
The audiences that could find value in this project span across the travel business lifecycle: 

* An individual that enjoys traveling and is anywhere from a frequent user of AirBnB to someone that has never used it but is considering it for their next trip may find value in this. If there are less obvious factors that correlate with positive reviews, they may learn to look for those factors in their next AirBnB booking. It may also help them to be aware of prices and how an event in a destination might make their trip more or less expensive. 

* A host or someone considering becoming a host on the AirBnB platform may also benefit from knowing about factors that correlate with positive or negative reviews. It may also benefit a host to know just how much manipulating some of these factors could increase their listing price and therefore, potential profit.  

* AirBnB could benefit from this information by streamlining and improving the experience for users and hosts. By more quickly connecting hosts with factors they should incorporate or steer clear of, they can help make the hosts more effective, which will in turn improve experiences for users. Also, with information on predicted prices around events in the city, AirBnB can incorporate this into their marketing efforts, but increasing promotions on certain listings or certain AirBnB experiences related to those events.

---

## Data Description
The data used in this project was collected from AirBnB and compiled on [InsideAirBnB](http://insideairbnb.com/get-the-data.html). The information made available by this site includes the listings, reviews, neighborhoods, and calendar of listings and prices for Washington, D.C., starting in January, 2009 up through September, 2019.

InsideAirbnb has information on AirBnB listings in cities around the globe, since very shortly after AirBnB's inception, which was August of 2008. The information on InsideAirBnB.com is updated by its moderators on an irregular basis. The data used in the project was collected from the AirBnB site in September 2019.

There are criticisms of AirBnB and its effect on poverty and the housing and rental industry in cities across the world. InsideAirBnB is the result of efforts to shine a light on the effect that AirBnB can have on a city's housing. Only the data from this site was used for this project, not their analysis.

---

## Additional Research
DC local government passed a law on October 31, 2019 place stricter regulations on short-term rentals. DC property owners are not permitted to rent out second homes on a short-term basis, and a host cannot rent out spare bedrooms or basement rooms of their primary residence for more than 90 days a year
https://www.washingtonpost.com/local/dc-politics/frustrated-airbnb-hosts-wait-for-dc-to-explain-new-regulations/2019/10/31/88293190-fa83-11e9-8190-6be4deb56e01_story.html

---

## Methodology





---


## Analytical Findings

Review volume (number of reviews left) has increased over time
inauguration palace??
$10 - 10,000

## presentation outline
- what question am i trying to answer (why is this interesting to me)
- why is this valuable? traveler, resident with extra space, airbnb or other platform/hotel 
- data - what data do i have, how was it obtained
- what did i do with the data? (model, analysis)
- findings, conclusions


---

## Resources
* All data from [InsideAirBnB](http://insideairbnb.com/get-the-data.html)
* Referenced methodology from following blogs:
    * https://towardsdatascience.com/digging-into-airbnb-data-reviews-sentiments-superhosts-and-prices-prediction-part1-6c80ccb26c6a
    * https://towardsdatascience.com/lets-make-a-map-using-geopandas-pandas-and-matplotlib-to-make-a-chloropleth-map-dddc31c1983d
    * https://stackoverflow.com/questions/38250710/how-to-split-data-into-3-sets-train-validation-and-test
    * https://towardsdatascience.com/exploring-machine-learning-for-airbnb-listings-in-toronto-efdbdeba2644
