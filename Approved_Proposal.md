# Impact of COVID-19 on US Housing Market

## Introduction
Over the past decade, US home prices have experience steady growth. Location has been the chief criteria dictating the price and the potential buyer, but where is the location? After the pandemic, has the requirements for the property location changed. <br><br> 
Since March 2020, when COVID-19 virus has raged through the United States and around the world, this deadly virus had left a trail of numerous deaths and lingering effects of illnesses. To contain the spread of COVID-19, our way of life took a drastic turn. Physical presence at and long commute to work have been delegated to remote attendance in a part of the dwelling. A warm hug or a firm handshake have been replaced with six feet distance or a quick fist bump. Now, it seems the period of endemic is at hand. The luxury of working remotely is a possibility. Working from a far distance is not a barrier as long as internet infrastructure is in place. One could be in New York and be working forty hours a week in California. Once, our job dictates where one live which no longer is. <br><br>
The location of the house is an important issue to a home developer, home buyer or seller. The home developer will plan where the community will be. The creation of the community will be based on the demand of the buyer. Being able foresee the needs of the buyers will dictate the price of the property. The more in demand the location of the property is the better the asking price.<br><br>

## Research Question(s)
Has there been a change in house prices since COVID-19? <br>
Has there been a change in in-demand house location since COVID-19?<br>
Has there been a change in buyers' house buying criteria since COVID-19? <br><br>

## Dataset
<img src = 'https://github.com/tmarissa/marissa_DATA606/blob/main/Images/Data%20Source.PNG'/><br><br>

## Unit of Analysis
- US County is the unit of analysis for this research. This unit is represented by the Federal Information Processing Standard (FIPS) code which is 5 digit code that uniquely identifies counties in the United States.
- Population and land area dataset are joined with FIPS code to use to derive the density.
- FIPS code is also used to joined the density and real estate data which are used for visualization and machine learning.<br><br>

## Variables/Measures 
- Density of the area (counties) with price per square will be used to analyze between before COVID-19 (2016 to 2019) and after COVID-19 (2020 to 2021).
- There will be 26 variables used, Active Listing Count, Avg Listing Price, Avg Listing Price M/M, Avg Listing Price Y/Y, County, Date, Days on Market, Days on Market M/M, Days on Market Y/Y, Density, FIPS, Median List Price Per Sqft, Median Listing Price, Median Listing Sqft, New Listing Count, Pending Listing Count, Pending Ratio, Price Decrease Count, Price Decrease Count M/M, Price Decrease Count Y/Y, Price Increase Count, Price Increase Count M/M, Price Increase Count Y/Y, State, Total Listing Count.
- Average listing price (counties) will be used as the dependent variable and will be to analyze during 2016 to 2021.
- The independent variables will be as follows: Active Listing Count, Avg Listing Price, County, Date, Days on Market,  Density, FIPS, Median List Price Per Sqft, Median Listing Price, Median Listing Sqft, New Listing Count, Pending Listing Count, Pending Ratio, Price Decrease Count,  Price Increase Count,  State, Total Listing Count.
- These are the links to the description of the variables, [Variables A-N](https://github.com/tmarissa/marissa_DATA606/blob/main/Images/Data%20Variable%201.PNG) and [Variables O-Z](https://github.com/tmarissa/marissa_DATA606/blob/main/Images/Data%20Variable%202.PNG).<br><br>

## Techniques/Models 
- K-means will be the technique used in this project which works by selecting how many clusters, k, exist in the data. Each cluster will be represented by a centroid (average) of similar points with continuous features. Principal Component Analysis (PCA) will also be used because it help reducing the number of dimensions for the data set. This works by finding a lower dimension in the data such that the variance is maximized. <br><br> 

## Development/Applicaton of Machine Learning
- Lazy Predict will be used to analyze which machine learning model to be used. However, a correlational matrix will be graphed to show the relationship of each variable to the other. 

## Intended Outcomes
This research intends to understand how COVID-19 change the real estate market. This can help real estate developers and local government planners in designing future housing sites.
