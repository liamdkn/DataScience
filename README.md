# Data Science & Machine Learing Portfolio

## Introduction
Welcome to my Data Science and Machine Learing Portfolio!<br>
My name is Liam Durkan, and I am on track to graduate from South East Technological University with a BSc(Honours) in Software Development.<br>

### Contact Information
Connect with me on [LinkedIn](https://www.linkedin.com/in/liamdurkan/)<br> 
Check out my [GitHub](https://www.github.com/liamdkn/)<br> 
Email: liamdurkan24@icloud.com


## Portfolio Contents
1. [Introduction](#introduction)
2. [Contact Information](#contact-information)
3. [Technical Skills](#technical-skills)
4. [Education](#education)
5. [Professional Background](#professional-background)
6. [Previous Projects](#previous-projects)
7. [Intrests](#intrests)
8. [Skills](#skills)
9. [Project 1: RTB Average Monthly Rent Report](#project-1-rtb-average-monthly-rent-report)
10. [Project 2](#project-2)
11. [Project 3](#project-3)

---
## About Me

### Technical Skills
I have experience in the following languages: <br> 
- Proficient in Java
- C++ 
- C#
- Python
- HTML
- CSS
- React
- Assembly Language
- Bash

Experience in the following softwares: <br>
- Microsoft 
    - Azure 
    - Access
    - Excel, Powerpoint, Word
    - VS Code & Visual Studio
- GitHub
- Postman
- Arduino Integrated Enviroment
- Eclipse
- Plesk Web Host 
- Cisco Packet Tracer

---
### Education

- Currently undergoing a BSc(Honours) in Software Development  - South East Technological University
- Robotics & Intelligent Devices BSc - Maynooth University (First Year)
---
### Professional Background
In 2023, I completed an internship with NetWatch Ireland.<br>
This internship was an invaluable learning experience where I used technologies such as; 
- Azure
- GraphQl 
- C#
- ASPNET.Core 
- MySql 
- Postman

---
### Previous Projects
Throught my years of study, I have completed many projects that are linked below;

- Music Library & Playlist Streaming Application - SETU
- Line-Following Robot Using Arduino - Maynooth University
- Blood Bank Management System - Carlow IT
- Invoice Manager - Carlow IT 

---
### Intrests
Within software development there are a few areas I am specificaly intreseted in.<br>
- Machine learning, as popular as it is now, has always been a facination for me. I am considering furthering my edecation once I graduate and complete a masters in Artifical Intelligence. 

---
### Skills
I will dicuss my technical skills here 

---
### Volunteer Work

Throughout my three years studying software development I have acquired many skills in building websites. I decided to put them to use and volunteer to help with my local hurling club’s website for my village.<br> 
- The website is powered by clubforce which is an all-in-one platform that hosts the website and allows us to host a weekly lottery. The funds generated from this lottery are vital for the day-to-day operations of the hurling club offering locals a simple way to raise funds. 
- The website acts as a digital bulletin for all news relating to the hurling club. It delivers club notices, details on events, fixtures and results, and other club announcements. My main role with the website is on the bulletin when a match report comes in from the club. <br><br>

My experience in helping manage the hurling club website has shown me the impact that technology can have on a community and is an achievement that I am proud to be a part of in my village.<br><br>
Check out the website [here!](https://kilmessangaa.clubforce.com)



___


## Data Science & Machine Learning Projects
### Project 1: RTB Average Monthly Rent Report

#### Project Description
In this project, I utilise data collected from the [Property Services Regulatory Authority](https://propertypriceregister.ie) and the [Central Statistics Office](https://data.cso.ie). Using this data I will analyse how income and population data has impacted the price of residental housing. 

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
---

### Project 2
#### Project Description
#### Project Goals
#### Data Sets
#### Tools and Technologies
#### Ethics
#### Regulations 
#### Outcome & Results

---

### Project 3
#### Project Description
#### Project Goals
#### Data Sets
#### Tools and Technologies
#### Ethics
#### Regulations 
#### Outcome & Results