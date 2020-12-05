# Capstone Project - The Battle of Neighborhoods: Istanbul's Restaurants

## Introduction

Istanbul is Turkey's most populous megacity. Since this city legs on both European and Asian sides, it has a mixed culture which can also be seen in its rich and various cuisines. People can find from the far east sushi to the Turkish kebab, and from the greek seafood to the west burger. There are a lot of food options for people. 

In this capstone project, we aim to guide people to find suitable restaurants for their taste. So, we are trying to answer the following questions: "Which district offers what type of restaurants?", "Where to eat sushi or seafood?", "Where offers the meat and spice?" or "Where offers the most various cuisines?". 

## Data

Following data sources will be used to fulfill this project target:

**District List**: Istanbul's districts list can be obtained using Wikipedia's [List of districts of Istanbul](https://en.wikipedia.org/wiki/List_of_districts_of_Istanbul) page. This list provides all 39 district names with other information like population, area, and density.

**Location Data**: Using [Geocoder](https://geocoder.readthedocs.io) API, will obtain the coordinates of the districts.

**Restaurant List**: Using the [Foursquare API](https://developer.foursquare.com), we will fetch detailed information about the restaurants in Istanbul. 

By using all three data sources, we will collect the restaurants in the districts. After that, we will provide the distribution and density of the restaurant types.