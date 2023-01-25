# Analysis_and_Visualization
Visualization of moving annual rent of Australia Suburbs
5. How many columns the dataset has? - 8 columns
6. How many rows the dataset has? 89475

7. Complete the following table about the dataset columns
| Field Name   | Description | Pandas Data Type | Data Scale | Min Value | Max Value | Unique Values | Missing Value Count |    
| Property_Type| The 7 types of properties | Object | ---- | ---- | ---- | 7 | 0 |  
| Quarter | Particular month of ending qurater of the year | Object | ---- | ---- | ---- | 4 | 0 |
| Year | The year of the quarter | Object | ---- | ---- | ---- | 22 | 0 |
| Period | Combination of quarter and month | Object | ---- | ---- | ---- | 85 | 0 |
| Region | Australian Region | Object | ---- | ---- | ---- | 13 | 0 |
| Suburb | Particular area in a region  | Object | ---- | ---- | ---- | 146 | 0 |
| Count | The number of houses | Float | Numerical |10| 17533 | 3034 | 3381 |
| Median | The median price | Float | Numerical | 60 | 1875 | 803 | 3381 |

10. Write a statistical summary for the dataset. What have you found? 
The dataset contains information on the property market in Victoria, Australia, including the property type, quarter, year, period, region, suburb, count, and median value. It has information from 2000 to 2021. By looking at the data, we can see that the property market has evolved over time and there are variations in the count and median value depending on the region and suburb. The dataset has information on various types of properties such as 1 bedroom flat, 2 bedroom flat, 3 bedroom flat, etc and also on all properties. Some of the regions have more data than others.
The heat map depicts there is a positive corelation among all varibale and the there a 0.61 correlation coefficient among median price and year that shows the median price has been increaing with year. The scatter give a very important insight on count and the median price, as the median increases upto 500 the count of house also increased but there in is a decline after the median price of 500 that implies more people are interested in renting out properties within the price range of 0-500 across all regions.
histogram plotted based on median price and property type shows a slight right skewness among all property. The right skewed histogram for median and property types gives an insight that the median values are mostly concentrated on the lower end of the scale as mentioned abobe 0-500 , with a few outliers on the higher end. This suggests that there is a wide range of prices for different types of properties, but most of them fall within a relatively narrow range. The shape of the histogram also indicates that there are relatively few properties with very high median prices compared to those with lower prices. This could be due to a lack of high-end properties in the dataset, or it could indicate a general trend in the housing market towards more affordable properties.
