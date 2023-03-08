# DataEngineeringPracticum-1

# Project Description: 
We collected the data from various sources related to energy consumptions, other macroeconomic and energy related details across various countries. Then we are going to analyse the trends of the consumption, spends and other factors across countries primarily focusing on the E-Mobility and present as a dashboard.
Data is collected from the website IEA (International Energy Agency);
Total 24 datasets are collected and out of all those we selected one particular dataset which is relevant to our project objective.

# Data Description:
In our dataset we have details of 4 different sectors :

Industries
Residential
Services
Transport

In our dataset we have data of different resources for each sector:

Energy
Emissions
Carbon Indicators
Energy Indicators

Overall we have made the data into 16 sheets i.e. resources data for each sector.

# Data Cleaning:
We have read the data of each sheet required into one separate variable. (16 variables :: 16 sheets)
Years are in columns , we changed them to a single column name year and all the years and their corresponding values to other column names values.
Then we found there are few missing values and dropped all the records with missing values. 
We created a dim table for countries by getting all the unique countries from all sheets and given code to them. 
Finally we saved these 16 variables with each data frame as csv files to make it input for the dashboard.

# Steps Performed in PowerBI: 
We loaded all the 16 datasets and country dim table csv into powerbi.
Used first row as header, converted the columns into correct data types as required.
For each sheet we made new measure i.e. the average value.
Plotted the data of all countries on map with bubble size based on average value. 
Added functionalities to filter the data by year, subsector/ product/ vehicle type as applicable for the dataset.
We can also find the min and max countries with corresponding values, sector and measures.

 











