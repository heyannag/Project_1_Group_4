## Used Nissan Car Listings Analysis

# Project 1 - Group IV
Michael Cherkassky
Catie Clark
Garet Douglass
Anna Givens
John Patten

## Objective 
# I. Research Data from True Car Listing and analyze the information provided to determine the following;
  - Vehicle availability in TN and US Market
  - Vehicles available by Model Year
  - Model Year and Mileage Impact on Price
  - Model Year and Resale Price
  - Residual Value by Model and Model Year

This data was obtained on https://www.kaggle.com/jpayne/852k-used-car-listings#true_car_listings.csv and contains the following limitations:

    - We limited the data to only look at used cars made by Nissan (original dataset includes over 50 makes)
    - Model Years between 1997-2017
    - Listings that were live on September 24, 2017

Data included: year, make, model, price, VIN, city, state


# II. After initial research, collaborate on findings and comprise data to an overall theme
Educated Recommendation - What used Nissan vehicle do we recommend for our hypothetical customer?

1. Problem:
Shopping for a used vehicle can be difficult. You want to make the best investment, but it's hard to know if you are getting the best price/value or if there are other vehicles listed that best suit your needs.  

2. Goal:
What used Nissan car do we recommend user should buy within their ** qualifiers: budget, mileage, and geographical location of listing. ** (need to define)
Is the asking price for this particular car reasonable given the information provided in the dataset. 
What are other vehicles could we recommend? (Slightly overbudget, higher mileage, outside geographic location.)

This data was obtained on https://www.kaggle.com/jpayne/852k-used-car-listings#true_car_listings.csv and contains the following limitations:

    - Only used cars made by Nissan
    - Model years between 1997-2017
    - Listings that were live on September 24, 2017

Data included: year, make, model, price, VIN, city, state

## Vehicle availability in TN and surrounding area & general trends

# Findings

- United States: 
    - southeast/southwest: Altima most available (only 1 state did not have Altima as highest number of listings)
    - midwest (plains): there are more states with Rogue as highest number of listings than Altima as the highest
    - Alaska: only state with most Pathfinder listings
    - Nevada/Hawaii: only two states with most Versa listings
    
- Nissan: 66,250
    - when grouped by state --> 59 (need to consolidate duplicates)
    - Models in Tennessee: 'Versa', 'Altima', 'Sentra', 'Rogue', 'Maxima', 'Murano','Titan', 'Quest', 'Pathfinder', 'Xterra', 'NV', 'Armada', '370Z','GT-R'
    

![USA Availability](PNG_Files/1_availability_US.png)

- Tennessee: 1976 listings, Altima is the most available

![TN Availability](PNG_Files/1_availability_tennessee.png)


## Vehicles available by Model Year in Overall Market 

![Model by Model Year](PNG_Files/2_Model_by_Model_Year.png)
![Model Year by Model](PNG_Files/2_MY_by_Model.png)
![Total Listsings by Model Year](PNG_Files/2_Total_Vehicles_by_Model_Year_bar.png)
![Total Listsings by Model Year(Scatter)](PNG_Files/2_Total_Vehicles_by_Model_Year.png)

## Model Year and Mileage impact on price

![Mileage vs Resale Price](PNG_Files/3_Mileage_Resale_Price.png)
![Model Year vs Resale Price](PNG_Files/3_Model_Year_Resale_Price.png)

## Model Year and Resale Price

![Resale Price Distribution by Model](PNG_Files/4_Price_Distribution_Model.png)

# Findings
- The average price of a used Nissan is $16,602 (USD)
- When sorting by the highest price, there are some listings of non-luxury or sport vehicles (Altima, Sentra) that are priced extremely high and seem inaccurate (99,999).  This may be an attempt by the listing party to appear at the top of the list when sorted by price. 
- GT-Rs have the highest entry price of any used Nissan listing in this dataset. 
- The lower quartile of price(USD) is 1,500 
  - 25% $11,950 
  - 50% $15,000 
  - 75% $19,990 
  - and upper quartile $121,495

![Resale Price Distribution by Model Year](PNG_Files/4_Price_Distribution_Model_Year.png)

## Residual Value by Model and Model Year

![Depreceiation by Model](PNG_Files/5_Depreceiation_by_Model.png)

![Depreceiation in 5 Years](PNG_Files/5_Depreciation_by_Genesis_Year.png)

# Findings:

- Residual value is related to the lifespan of the *model*.
- Possible explanation: novelty vs. substitution.
- Best car to buy this year for resale next year?
    - New-ish year of the newest model
    - Older year of an older model
