# Smart-Foodie

I use Google Maps several times a day before coronavirus spreading, to check when is the good time to drive home after class for avoiding traffic, to discover local restaurants that I haven’t try, beautiful or fun places to walk and so on. I find this application is so useful. After frequently using Google Maps. I notice there are a few aspects it could improve and bring more convenience for users. I personally enjoy trying new food. Yes, this is why I named this web application “Smart Foodie”. This application has been set to search nearby restaurants from your input address, but you can always change the setting to search other types of locations, like hotels, book stores, banks, shopping malls, and so on by just changing one line of code.

```
Here are some aspects I noticed:

    -- So far, google map unable to display nearby locations to a searched location (start point) at the same time. Users have to change        the pin to each destination location to check drive time.  
    -- And it could not shows the details of this destination (ie: Customer Rating, Number of reviews, Price level, etc) at the same            time.
    -- The current google map only allows users to filter the results by select Customer Rating between 3.5, 4.0, and 4.5.
    -- The user is unable to filter the results by input or select a number of Total reviews.
```

## Introduction

Smart Foodie V1 is been develop as a single page web application. It connects with Google place API and Google Matrix API to get 60 nearby searches results based on what user input at start point box and calculate and return distance and drive time from the time user use this application.
Application filter the display results when user unclicks in Price range form or and input in Review or/and Rate. Then the user is able to see results pins and a result table. 
```
Click each result pin or result table will see the details of each location including:

    - Restaurant name with a clickable link to the original google page of this restaurant
    - Drive time from now( if google API provides)
    - Customer rating in stars and in a double number
    - Number of customer reviews this restaurant has
    - Telephone number
    - Restaurant address
    - Restaurant website
```
  

