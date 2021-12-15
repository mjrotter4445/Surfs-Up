# :ocean: Surfs-Up Weather Analysis :ocean:
*for an Exciting Business Venture called the Surf n' Shake Shop in Hawaii*
<p align="center">
   <img width="500" height="300" src="https://github.com/mjrotter4445/Surfs-Up/blob/main/Graphics/surfboardart.png">
</p>   

## Project Overview
This analysis project requires a quick build, quick turnaround data frame that pulls information from available Hawaiian Weather sites.  

### Purpose  
The purpose of this analysis is to help W. Avy, a famous surfer and investor make important business decisions about opening an ice cream 
shop with surf gear, called "Surf n' Shake Shop" on the island of Oahu.  The location is important because climate can vary on the island.  W. Ivy 
wants to be prepared by knowing weather history and patterns in the area where the shop might be located. A perfect place for the shop is where 
there is the right balance of warm temperatures and sunny days throughout the year.  The data-driven decisions that we will make will be 
based on temperature and rainfall for the past 7 years from 2010-2017, specifically June and December. These 2 months are far apart 
enough to ensure we have good conditions year-round.   

      -  The analysis consists of 2 parts:   
      - Temperature Statistics analysis for June and December for 2010-2017.
      - Rainfall analysis for June and December for 2010-2017.

### Results
The analysis focuses on the temperature and rainfall from six different weather stations.
On Oahu, Hawaii from 2010-2017 and June and December, specifically.  

The first 2 charts show the statistics for June and December – togs   

1.	**Data**
     -	There are less data points for December (1517 data points) than June (1700 data points).
2.	**Dispersion of the data**
     -	Temperatures are more spread out in December 
     -	June’s mean is 79.94 F and the median is 75.00 F.
     -	December’s mean is 71.04 F and median is 71.0 F.
<p align="center">
   <img width="300" height="300" src="https://github.com/mjrotter4445/Surfs-Up/blob/main/Graphics/fig%201%20temps.png">
</p>   
<p align="center">
Tables showing June and December temperature Statistics 
</p>

###  Comparison of the Rainfall for June and December:
The analysis focuses on the temperature and rainfall from six different weather stations
On Oahu, Hawaii from 2010-2017 and June and December specifically.  

1.	**Data**
     -	There are less data points for December again (1405 data points) than June (1574 data points).
2.	**Dispersion of the data**
     -	Rainfall quantity is more spread out in December than June.  
     -	June’s mean is 0.13 inches and the median is 0.02 inches.
     -	December’s mean is 0.21 and median is 0.03.
     -	Maximum rainfall in December is 6.42 inches and 4.43 in June. 
     -	Minimum rainfall in December is 0 inches and 0 inches in June too.   
 <p align="center">
   <img width="300" height="300" src="https://github.com/mjrotter4445/Surfs-Up/blob/main/Graphics/fig%202%20prcpt.png">
</p>   
<p align="center">
Tables showing June and December Precipitation Statistics 
</p>

### Summary 
The data frame tables above give us a quick view of the weather in area, but to fully understand the trends, additional
formats and analysis can be helpful.  I've provided 2 box and whisker charts for more visual understanding.  



### 2 Additional Queries and Charts - Box and Whisker Plots to Visualize the Statistics 
The analysis focuses on the temperature and rainfall from six different weather stations.  

The first **box and whiskers chart** shows how the mild and steady temperatures are year-round. There is very little
distribution of data and very few outliers.   
<p align="center">
   <img width="400" height="350" src="https://github.com/mjrotter4445/Surfs-Up/blob/main/Graphics/fig_4%20temps_box_whisker.png">
</p>   
<p align="center">
Box and Whisker plot showing June and December Temperature Statistics 
</p>
 
The second **box and whiskers chart** is impacted by the outliers.    Additional information is needed to really get the the facts.  

<p align="center">
   <img width="400" height="350" src="https://github.com/mjrotter4445/Surfs-Up/blob/main/Graphics/fig_3_precip_box_whisker.png">
</p>   
<p align="center">
Box and Whisker plot showing June and December Precipitation Statistics 
</p>

The next **Data Frame Summaries** represent the AVERAGE Precipitation for both June and December, and begin to give us a clearer picture.      
<p align="center">
   <img width="400" height="350" src="https://github.com/mjrotter4445/Surfs-Up/blob/main/Graphics/fig%20second%20to%20last.png">
</p>   
<p align="center">
Look further into Averages of Rainfall for June and December  
</p>

The next **Line Chart** really gives us a better idea of seasonal Precipitation for both June and December.  We can really make some decisions
from this compilation of summaries and charts.  There was a year in 2010 where above average rainfall did occur, but after that timeframe, 
precipitation leveled out and was very consistent in the years 2011-2017.  
<p align="center">
   <img width="700" height="300" src="https://github.com/mjrotter4445/Surfs-Up/blob/main/Graphics/last%20and%20best%20chart%20avg%20precip%20line.png">
</p>   
<p align="center">
A "Big Picture" view of the data over time for better decision making 
</p>

Environment and Software:
 - **Python**
 - **Jupx Notebook**
 - **PostxQL and PgAdmin**
Dependencies:
  -  **Pandas**
  -  **JSONs**
  -  **numpy**
  -  **re** for regular expressions
  -   imported **datetime time** for timekeeping 
  -  **sqlalchemy** 
  -  **Python SQL toolkit and Object Relational Mapper**
  -  **psycopg2**
  -  **matplotlib**
  -  **seaborn**

Software:
   -  **SQLlite**   
   -  **SQL**  
   -  **Jupyter Notebook**
   -  **Flask Web Server**

