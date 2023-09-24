# Final-Project-Tableau

## Project/Goals
I want to show what portion of Calgaries bicycle pathways are easily accessible given a person's cycling fitness, weight. 
## Process
### 1) Get elevation data for Calgary. (DEM model from the City of Calgary website)
### 2) Get shapefiles of Calgaries bikeways from the City of Calgary website
### 3) Calculate inclinations of each 10m segment of Calgary's bikeways using QGIS and a python plugin 
### 4) Calculate theoretical data on the physics of bicycles. See jupyter notebook
### 5) Get cycling demographic data from the City of Calgary website
### 5) Combine datasources in Tableau and create a story

## Results
I found that hilliness is a very import factor in how much effort a cyclist must produce. Cycling at a modest pace of 15 k/hr is easy for almost everyone, given a flat incline. Calgary has plenty of hills but most of the network is flat.   

## Challenges 
It was difficult using Tableau at times. Specifically tyring to use calculated fields relying on parameters in another datasource. I also had to use estimations for cycling fitness that may not be accurate. 

## Future Goals
I found what areas of the city are accessible for each a cyclist without sweating. The next step is finding where it is impossible for a cyclist to access. And trying this for other cities and cycle networks. I would also like to find out a more accurate estimate of FTP fitness 
