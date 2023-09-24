# Final-Project-Tableau

## Project/Goals
I want to show what portion of Calgaries bicycle pathways are easily accessible given a person's cycling fitness, weight. 
## Process
### 1) Get elevation data for Calgary. (DEM model from the City of Calgary website)
https://data.calgary.ca/Base-Maps/Digital-Elevation-Model-DEM-ASCII-2M/eink-tu9p
### 2) Get shapefiles of Calgaries bikeways from the City of Calgary website
https://data.calgary.ca/Transportation-Transit/Calgary-Bikeways/yigb-2xmq
### 3) Calculate inclinations of each 10m segment of Calgary's bikeways using QGIS and a python plugin 
https://github.com/Almeida100/Road-Slope-Calculator
Almeida100
### 4) Calculate theoretical data on the physics of bicycles. See jupyter notebook
created a dataframe from using the formulas and constants described here: https://www.omnicalculator.com/sports/cycling-wattage

### 5) Get cycling demographic data from the City of Calgary website
https://data.calgary.ca/Transportation-Transit/Bike-and-Pedestrian-Counts/pede-tz7g
### 5) Combine datasources in Tableau and create a story

## Results
I found that hilliness is a very import factor in how much effort a cyclist must produce. At 0% incline Cycling at a modest pace of 15 k/hr is easy for almost everyone. Hills in contrast require some "sweat" for almost everyone to varying degrees, and is likely a factor for difference in Calgary's general demographics and the demographics of cycle-commuters. 

## Challenges 
It was difficult using Tableau at times. Specifically using calculated fields relying on parameters in another datasource. I also had to use estimations for cycling fitness that may not be accurate. 

## Future Goals
I found what areas of the city are accessible for each a cyclist without sweating. The next step is finding where it is impossible for a cyclist to access. And trying this for other cities and cycle networks. I would also like to find out a more accurate estimate of FTP fitness 
