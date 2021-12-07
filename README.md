# Seattle-Airbnb

My Medium post on this project is here. (https://medium.com/@kitozuka/want-to-run-a-vacation-rental-understanding-airbnb-rent-prices-in-seattle-d64dc15b8e28)

## Installation
 - folium: I used folium package to create interactive maps that contain marker plots and choropleth plots. Other than this, I used libraries from Anaconda the distribution.

## Project Motivation
To understand the factors of determining rent price on Airbnb listings, I use "Kaggle Seattle Airbnb Open Data"(https://www.kaggle.com/airbnb/seattle), which includes listings data in 2016. I will look into this by exploring the following three sub-questions:
 1. When are the busier days or seasons in Seattle? What are the average prices then?
 2. What is the number of listings and the median price over night in the neighborhood?
 3. Which factors have a strong correlation with the price of listings?

## File Description
Those files below are the major ones for running the project.
 - Seattle AirBnB_2.ipynb: This ipynb file is the main Jupyter notebook I made analysis. This contains codes for geospatial maps and some statistical models. 
 - ScatterListings.html: This html file includes geospatial scatter plot of Airbnb listings, colored by rent prices with pupup lables.
 - med_price.html: This html file includes the median rent prices with popup labels by neighborhood in Seattle
 
## Technical Details
Although I created some interactive maps using folium, the file sizes are too to show on github. To view the results fully, you can downloead the html files (ScatterListings.html, med_price.html). I also run some machine learning models to predict rent prices. I mainly tried Random Forest + GridsearchCv to find the best model, but I did not try ensemble models with multiple algorithms. However, I got R-squared of around 62%.

## Acknowledgement
I wrote this blog as a project for Udacity Data Scientist Nanodegree Program. I appreciate Udacity to give me this opportunity to hone my skill in analyzing and presenting real-world dataset. I also want to thank peer learners, especially Adnan Shaikh for their medium post (https://medium.com/@kaddu4u/understanding-the-rental-prices-of-airbnb-in-seattle-29a0427889e9) that helped me get a sense of the project.
