---
title: Lab brainstorm for final project
author: great-a
date: '2019-10-21'
slug: lab-brainstorm-for-final-project
categories: []
tags: []
description: ''
featured_image: ''
---
* At the beginning, we have several different preferences about the final project. 
Someone would like to detect the environment related data, and some people prefer the NBA shooting numbers, mobile app downloading, and success elements of the chest game. Finally, after a discussion and carefully datasets searching, we decide to work on the Boston Airbnb dataset.


* A link to data: https://www.kaggle.com/airbnb/boston
Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Boston, MA.

* The data will require much tidying for it to be useable. 
There are many columns for descriptions for the homes and hosts, which are long strings. These hold interesting information but some sort of natural language processing would be required to properly analyze the text found on these listings. We may be able to calculate the number of words in the strings and see if the length of these descriptions have interesting relationships with other variables. Another variable, ‘host_verifications’, takes a list of strings. For example, one listing has ['email', 'phone', 'facebook', 'reviews'] for the value of this variable. We will likely need to split this one column into many columns for each method of verification. 

* Our thoughts
How many features that affected the price? 
What kind of features affect the rating of host?
What are the busiest times of the year to visit Boston? By how much do prices spike?
Is there a general upward trend of both new Airbnb listings and total Airbnb visitors to Boston?


