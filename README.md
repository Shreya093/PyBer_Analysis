# PyBer_Analysis

## Project Overview

The purpose of this project is to analyze the data for a ride sharing company called "PyBer" . We need to calculate the total weekly fares for each city type the rideshare company operates in. Datasets containing ride and city data were used to calculate metrics such as total rides, total drivers, total fares, average fare per ride and driver for each of the respective city types.The Data sets were also used to create a new data frame to find the average fare per week from January 1st 2019 to April 29th 2019 for each of the city types. The dataframe from the analysis was used to create a multiple-line graph using pandas and matplotlib that visualized the total weekly fares for each city type for the above mentioned period. 
This detailed analysis has to be presented to the CFO of PyBer company.

## Results

After merging the provided datasets (city_data.csv and ride_data.csv) into a single dataframe and then applying the groupby() function on the city type to get the total rides, total drivers, total fares, average fare per ride and average fare per driver we created the below new PyBer summary dataframe.

<img width="627" alt="PyBer Summary DF" src="https://user-images.githubusercontent.com/88418201/134265609-0cf4d516-ae6a-45a3-8717-b9036261b2c2.png">

From the above dataframe we can infer :

1. Urban city type have the most number of total rides and drivers while rural city type have the least numbers.
2. As  a result of highest number of total rides and drivers the Urban city type generates the most revenue by having the highest amount of total fare ($39,854.38). The rural city type have the lowest fare amount ($4,327.93).
3. The Urban city type had more total drivers than total rides, which had a dramatic impact on the average fare per ride and average fare per driver. The Urban drivers had the lowest average fare per ride ($24.53) and earned significantly less than the Rural drivers ($34.62).
4. The other metric in the dataframe is the average fare per driver, from this data it can be seen that drivers in the rural city type make $55.49 per ride, whereas the drivers in urban areas make almost 3 times less per ride which is $16.57

A multiple line chart was created  as part of the analysis to help us visualize and perform analysis of the total fares from January 1st 2019 to April 29th 2019 for each of the city types.

<img width="1154" alt="PyBer fare summary" src="https://user-images.githubusercontent.com/88418201/134267294-59ac9024-7694-4b4f-98ed-096fdf2a5d60.png">

From the above line chart we can understand the below points :

1. Urban and Suburban city type starts to rise from the beginning of the January 2019 while the Rural city type gains it's growth by the end of February. By the end of February all the three city types rise to their peak.
2. For Urban city type the fare peak kept on rising through the April while for Suburban and Rural city type the fare price started to decline in the month of March.
3. The Rural city type increases again leading into the month of April. The Suburban city type starts to peak again at the end of April, while the Rural city type drops off.

## Summary

Based on the above results, the three business recommendations I would give are :

1. As the Urban city type has the highest number of rides and drivers which results in more revenue by generating the highest amount of total fare among all the three city types. Hence, it is the best performing city and PyBer should invest more into it to receive greater profits in the future.
2. Rural city type account for least number of rides and drivers among all the three city types even though it has received the highest average fare per ride. In order to generate more revenue and much more rides in the rural cities PyBer should hire more drivers and they can also invest in good advertising campaigns of their ride sharing company so that more people from rural cities can book their rides from them.
3. Suburban city type is the average performing city type as it falls under the middle category for all the revenue and the rides count it have accomplished among all the three city types. Since Suburban city type is doing pretty well I would recommend PyBer to focus more towards Urban and Rural city type to increase their investments and other perks which can result into greater profits for them in future.
