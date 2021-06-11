# Final_Project California House Price Analysis

https://oxypetalumm.github.io/Final_Project/

The contributors to this project has been Elstan and Lina.

## Introduction and Inspiration

**Background information:**

Many of us probably have noticed, since last year, California housing prices have been rocketing. Meanwhile, home sales have been strong. According to California Association of Realtors (C.A.R)’s data, as of April 2021,

•	Year 2021 home sales increased 65% comparing to 2020,
•	Year-to-date until April home sales increased 26%,
•	April 2021 single-family-home sales totaled over 450thousand,
•	2021 median home price increased 34% comparing to 2020, and in April, median home price breaks $8000,000 (8million),
•	San Francisco Bay Area has the highest home sales increase. Its year-over-year home sales increased 101%

According to Gallup, 

•	53% of Americans believe now is a good time to buy a home
•	71% of Americans believe that home prices are going to increase over the next year in their local market.

As we looked at datasets on Kaggle while doing our research, my teammate and I became interested in analyzing California home prices. We wanted to find out what factors, in addition to mortgage rates and on market house inventor, are associated with home value. Furthermore, we were interested in using the dataset to practice making predictions by using scikit learn.
On Kaggle, we found this dataset, “California Housing Prices” (https://www.kaggle.com/harrywang/housing), which was based on the 1990 census record. It had been the only dataset we were able to find about California house price records. 

### Understanding the dataset:
1. Longitude: A measure of how far west a house is; a higher value is farther west
2. Latitude: A measure of how far north a house is; a higher value is farther north
3. Housing Median Age: Median age of a house within a block; a lower number is a newer building
4. Total Rooms: Total number of rooms within a block
5. Total Bedrooms: Total number of bedrooms within a block
6. Population: Total number of people residing within a block
7. Households: Total number of households, a group of people residing within a home unit, for a block
8. Median Income: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
9. Median House Value: Median house value for households within a block (measured in US Dollars)
10. Ocean Proximity: Location of the house with relation to ocean/sea

We use Tableau to create graphs to analyze house value’s correlations with ocean proximity, income, house age, population, households, total rooms, and total bedrooms.
Here’s the ocean proximity’s correlation with house value:

## Data Analysis
 
**Correlation Analysis:**
 
**House Prices vs. Ocean Proximity**
We plot the data into a Tableau map. We find that while the most expensive can be spotted in different areas, however, these most expensive houses concentrate near bay, followed by near ocean and then <1H ocean. The least expensive houses are in inland areas.
**House Prices vs. Income**
The trend line shows the R-squared value between house prices and income to be 0.47, meaning that income levels correlate to local house prices, yet the correlation is not very strong.
 
**CA House Prices vs. Population**
There are dense populations near bay, near ocean, and in inland areas. As we plot the data into a map, we see that densely populated areas near bay and near ocean appear to have a lot of expensive houses. However, the densely populated areas inland show house prices with least house prices. This finding correlates to our graph showing that these two attributes have a very weak R-squared value at 0.00016.
 
**CA House Prices vs. Households**
House prices and households seem to have slightly stronger correlation compared to house prices and population, according to our graph, with R-squared value at 0.0076, but the correlation is still very weak.
 
**CA House Prices vs. Total Rooms and CA House Prices vs. Total Bedrooms**
House prices and total rooms have an R-squared value at 0.019 while house prices and total bedrooms have an R-squared value at 0.0048. Both of these attributes don’t seem to have a strong correlation to house prices.
Conclusion:
We conclude that house prices have strong correlation with ocean proximity and have less strong correlation with income but have very weak correlations with factors such as population, households, and room numbers. We find that the most affordable houses are likely to be in inland areas.
 

## Model Of Machine Learning:
We use our data to test and train different machine learning models. These models include Linear Regression, Decision Tree, and Random Forest.
After comparing the different modules, we figure that Random Forest is much better than the Linear Regression and Decision Tree. We assume the Random Forest model is the best for this Machine Learning Model. 

