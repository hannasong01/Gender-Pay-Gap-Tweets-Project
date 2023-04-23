# Gender-Pay-Gap

## Name
Exploring Twitter Users' Engagement Patterns with Positive and Negative Tweets on Gender Pay Gap: A Comparative Study.

## Introduction

Gender pay inequality continues to persist, with women earning only 83% of what men make when working full-time in the US, according to American Assoication of University Women(AAUW). This disparity is further exacerbated by the fact that 14 out of the 20 lowest-paying jobs are predominanatly held by women, while 15 of the top highest-paying jobs are predominantly held by women, while 15 of the top highest-paying jobs are dominated by men. As a result, a 20-year-old woman starting her career today stands to lose a staggering  $406,760 over a 40-year career compared to her male counterpart, as reported by AAUW. The financial impact of this disparity is immense, with working women collectively losing out on over $500 billion annually. Despite efforts towards progress, the slow rate of change indicates that equality in pay may not be achived unitl the year 2111, highlighting the urgent need for action to address this persistent issue.

## Objectives of the Project

The project aims to achieve several objectives. Firstly, it will involve analyzing the volume of positive and negative tweets, with the goal of understanding the sentiment trends in social media conversations. Secondly, the project will explore engagement metrics, such as likes, shares, and comments, in relation to positive and negative tweets, in order to uncover patterns and trends in user engagement. Lastly, the project will seek to draw meaningful insigts from the engagement patterns with different polarity of tweets, with the objective of gaining a deeper undersstanding of how positive and negative sentiment impacts socila media engagement. By achieving these objectives, the project aims to provide valuable insights and understanding of sentiment analysis and engagement metrics in the context of social media conversations.

## Description of the Dataset

File Format: JSON
Dataset Size: 3 GB
Time to collect: 5.5 hours
Data Source: Twitter API
Time Range of Data: January 01, 2022 to January 31, 2022


## Roadmap

Study the JSON data structure from Twitter API.
Finalize data to Retrieve.
Convert semi structured data(JSON) to structured file format.
Make different dataframes as per needed.
Descriptive Analytics: Explore location, language, verification of users and engagements metrics data.
Convert location data which is in address format to coordinates format.
Plot coordinates(latitude and longitude) to a world map and understand distribution of tweets from different regions of the world.
Calculate polarity scores for tweets and label them as positive, negative and neutral.
Engagement analysis of users in positive and negative tweets.

##Softwares for the Project
PySpark is employed for reading and converting semi-structured data from APIs into a structured file format. DBeaver serves as an interface for querying PostgreSQL. The choice between Python libraries and PySpark for analysis depends on several factors. Some analyses are carried out using Python libraries, while others are performed using PySpark, depending on the specific requirements and conditions.

##Description of different files in the repository

basic_exploration.ipynb: This file demonstrates reading json file from Twitter API, conversion of json data to strucutred file format, data and text pre processing, descriptive analytics, text analytics and hyopthesis testing on Gender Pay Gap from Twitter.

address_to_coordinates: This file demonstrates how to extract latitude and longitude coordinates for addresses provided in a dataframe.

plot_world_map.ipynb: This file demonstrates how to create plots on a world map using latitude and longitude coordinates for a given location.


