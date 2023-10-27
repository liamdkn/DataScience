### Project 1: RTB Average Monthly Rent Report

#### Project Description
In this project, I utilise data collected from the [Property Services Regulatory Authority](https://propertypriceregister.ie) and the [Central Statistics Office](https://data.cso.ie). Using this data I will analyse how income and population data has impacted the price of residental housing, and create future predictions of housing prices using income and population data. 

#### Project Goals
- Analyse & visualise historical housing sales.
    - Explore data on hosing sales to gain insight into trends or patters.
    - Create a narative of historical data, do prices only increase, or do they fluctuate? 
- Analyse the correlation between housing sales and population per county.
    - Investigate historical using statstical methods and data visualization to locate correlation/paterns.
- Analyse the correlation between hosing sales and income per county. 
    - Investigate historical using statstical methods and data visualization  to locate any trends or patterns
    - Using this data, predict how income levels in the future can influence house sale prices. 
- Build a machine learning model to predict how future income and population will affect housing prices. 
    - Using trends are patterns found, make preditictions for each county in Ireland to see how future population and Income levels will affect housing prices. 


#### Data Sets
1. The first, and largerst data set I am using is 'Property Price Register Ireland'. The raw file contains 476745 rows and 9 columns. Data included is the: 
    - Sale Date (2010 - 2021)
    - County
    - Sale Price
    - If Market Price
    - If Vat Excluded: 2nd hand houses do not include VAT on sale price. 
    - Property Description
    - Property Size
- Cleaning the data set included:
    - Dropping columns
    - Dropping rows with null value
    - Renaming columns 
    - Adding VAT to sale prices if it was excluded
    - Changing string values for new/old house to 1/0
- After cleaning the data there are 476,745 rows & 4 columns (Sale Date, County, Sale Price, Property Description)
2. The second data set I am using is population data from the Central Statistics Office. The raw file contains 2232 rows and 7 columns. Data included is: 
    - Census Year (2011 - 2022)
    - County and City
    - Marital Status
    - Sex
    - Population value
- Cleaning the dataset included:
    - Dropping columns
    - Dropping rows with null value
    - Removing rows that were just male or female data.
    - Removing rows that were total data for Ireland (not by county)
    - Cleaning and standardising county names. 
    - Grouping rows where year and county matches, summing the population in the process. 
- After cleaning the data there are 78 rows & 3 columns (Census Year, County, Population Value)
3. The third data set that I am using is household income data per county from the Central Statistics Office. The raw file contains 1944 rows & 6 columns. Data included is:
    - Year (2011 - 2022)
    - County 
    - Sex
    - Mean annual Income
    - Median annual Income 
-Cleaning the dataset included: 
    - Dropping columns
    - Dropping rows with null value
    - Removing male/female rows, only keeping sum of both sexes. 
    - Removing 'All counties' sumed values. 
- Afte cleaning the data there are 624 rows & 4 columns (Statistic Label, Year, County, Value)


#### Tools and Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebooks 

#### Ethics

#### Regulations 

#### Outcome & Results
- I will discuss the results including trends, correlations and relationships that are discovered throguht the process. 
- I will include data visulations that represent the trends and patterns that are found. 
- I will discuss corelations that are observed between house sales, population and income data.
- I will analyse how housing prices, income and population have evolved over time, and how this varies in different counties. 
- I will discuss results of the machine learning algorithims that predict future housing prices per county, based on future income and population predicitons. 