# Currently Working on 


Dylan - Download and explore Zillow Home Value Index (ZHVI) to see what data we can grab for city = Seattle or zipcode = ?
Eunice - 
Greg -
Pablo -
Duygu - 




# To-Do List



Define which zipcodes
time period
gather income data (either from US Census Bureau or Bureau of Economic Analysis)
organize this todo list to fifgure out what we need to do chronologically 
update the readme and make it loook pretty



# goals
how prices have changed in the last 5 years for 1 / 2 /3 .. bedrooms houses for renting vs buying

main goal (price of houseing df ["sqft"]["bedrooms"]["bathrooms"]["zipcode"]["totalcost"]["monthly cost"])

how fast rent is increasing year to year
house equity appreciation year to year
percent of average income for each zipcode that someone would pay to rent vs buy
find zipcodes where house value is increasing the fastest
find zipcodes where rent price is increasing the slowest
what kinds of visualizations would be best?
    pie charts for percent of renters vs buyers in each neighborhood
    stacked bar charts to see percentage of income spent on housing
How the employmenmt data has chaged in this time (investing.com)?
why has the price changes? (# rooms, ammenities, renting in single unit home vs apartment complex or buying simgle unit home or condo/townhouse)




# API Sets to search 
https://datasetsearch.research.google.com/search?src=0&query=housing%20markets%20&docid=L2cvMTF0ZGh2ODYwZw%3D%3D
https://www.patpohler.com/big-list-real-estate-apis/
https://github.com/public-apis/public-apis?tab=readme-ov-file#geocoding
https://docs.google.com/document/d/1Xpt974luDTCZW-SM3AxInN4YDzF38qTOoC00la_j1So/edit



## Zillow Home Value Index (ZHVI)
city = Seattle
Metro = Seattle-Tacoma-Bellevue, WA
HOME VALUES
Zillow Home Value Index (ZHVI): A measure of the typical home value and market changes across a given region and housing type. It reflects the typical value for homes in the 35th to 65th percentile range. Available as a smoothed, seasonally adjusted measure and as a raw measure.

Zillow publishes top-tier ZHVI ($, typical value for homes within the 65th to 95th percentile range for a given region) and bottom-tier ZHVI ($, typical value for homes within the 5th to 35th percentile range for a given region).

Zillow also publishes ZHVI for all single-family residences ($, typical value for all single-family homes in a given region), for condo/coops ($), for all homes with 1, 2, 3, 4 and 5+ bedrooms ($), and the ZHVI per square foot ($, typical value of all homes per square foot calculated by taking the estimated home value for each home in a given region and dividing it by the home’s square footage).

Note: Starting with the January 2023 data release, and for all subsequent releases, the full ZHVI time series has been upgraded to harness the power of the neural Zestimate.

More information about what ZHVI is and how it’s calculated is available on this overview page(https://www.zillow.com/research/methodology-neural-zhvi-32128). Here’s a handy ZHVI User Guide for information about properly citing and making calculations with this metric.

## Kaggle US Cities Housing Market Data
Monthly Housing Market Data From 2012 to Present - Redfin
https://www.kaggle.com/datasets/vincentvaseghi/us-cities-housing-market-data?resource=download

## Rapidapi Realty Mole Property
(Deprecated) The Realty Mole real estate and property data API provides on-demand access to 140+ million property records, owner details, home value and rent estimates, comparable properties, active sale and rental listings, as well as aggregate real estate market data.
https://rapidapi.com/realtymole/api/realty-mole-property-api

## Rapidapi Rent Estimate
(API Deprecated) Get instant access to 140+ million real-time property rent estimates and comparable rental listings with the Realty Mole rental data API. Available nationwide in the US.
https://rapidapi.com/moneals/api/rent-estimate

