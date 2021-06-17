# Citi Bike Analysis - August 2019

## Overview 
The purpose of this exercise was to analyze Citi Bike Data from August of 2019 to evaluate ridership and demographic information to decern trends. The trends identified will ultimately be used for subsequent plans to expand the Citi Bike Program into Des Moines, Iowa. To conduct this analysis, we used Tableau and Jupyter Notebook. Citi Bike Data for August of 2019 can be found on the [Citi Bike website](https://s3.amazonaws.com/tripdata/index.html).


## Results
The below screenshots provide a commentary of our findings. To view the full interactive Tableau Story and commentary, please click [here](https://public.tableau.com/app/profile/chris.reinhardt/viz/creinz11-CitiBikeAnalysisAugust2019/NYCAug2019).

### Key Findings

* There were a total of 2.3 Million Rides with Citi Bikes in August 2019.
* The Majority of riders are subscribers, as opposed to "Pay per Ride" clients highlighting the recurring demand. Orange in the below image denotes Subscribers, and Blue denotes "Pay per Ride".

<img width="186" alt="Screen Shot 2021-06-16 at 8 49 37 PM" src="https://user-images.githubusercontent.com/80016496/122318972-8dfe0680-cee5-11eb-950a-de2e0dd57bbd.png">

* The most popular times for Citi Bike rides were between 7-9AM and 5-7PM consistent with the traditional work commute.

<img width="1002" alt="Screen Shot 2021-06-16 at 8 58 44 PM" src="https://user-images.githubusercontent.com/80016496/122319113-c9003a00-cee5-11eb-9fa1-a39bd34e2f6f.png">

* Typically, Citi Bike rides are short in nature averaging about five minutes per ride. We saw a simialr trend when stratifying trip duration by gender. Orange represents males, blue represents females, and red represents unknown in the second graph below

<img width="675" alt="Screen Shot 2021-06-16 at 9 00 14 PM" src="https://user-images.githubusercontent.com/80016496/122319240-f64ce800-cee5-11eb-8720-70b5e4adbb04.png">

<img width="562" alt="Screen Shot 2021-06-16 at 9 02 06 PM" src="https://user-images.githubusercontent.com/80016496/122319411-37dd9300-cee6-11eb-9aea-75afb9d76e07.png">

* Citi Bike usage is heavy during the hours discussed above consistent wiht commuting hours, but the below graph captures a general uptick in Citi Bike usage on weekends denoted by the deeper orange/red in the heat map below. When we compare genders vs. usage of Citi Bike for given weekdays we still see the persistence of peak usage hours, and higher rate of usage by males.

<img width="500" alt="Screen Shot 2021-06-16 at 9 04 51 PM" src="https://user-images.githubusercontent.com/80016496/122319746-a9b5dc80-cee6-11eb-913f-3cd07035e23c.png">

<img width="699" alt="Screen Shot 2021-06-16 at 9 06 35 PM" src="https://user-images.githubusercontent.com/80016496/122319884-e255b600-cee6-11eb-8950-dd3928c0de3b.png">

* Aside from our previously noted trend of more subscriber-based usage vs. "Pay per Ride", we also see that subscribers are overwhelmingly male per the below heatmap.

<img width="260" alt="Screen Shot 2021-06-16 at 9 08 17 PM" src="https://user-images.githubusercontent.com/80016496/122320019-247ef780-cee7-11eb-9df1-5d97b048a26d.png">

## Summary

Based on our analysis it is clear Citi Bike is an incredibly popular means of transportation on a recurring basis, particularly for morning and evening commuting hours. In addition to the general popularity Cit Bike has a loyal recurring client base emphasizing the perceived value of the programs subscriber model. As the group considers rolling Citi Bike out to Des Moines, the initial targeted marketing should focus on Citi Bike being a convenient way to commute to work within a City, and should generally target males. From an operational perspective, the program should manage bike downtime counter to the peak hours of usage and areas. For future analysis, we should consider not only peak usage months (traditionally summer) but also what Citi Bike utilization looks like in the winter months. In addition to season cyclicality, we should evaluate the most popular start/stop routes to evaluate any potential value in creating a surge pricing model for "Pay per Ride" clients. If we implement demand-driven pricing based on our findings, we may be able to stimulate further demand for the subscription model, and generate further recurring revenue in non-peak months.


