# Visualising weekly mortality data using polar graphs.


## Background
Mortality data show clear seasonal patterns relating to temperature and disease prevalence. While polar charts, which map variable values to angles from the vertical and radial distance to the origin, can sometimes be misleading, particularly because of the distortion of area, they are well suited to the display of periodic data. For mortality data, the months of December and January, which share similar climatic conditions, are displayed adjacent to each other in polar charts and are thus easily comparable. 


## Objective
This article demonstrates how polar graphs can be used to examine the evolution of mortality conditions using weekly death data from England and Wales.

## Methods
A Generalised Additive Model is used to decompose the time series of weekly mortality data for age 65+ into a long-term linear trend, a seasonal component, and shorter term smooth variations. The plotting library `d3.js` is used to produce a dynamic visualisation of these trends. The effects of public holidays on death registrations are accounted for through fixed effects.

## Results
Strong seasonality is observed in weekly mortality data, and the high mortality in the first quarter of 2015 in England and Wales is clearly observed in the short-term seasonal mortality trend. 


## Conclusions and contribution
The use of polar graphs and allows the periodic nature of mortality data to be visualised in a simple and meaningful way. Decomposing log-mortality into additive linear, and smooth seasonal and short-term variation allows for insights into the nature of the mortality process. Further work will involve incorporating standardisation against forecast data, and the incorporation of model uncertainty into the visualisation. Comparisons of polar charts with equivalent heat-maps and cartesian line-graphs will also be offered to demonstrate the advantages and disadvantages of each visualisation method.