# Home_Sales
** The first cell of the colab notebook was skipped and not used. Pyspark downloaded in the cell below it**


The goal of this challenge was the determine key metrics about home sales data using Spark and SparkSQL. Images for the answer to each question are in the "Images" folder in this repository.

Using the data, these questions were answered: 

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
-We can see that the average price of a four-bedroom house peaked in 2021, with a slight decrease in 2022. 


What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
-The average price of a three-bedroom, three-bathroom home fluctuated between the years of 2010 and 2017, the highest average price being in 2013. 

What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
- The average price of a three-bedroom, three-bathroom home with two floors and over 2,000 square feet peaked in 2012, but decreased again after that year.

What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
- The view rating for homes greater than or equal to $350,000 also varied, but seemed to increase with the price of the house. 

As can be seen in the jupyter notebook, the runtime of the cached data and the data saved with parquet both ran faster than using the original dataframe. Caching data and using parquet is especially helpful when analysing large datasets. 
