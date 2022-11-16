# Analysis for San Francisco Bay Ford GoBike Service 2019
## by (Olawoye Taofeek)


#  Data Exploration

## Dataset
The data consists of information regarding over 183,000 rides made in a bike-sharing system covering the greater San Francisco Bay area. The data features include duration (secs) and others such as DateTime, customer type, gender, and some additional variables.
Out of 16 specifications 9 are numerical, 2 are datetime, 4 are object type and 1 is boolean type.
The dataset can be found on this link https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv.


## Summary of Findings
In the exploration, I found that there was a strong relationship between the
duration_sec and Age. The age range between 20-45 have the highest duration seconds, indicating that as the age increases the duration second reduces. 
I found out that most rides were taken between 8th-9th hours and 17th-18th hours. The higher ride frequencies for the morning (8th and 9th hrs) and evening (17th and 18th hrs) can be linked to rush hours where people leave for work and come back later in the evening.
In addition, it was shown that although we have higher number of subscribers as compared to customers, still higher percentage of customers are taking longer trips when compared to subscribers.
It was also shown that bike sharing is available to only subscribers. And the subscribers undergo more trips on Thursdays and Tuesdays.
And lastly it was shown. that most rides were taken on Thursdays and Tuesdays. Weekends have the lowest ride records which actually makes sense as weekends are regarded as work off days.



## Key Insights for Presentation

For this presentation, I focus on duration_sec feature which is the feature of interest and other four selected features which happen to have more influence on the duration_sec. These features are Age, user_type, start_station_name, member_gender, hours(Hours of the day).

Firstly, I plotted a bar chart to show which days of the week recorded the highest amounts of rides, then created distribution of the duration_sec and age, and then moved on to create bar chart to show which member_gender took more rides in San Fransisco. After this I progressed to create a Clustered Bar chart for the relationship between user_type and start_day, and also for User type and bike sharing for trips.
After this I progressed to create a scatter plot to show the dependency of duration_sec with respect to member age. 

To round things off, I created a FacetGrid(scatterplot) so as to check the relationship between the numerical features (duration_sec vs Age) and categorical features concerned (user_type and member_gender)