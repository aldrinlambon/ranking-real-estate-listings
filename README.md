# Ranking Real Estate Listings

## Project Motivation
For this project, I want to create a model to rank property listings based on different characteristics and answer the following:
1. What are the most common characteristics of sold properties?
2. What are the factors that are highly affect a property's pricing?
3. How can we rank 'for sale' properties based on pricing and chrateristics?

## Data Source / Web Scraping
Due to the API limitations and data availability, I created a python application to scrape listing from [Zillow.com](https://www.zillow.com/). 

I will not provide code for my web scraper. But if you are interested in building one here's the [Repo by maksimKorzh](https://github.com/maksimKorzh/one-time-scrapers/tree/master/scrapers/zillow) that I used as the basis for my initial codes.

## Data Preparation

Based from the motivation and the questions we want to answer, I have selected the following variables for the analysis:

- Price: $ value of a property
- ListType: Sold or For Sale

Geographical variables:
- Street, State, City, Zipcode, Lat, Lon

Property variables:
- Beds, Baths, Area, Type, Year Built, Heating, Cooling, Parking, Lot, Price/Sqft, Full Bathrooms, 3/4 Bathrooms, 1/2 Bathrooms, 1/4 Bathrooms, Basement, Flooring, Total Interior Livable Area, Fireplace, Stories, Exterior Features, Roof, Tax Assessed Value