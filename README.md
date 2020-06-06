# Los-Angeles-Airbnb-Analysis

## Files
Dataset: listing.csv  (available for download at Inside Airbnb: http://data.insideairbnb.com/united-states/ca/los-angeles/2020-05-08/data/listings.csv.gz)

Code: LA Airbnb Analysis.ipynb

Analysis on Medium: https://medium.com/@xinyuzou_34243/the-houses-that-are-still-booked-during-the-pandemic-a-case-study-about-the-airbnb-listings-in-5adb5d2a9da2

## Package Needed to be Installed (Python 3)
numpy

matplotlib

locale

scipy

sklearn


## Motivation
The target is to learn about the factors that influence a listing's occupancy rate, especially during this time of pandemic. The result will provide insights about what to do to make listings have more days of reservations to the current and prospect hosts.

## Findings
The listings that the occupancy rate beats at least half of all listings in LA area tend to have higher host acceptance rate, more reviews received, more privacy (whole apt instead of shared room, for instance). When predicting the availability, the number of reviews received, price and extra fees(security deposit, cleaning fee, etc.) are important components considered by random forest classifier, which obtains a 64% accuracy on the test dataset.
