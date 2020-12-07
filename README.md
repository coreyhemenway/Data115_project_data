# *Relationship between USG% MIN% and Versatility Index in Basketball*
## Motivation
I always loved basketball and for this project wanted to find some statistical categories that are overlooked and tried to find a relationship between them that might help take a different look at ways you can track overall efficiency in the sport as well as look for statistical outliers that might be performing above average for their overall worth and usage. Which could shed some much needed light on overrated and underrated/overlooked players. 
Another motivation of mine was obviously find statistucs that are not commonly seen and to find a connection between them, because it seems a little more original and different when trying to analyze these types of stats.
## Source 
I got my data from NBA stuffer https://www.nbastuffer.com/2018-2019-nba-player-stats/, it has a fairly straightforward database with different spread sheets that are updated regularly, and the capability to load the data right into an excel spreadsheet, which made it easy to organize the data and clean it. I decided to use the 2018-2019 dataset from this site because of the anomalies in the recent season.
## Processing
The data I used did not require much processing because the uploadable excel sheet is already very organized on their website. However for formatting for python it made sense to abbreviate columns and chamge column names for ease of access, for example changing "Field Goal Percentage" to "FG%", helped a lot when writing the code into python and being able to see column names fully in the data frame and in excel. Later on in the project I also created a separate data frame in python with just MIN%, USG%, and VI. This was useful in making graphs and analyzing the data, because it does not show data from irrelevant catgeories.
## Visualization
This visualization shows a relationship between MIN% as the x axis values, which is percent of minutes played for a player, USG% as the y axis values, which is total usage in the teams plays and how involved the player is, and VI(Versatility Index), which is how versatile a player is whe it comes to points rebounds and assists, and how balanced theser are, which can relate to the multidimensionality of a player, the VI in this visual was represented in the color of the dot, brighter colors having a higher versatility, it was cool to see the relationships between how the MIN% and USG% related with the color of the dot.

![stats image](https://user-images.githubusercontent.com/72179528/98887316-9b807900-244a-11eb-952d-0c9522258f77.png)

## Final Analysis
As part of my final analysis i looked at this visualization which helps show the how the stats related with eachother as well as helps locate outliers and shows well what I am trying to represent.

![stats image](https://github.com/coreyhemenway/Data115_project_data/blob/master/download%20(2).png)
## Code and Materials
The data that was used and downloaded fromn excel was in .csv, but originally used in .xls form from the data stuffers website to excel. The jupyter notebook and images from that notebook used are also uploaded.
