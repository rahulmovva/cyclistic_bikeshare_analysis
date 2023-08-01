# Cyclistic_Bikeshare_Analysis
## Introduction
As a junior data analyst working in the marketing analyst team at Cyclistic (a bike-sharing company in Chicago), me and my team are tasked with designing a marketing strategy to convert casual riders to annual members. Casual riders consist of customers that purchase single-ride or full-day pass, whereas annual members purchase an yearly subscription for unlimited biking access. Our team is responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy.

## Ask
In the interest of company growth, the director of marketing believes that Cyclistic should capitalize on the lucrative profit margins of annual subscribers by marketing to existing casual customers and persuading them to become yearly subscribers. If that strategy is plausible, a well-executed marketing campaign may lead to more sustainable long-term revenue. Therefore, we need to analyze how and why Cyclistic casual riders and members differ to weigh any evidence, opportunities, and drawbacks to any future marketing strategy.

## Prepare
The dataset required for the business objective should be of past 12 months. Here I considered the data from the complete year of 2022.
Data Source and Organization
The data was made available by Motivate International Inc. under the appropriate license which ensures credibility of the data. This is public data that you can use to explore how different customer types are using Cyclistic bikes.
As we had to consider only the data related to the past 12 months, I downloaded the csv files as per the requirement and stored it in a single folder so they are easier to access and work on.

The data-privacy issues prohibit you from using riders’ personally identifiable information. This means that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes. This ensures data integrity.

## Process
Research and apply the correct data manipulation tools for processing and analysis
Check for dirty data - in particular for data that is outdated, duplicated, incomplete, inconsistent and inaccurate
Transform and clean the data to a point where it can be worked with effectively in analysis

I am using Python language for working on data as it is more accessible and easier to use.

The first step while starting any analysis is to import appropriate libraries in the notebook.

Some of the important libraries are:
Pandas - Pandas allows importing data from various file formats such as comma-separated values (CSV), JSON, SQL, Excel. Pandas allows various data manipulation operations such as merging, 
         reshaping, selecting, as well as data cleaning, and data wrangling features.
Numpy - It can be used to perform a number of mathematical operations like trigonometric, statistical, and algebraic on arrays.
Matplotlib and Seaborn - It is used to create graphical analysis of the data.
Datetime - These classes provide a number of functions to deal with dates, times and time intervals.

Merging our datasets into a single dataframe
We then read the dataframe in Visual Studio to understand the code
We then check the datatype of all the columns present in the dataframe and convert the datatype according to our requirement
We now add new columns to dataframe in order to make our table look organized
we then add the columns such as ride_length, start_date, week_day.

Now transforming and cleaning the data
Resolving duplicate ids, eliminate missing values, adjusting the minimum ride_length, adding columns for analysis

## Analyze
Scope : Organize and format the data (including useful aggregate tables)
        Identify trends and relationships with the help of calculations, data aggregations, and relevant visuals
        Provide a summary of the analysis
After cleaning the data, it is important to aggregate, organize and format the data. Here we need to perform calculations(descriptive analysis) and understand how casuals and members behave differently.
Average ride length, mode of weekday, maximum number of rides, busiest days,  
Relevant Pictures

## Share
Identifying trends and relations
Users are very few in colder months
Members have consistent usage on working days, active at all times of the day
Casuals are numerous during summer, consistentl have longer ride lengths year-round, tend to be more active in evenings

## Act
We can only make generalized statements about the entire population and is insufficient to draw any conclusions. We need more relevant data.
Assumptions can be made 
Perks for members
Weekend special pass for casuals
