
Neda Jabbari, Erica Ho
Date: 07/25/2019

### Goal

Explore Soccer Team Summary statistics: 

The name of the team
The total number of goals scored by the team during the 2011 season
A histogram visualization of the team's wins and losses for the 2011 season (store the visualization directly)
The total number of wins the team earned during the 2011 season
The team's win percentage on days where it was raining during games in the 2011 season.


#### Getting the Data

The dataset is attempted from https://www.kaggle.com/laudanum/footballdelphi. 

TO explore the last question, we use the [DarkSky API](https://darksky.net/dev) to get the historical weather data for the day on which the game was played and to figure out if it was raining or not during the game. 

Each game is played in a different location, and this information is not contained in our SQL database. Since, the soccer teams in this database are largely German, we subset HomeTeams as German teams and use the weather in Berlin, Germany as a proxy for this information.


## Project Architecture

* Query the SQL database
* Calculate summary statistics
* Get the weather data from the DarkSky API to calculate statistics
* Complete summary statistics

