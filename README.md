# The State of AirBnB in Washington, D.C.

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

---

## Table of Contents
* Included in this repository:
    * [Data](./data)
    * [Data Dictionary](./code/01-data-dictionary)
    * [EDA](./code/02-eda-airbnb)
* [Intended Audience](Intended-Audience)
* [Data Description](Data-Description)
* [Methodology](Methodology)
* [Preliminary EDA](Preliminary-EDA)
* [Roadmap](Roadmap)
* [Resources](Resources)

---

## Intended Audience
The audiences that could find value in this project span across the travel business lifecycle: 

* An individual that enjoys traveling and is anywhere from a frequent user of AirBnB to someone that has never used it but is considering it for their next trip may find value in this. If there are less obvious factors that correlate with positive reviews, they may learn to look for those factors in their next AirBnB booking. It may also help them to be aware of prices and how an event in a destination might make their trip more or less expensive. 

* A host or someone considering becoming a host on the AirBnB platform may also benefit from knowing about factors that correlate with positive or negative reviews. It may also benefit a host to know just how much manipulating some of these factors could increase their listing price and therefore, potential profit.  

* AirBnB could benefit from this information by streamlining and improving the experience for users and hosts. By more quickly connecting hosts with factors they should incorporate or steer clear of, they can help make the hosts more effective, which will in turn improve experiences for users. Also, with information on predicted prices around events in the city, AirBnB can incorporate this into their marketing efforts, but increasing promotions on certain listings or certain AirBnB experiences related to those events.

---

## Data Description
The data I have was collected from AirBnB and compiled on InsideAirBnb.com. The information on AirBnB that I will be using to look at this problem are the listings, reviews, neighborhoods, and calendar of listings and prices for Washington, D.C., starting in January, 2009 up through September, 2019.

InsideAirbnb.com has information on AirBnB listings in cities around the globe, since very shortly after AirBnB's inception, which was August of 2008. 

The information on InsideAirBnB.com is updated monthly. This means that near the time of the Capstone presentations and Spotlight presentations, I will have access to an additional two months worth of data to use as a validation dataset. 

There are criticisms of AirBnB and its effect on poverty and the housing and rental industry in cities across the world. This is what prompted the data collection and analysis which makes up InsideAirbnb. I am only using their datasets, not their analysis as I hope to do some of this on my own. 

---

## Methodology
Outlines your proposed methods and models

---

## Preliminary EDA
Performs & summarizes preliminary EDA of your data

**Current**

**Next Steps for EDA**
There is a lot more to be done in terms of EDA and the different things I want to do with the data.



Defines the risks & assumptions of your data


---

## Roadmap 
Revises initial goals & success criteria, as needed

---

## Resources
* [InsideAirBnB](http://insideairbnb.com/get-the-data.html)
