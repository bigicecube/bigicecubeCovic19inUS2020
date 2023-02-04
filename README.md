# bigicecubeCovic19inUS2020
This repository contains maps that describes Covid19 counts and rates across USA in 2020.

Map1, which is based on the data of Covid19 counts in US in 2020, utilized the proportional symbol function in order to represent
distinction between number of occurences within the place. As the size of dot increases, it indiciates there are more people who are
infected with Covid19. The scale is shown on the legend located at the bottom-right corner of the map. 
new mapboxgl.Popup() function enabled me to click onto the dot and read the detail implemented inside it.
Map2, which is based on the data of Covid19 rates in US in 2020, utilzied the choropleth function in order to represent distinction
between case rates within the county. As the color of the choropleth gets darker, it indicates there is higher case rate of people
who are infected with Covid19. The scale is also shown on the legend located at the bottom-right corner of the map.
layers.forEach((layer, i) function enabled me to create the choropleth layer for the map and see the difference between the counties. 

The libraries for both maps, I used mapbox gl js for the creations and for map1, I used Open Sans font from google.
The US covid19 counts data was originally from New York Times, while the US county data is from U.S. Census Bureau.
The US covid19 rates data was collected from 2018 ACS 5 year estimates. 
The acknowledgement goes to Steven Bao, who processed the data, and I appreicate his assistance in creating lab data. 




The url to the map1: https://bigicecube.github.io/bigicecubeCovic19inUS2020/map1.html
The url to the map2: https://bigicecube.github.io/bigicecubeCovic19inUS2020/map2.html

![Map1](https://github.com/bigicecube/bigicecubeCovic19inUS2020/blob/main/img/map1.png)
![Map2](https://github.com/bigicecube/bigicecubeCovic19inUS2020/blob/main/img/map2.png)
