# Purpose of the branch 

D3 and React tutorials from Shirley Wu

## Workshop goal : 
- Use D3 for calculate data 
- React to render visualizations 


## Why ? 
- D3's learning curve : enter - update - exit == React's virtual DOM ! 

Order of taking the courses : 
1) Data vizualisation for React developers 
2) Introduction to data vizualisation with d3.js v4 
3) Building custom data vizualisations 


## Data Types 

- Categorical (genres)  
Ordinal (t-shirt sizes)
Quantitative (temperatures, ratings, score)
Temporal (dates)
Spatial (cities)

## Basic Charts and when to use them 

- Bar Chart for categorial comparaisons (domain: categorical, range: quantitative)
- Histogram: categorial distributions (domain: quantitative, range: frequency)
- Scatterplot: for correlation (2 attributes and the relationship between their quantitative values)
- Line chart: for temporal trends (domain : temporal, range : quantitative)
- Tree : for hierarchy, parent-child relations, multiple tiers of category (one directional)
- Node-link diagram : for connection (relationship between entities, cyclical)
- Chloropleth : for spatial trends (domain : spatial regions, range : quantitative). cf. Datawrapper academy. Best for : regional patterns, only one variable, relative data. Not good for suble differences in data. 
- Radial charts: are cool, for annual weather of a city for example

## Pie Charts : do's and dont's 

Pie chart for hierarchical part-to-whole.
Best for when values are around (25,30 or 75%).
3-4 values. 
Not good for comparing fine differences, multiple totals. 

## Introduction to SVG 

- rect : x , y , width , height 
- circle : cx, cy, r (radius)
- text : x, y, dx, dy (x or y coordinate offset), text-anchor (horizontal text alignment)
- path: d (path to follow)




