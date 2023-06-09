# WSDD
WSDD: Wheat Supply and Demand Benchmark Dataset 

1) Demand dataset: Considered different related features such as 
•	income

•	population 

•	wheat price 

•	price

Demand data and agricultural data have been collected from extracted from:

•	The US Department of Agriculture USDA (Agriculture data)

•	The Foreign Agricultural Service (Agriculture data)

•	The Food and Agriculture Organization of the United Nations. (Agriculture data)

•	World Bank Open data. (Income And Population)

•	FRED economic Data (Prices)

The Demand data set contains 33 features with 265 cases, the cases represent data for each month for 20 years (2000-2020), and the data collected as a time series represented by the date of the first of each month. The countries represented as features “12 Countries”
(China, India, Russia, US, Pakistan, Turkey, Egypt, Iran, the UK, and Europe "Malta, Italy, and Romania")
For example, income was collected in 12 columns, for each country one column for the income and 12 columns for population, however, for the prices of wheat and the alternatives (oat, corn, and rice) it was world price so for each crop one column that represents the price.
This Data set can be used for wheat and it can be used from different perspectives based on the target, such as predicting the price or demand and so on for 12 countries around the world, which are the top consumer countries of wheat.


2) Supply data set: 3 types of features were considered for the wheat and the alternatives (oat, corn, and rice).

•	weather data
•	area harvested 
•	producer price 

In terms of data collection

•	weather data was requested from Arabia Weather, it checked the planting areas in the 15 countries, and in coordination, with them, 56 weather stations were selected and the data was collected from each station separately. 

•	The rest of the data as data related to agriculture such as the area harvested, and the producer price of the wheat and the alternatives (oat, corn, and rice) was extracted from The Food and Agriculture Organization of the United Nations.

The supply data set contains 56 features with 331 cases, the cases represented by country, and each country have 22 rows that represent the years from 2000 - 2021, so the data was collected by year. The features collected were the producer price and harvested area for the wheat and the alternatives (oat, corn, and rice), and the weather data has 7 features it was collected for 6 months, and for each month 7 columns so there are 42 columns for the weather. the 6 months taken into consideration represent the months from the planting month to harvesting month.

This data set can be used for wheat and alternative corps (oat, corn, and rice), based and can be used to predict the supply of wheat for 15 countries around the world, which are the top producer countries of wheat.
Files:
1) Demand Dataset
2) Supply Dataset
