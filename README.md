# NYC-Airbnb

#### Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalised way of experiencing the world.
#### Whether it is down to be a more wallet-friendly option, or an opportunity to experience the city like a local, staying at an Airbnb in New York City has become an increasingly popular option for people visiting the city.

## Motivation:
#### Do features of a listing affect the price? Can we make predictions about price?

## Analytical Process:
#### Cleaning & Consisteny Checks
#### Exploring Relationsips
#### Geographical Visualisations
#### Supervised Machine Learning
#### Unsupervised Machine Learning
#### Sourcing & Analysing Time Series Data

## Libraries:
#### Quandl
#### Pandas
#### Numpy 
#### Seaborn
#### Matplotlib
#### Statsmodels API 
#### Warnings

## Exploratory Analysis: Price Across Each Borough
#### The Box and Whisker plot below shows the comparison of price distribution for each borough. 
<img width="525" alt="BW Price" src="https://user-images.githubusercontent.com/71847867/129921266-8fa2ed66-ce88-4912-9012-b1c06b837031.png">

#### The histogram to the right depicts the price distribution per night for all listings under $400 (excludied the outliers).
<img width="544" alt="Hist  Price Distribution" src="https://user-images.githubusercontent.com/71847867/129921485-638cf954-e0bd-4551-aa03-76999591bdd0.png">

## Unsupervised Machine Learning
#### According to the Elbow Curve, there is a large jump between 2 and 4 on the x-axis, then straightens out, thus the optimal count for clusters is 3.
### Availabilty
<img width="642" alt="Cluster  Avail" src="https://user-images.githubusercontent.com/71847867/129922318-1e71ed95-23df-4cd1-9a32-d1bd07342d3b.png">

### Host Listings
<img width="644" alt="Cluster  Listings" src="https://user-images.githubusercontent.com/71847867/129922335-ca257f5e-67ed-437c-9e25-5e7410258c8d.png">

### Minimum Nights
<img width="650" alt="Cluster  Min Nights" src="https://user-images.githubusercontent.com/71847867/129922340-5417bb45-3d73-4306-9011-bc9cb9310b28.png">

### Reviews per Month
<img width="630" alt="Cluster  Reviews Month" src="https://user-images.githubusercontent.com/71847867/129922343-40737548-8379-4417-9f1d-cda33db524b0.png">

### Total Number of Reviews
<img width="668" alt="Cluster  Total Reviews" src="https://user-images.githubusercontent.com/71847867/129922352-ba8ebf9a-2e8b-42a6-bfd6-dde9c7c8b81d.png">

## Conclusion
#### Through this analysis, we can better predict the price according to variables, such as: availability, host listings, minimum nights, reviews per month, total number of reviews. 
#### Number of Reviews: The average price per night, the more reviews. Followed by least expensive, then most expensive.
#### Reviews per Month: Excluding the outliers, the least expensive booking has the highest amount of reviews per month. Followed by average price, then most expensive.
#### Minimum Nights: The least expensive and average price have the higher amount of minimum nights.
#### Availability: Average price has the highest availability, least expensive has the least available.
#### Host Listings: Higher host listings for bookings with average price.


## Acknowledgements: 
#### Airbnb public dataset: the original source can be found on this website:  https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data
#### Neighborhood Tabulation Areas (NTA) public dataset: the original source can be found on this website: https://data.cityofnewyork.us/City-Government/Neighborhood-Tabulation-Areas-NTA-/cpf4-rkhq
#### 

## Link to Tableau Public: 
#### https://public.tableau.com/views/NYCAirbnb_16280850718870/NYCAirbnb?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link
