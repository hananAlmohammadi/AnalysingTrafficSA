
  
[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)![Misk Logo](https://i.ibb.co/KmXhJbm/Webp-net-resizeimage-1.png)

# DSI-Project 1
## Driving Licenses, Traffic Accidents and Casualties Analysis in Saudi Arabia
#### Hanan Almohammadi

## Problems statement

The project aims to states the traffic and accidents in Saudi Arabia for years from 1993 to 2017 by analysing two datasets; the first one is the driving licenses data set which describe the number of driving licenses issued in Saudi Arabia from 1993 to 2017 and the second one is the traffic accidents which describe the number of traffic accidents, number of dead and injured happened in Saudi Arabia for the years 2016 and 2017 to investigate the reasons behind it to participate in the process of decision making and support the right decision.

## Executive Summary
After investigating the traffic and accidents in Saudi Arabia, we found out which regions having the highest and lowest Driving Licenses based on years (1993–2017), the highest regions were Riyadh and Makkah. The lowers region over years were Northern region and Albaha. And the regions that have more Traffic Accidents each year more than the average of Saudi Arabia were Eastern Region, Makkah and Riyadh for the years 2016-2017.
## Data Dictionary
- **Traffic Accidents**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Traffic_Accidents|The year of the accidents or the casualties  | 
|region|object|Traffic_Accidents|The region where accidents or casualties happend | 
|indicator|object|Traffic_Accidents|the type of traffic status: Accidents or Casualties in specific region & year, it show also the type of casualties: dead or injured | 
|value|int|Traffic_Accidents|The number of Accidents and Casualties| 
|longitude|float|Traffic_Accidents|The geographic coordinate that specifies the position of a place on Earth, east-west   of the prime meridian| 
|latitude|float|Traffic_Accidents|The geographic coordinate that specifies the position of a place on Earth, north-south| 



- **Driving Licenses**

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Driving_Licenses|The year where the Driving Licenses were issued| 
|driving_licenses|int|Driving_Licenses|The number of driving licenses in specific region and specific year| 
|region|object|Driving_Licenses|The region where the Driving Licenses were issued | 
|longitude|float|Driving_Licenses|The geographic coordinate that specifies the position of a place on Earth, east-west of the prime meridian| 
|latitude|float|Driving_Licenses|The geographic coordinate that specifies the position of a place on Earth, north-south| 


## Conclusions and Recommendations

- 
Our finding of this study is that Riyadh and Makkah were the regions with highest number of the issued driving licences and they also had highest number of accidents and they were above the average of Saudi Arabia.

The highest region in all years in issuing driving licensees was Makkah region, and Northern region was the lowest region in issuing driving licensees.


In 2017, Makkah region has the highest accidents between all Saudi Arabia regions with more than 140,000 accidents, where in 2016 Riyadh had the highest accidents and in 2017 the numbers incredibly decreased. And Najran had the lowest number with less than 1500 accidents.

My recommendation is that more information need to be added about the accidents such as the time of accidents; which time has more accidents rate during vacations or working days, how the use of safety belt affects the number of injured vs. the number of dead?, what the cause of accidents? is it using phone while driving, the high speed, or crowded area,.. etc and the age of driver; is he/she licensed or not. And according to the cause a better actions can be taken in order to prevent these causes. Also the dataset should add the recent years, since Saudi Arabia allowed women to drive from 2018 to investigate how this decision affect the traffic in Saudi Arabia.
## Datasets

#### Provided Data

For this project, we have two provided datasets:

- [Traffic Accidents and Casualties by Region](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
- [Driving Licenses Issued By Administrative Area](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)

You can see the source for the accident data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/), and the source for the license data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/). 


## Article
- After invistgating the data, i write an article about driving licenses, traffic accidents and casualties analysis in Saudi Arabia,[see here for the article](https://hanan-almohammadi.medium.com/analysing-driving-licenses-traffic-accidents-and-casualties-in-saudi-arabia-8af320a6651e)
