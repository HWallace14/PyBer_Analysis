# PyBer_Analysis

## Overview

### Purpose

The purpose of this analysis is to provide our boss, V. Isualize, with a visual that quickly shows the total weekly fares for the city types Urban, Suburban and Rural over a four-month period. We are then to look at the data and provide an analysis of the data to our boss and the other decision-makers at our company, PyBer.

## Results

We took ride data involving different cities and their fares and pulled the followinf data from them: total drivers, total rides, total fares. This allowed us to figure out the average fare per ride and the average fare per driver, which we put into a dataframe as shown below:

<img width="448" alt="rides_by_type" src="https://user-images.githubusercontent.com/105998378/178126292-7731aac5-0d61-43ac-8738-83f3af4de152.png">

Following that we took the original dataframe where the above data was pulled from and grabbed a four-month period of data regarding fares, dates and types of cities in a pivot table. We resampled that data grouped it by week so that we could get the total fare amounts per week by city type (shown below).

<img width="192" alt="Weekly Fares" src="https://user-images.githubusercontent.com/105998378/178126377-e58e96bd-4c55-474e-8e92-05bad160d060.png">

The above information was fed into a graph, from which we will draw our conclusions. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/105998378/178126433-aeea3604-d0cf-427c-bcaa-8597d7cbe942.png)

## Summary

We can see from the graphs that urban areas should be our main area of focus for PyBer. Despite their lower average fares they have many more rides and generate the most revenue. The suburban market is a fairly distant second, with the rural market trailing far behind. Generally the rule seems to be that the farther you get from a city center the less likely you are to use PyBer.

My recommended course of action is to allocate more resources toward city-based advertisement and support, with a secondary goal of securing the suburbs. The rural areas don't generate enough revenue to warrant focusing on at this time and should be focused on only if we've fully secured the maximum amount of market share for the other two types of cities that we possibly can. 
