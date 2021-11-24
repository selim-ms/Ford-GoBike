# <center> Communicate Data Findings <center> #

## <center> Ford GoBike Data Investigation <center> ##

### <center> By: Marwan Selim <center> ###

![alt text](GoBike.png "Ford GoBike")

## Project Overview ##

The Analysis is the final project of Udacity Advanced Data Analytics Nanodegree and it focuses on doing a complete analysis of an actual data set by Ford GoBike.

The project demonstrate the different phases of data analysis including:

1- Data Pulling/Gathering.

2- Preliminary Exploration.

3- Cleaning & Wrangling.

4- Exploratory Data Analysis Visualization.

5- Explanatory Data Visualisation.

## The Dataset: ##

[Ford GoBike](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv) is a data set of trips from February 2019 covering 183,412 entries with 16 initial variables.

#### The variables can be grouped into: ####

* Trip Duration (seconds)

* Start Station (ID, Name, Longitude & Latitude)

* End Station (ID, Name, Longitude & Latitude)

* Bike ID

* Start & End Times

* User Type, Gender, Birthyear & Whether they use bikeshare for all trips

#### The Variables are then cleaned & wrangleded to cover 174,668 entries with also 16 variables ####

* Trip Duration (seconds) & Distance (meters)
* Start Station (ID & Name)
* End Station (ID & Name)
* Bike ID
* Start & End Hours
* Start Weekdays
* Start Date
* User Type, Gender, Age, Age Group & Whether they use bikeshare for all trips





## Key Findings & Insights ##

* The Analysis showed that the majority of users are subscribers & they mostly use the service for commuting to & from work at peak hours of 8-9 am & 5-6 pm on weekdays.
* It also shows a unimodal more normally distributed timings on the weekends around the after noon
* The majority of the users are males with a significant amount of females & around 2% non-binary users
* Users Age vary significantly between 18 & 140 years old with the majority of the users between 18 & 44 years of age
* February 13th (a weekday) showed a significant drop in demand & Feb 25th (a weekend) showed an unexplained rise in demand
* A lot of the trips were noticed to have a zero distance meaning that it's a round trip which suggest their use for running quick errands or recreational use specially that there duration are typically around the 10 minutes mark
* The Average distance seem to decrease on weekends vs. weekdays while the average duration acts in an opposite manner which could be explained by the fact that people are usually more rushed during commuting times
* There's an increase in the demand on weekends amongst the youngest & oldest age groups
* Customers have longer distances & durations vs. the average subscriber
* The main cluster of data lies below 8 Kms & between the 10 & 60 minutes mark



```python

```
