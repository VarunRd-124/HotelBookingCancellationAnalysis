# Hotel Booking Cancellation Analysis

## Overview of Analysis

- The Aim of this project is to analyse the hotel reservation cancellations, when and why they're taking place, in what regions and at what time of the year(in python).

- I've used the dataset available on kaggle (the same can be found in the files section of this repository).
 
- I started by importing the necessary libraries then i had a look at the the data from a high level (first 5 and last 5 rows). 

- After having an overview of the how the data looks, i dived into EDA and discovered the number of rows, and other statistical measures using describe and info() methods available in pandas.

- I've changed the data type of the column 'reservation status date' to datetime to fecilitate the analysis

- then i've looked at the unique values present in all the columns, Next step in EDA is a very important one i.e dealing with missing data

- I found that the column 'company' has a lot of missing data so chose to drop the column, even the column agent had a quite a lot of missing values so i dropped it too.

- Then i have removed the NA values present in the 'country' column as they were quite negligible.

- Then coming to the main part i.e analysis firstly we calculated the count of cancelled and not cancelled reservations, i found out that more than 37% of the reservations were cancelled which is a thing to worry about

- Then i've created a plot to find out the variation in cancelled and not cancelled reservations in different type of hotels(City hotels and resort hotels)

- Then after plotting i found that around 28% reservation in resort hotels were cancelled whereas around 42% of reservations were cancelled in city hotels.

- Higher cancellations in city hotels can be attributed to higher daily rates and maintanence costs as they're used regularly.

- Next I've plotted the daily average rates for hotels then found out that in january rates are quite high and it led to the highest number of cancellations in the same month compared to the other months in the year.

- Then moving on we found out that country-wise, portugal had the highest number of reservation cancellations.

## Suggestions

Some of the **Suggestions** which i could give to the hotels in order to reduce the number of cancellations are:

1) Cancellation Rates rice as the price does, in order to prevent cancellations of reservations hotels could work on their pricing stratergies and try to lower the ratee of hotels on some specific locations or they could also provide some discount for customers.
2) As the ratio of the cancellation and not cancellation of the reservations is higher in the city hotels than resort hotels, so the hotels should provide reasonable discounts on the room prices on holidays and weekends.
3) In the month of january hotels could start a marketing campaign as the rate of cancellations is the highest in this month.
4) As rate of cancellation in highest in portugal they can improve the quality of services in that region.

## Key Points to Note:

- Efficiency in generating revenue is affected by booking cancellation.

- Hotel reservation cancellations and the factors affecting them

- You can perform various actions and analysis on the dataset

- There are multiple categories with different values in the dataset.

- Around 37% of reservations are canceled, which is a major issue for the hotel.

- Cancellation ratio is higher for city hotel compared to resort hotel, possibly due to higher prices and maintenance issues.

- Analysis shows that when cancellations are highest, reservations are lower

- Hotels in Portugal should increase facilities.

- The average daily rate is influencing the cancellation rates.

- Significant impact on hotel earning


