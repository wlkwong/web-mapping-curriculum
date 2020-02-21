Data Report: Fracking

Problem and Objectives 

<b>Problem</b>
1. Fracking in California and effects on groundwater
Fracking causes overdrawn groundwater basins that are a water source for certain counties (diminishing potable water source). 
2. Health concerns
3. Who is potentially affected 
Population in affected areas

<b>Objectives</b>
1. Educate policy makers
2. Educate and inform individuals who may be affected by fracking 
3. Provide information to activist groups opposing fracking in California

<b>Datasets</b>
1. California Geographic Boundaries
Link: https://data.ca.gov/dataset/ca-geographic-boundaries
2. Population of Counties in California (2020)
Link: http://worldpopulationreview.com/us-counties/ca/
3. CA Fracking Wells 
Link: https://drive.google.com/open?id=1kF7-pHg94COQo69L7gjEcs1co54yNLf7  
4. CA Groundwater Basins 
Link: https://drive.google.com/open?id=1kF7-pHg94COQo69L7gjEcs1co54yNLf7 

<b>Dataset Descriptions</b>
Define the need for each of the datasets. How do each of the datasets help you meet your objectives?

1. California Geographic Boundaries
Highlight counties where fracking is occuring. 
2. Population of Counties in California (2020)
Shows the amount of the population potentially impacted by fracking.
3. CA Fracking Wells 
Map users can quickly glance where the highest density of fracking wells is located in CA.
4. CA Groundwater Basins 
Shows location of GW basins in CA.
Show GW basins where hydraulic fracturing is occurring. 
Show GW basins that are a potable water source and where fracking is occurring.

Are there additional datasets that would help you meet your objectives? What barriers exist that prevent you from incorporating those datasets?

1. Income Data for Select Counties 
We have a time constraint where we might not be able to include this in our final map. 
2. Add choropleth map of total fracking well volume 
We would need total well volumes which might take time to track down and synthesize.
This data would provide a stronger link between fracking and diminishing GW supply. 

<b>Methodology</b>
Describe steps required to prepare data for use in your web map. How will you need to transform the data? Do you need to combine it with other kinds of data? Does it need to be reformatted in any way?

1. Counties
Isolate CA counties.
Isolate 10 desired counties.
Only show the 10 counties along with the first paragraph of the scrollytelling map.
2. Population Affected
Get populations of all ten counties with fracking.
Calculate total.
Show up in popups. 
3. CA Fracking Wells 
Add all wells from shapefile. 
Determine if fracking wells are located in high priority GW basins (SGMA 2019 Basin Prioritization Plan).
4. CA GW Basins 
Add all CA GW basins. 
Differentiate GW basins that have fracking wells and high priority GW basins (SGMA 2019 Basin Prioritization Plan) from GW basins not expected to be impacted with different colors. 

For each dataset, description of how the data will be displayed on your web map. What kinds of UI elements and interactions will you need to build for your user to understand each dataset? 

1. Counties 
10 counties that have fracking activity will be highlighted.
Linked to a paragraph in the scrollytelling map.
2. Population Affected
Total can be in scrollytelling text.
Population for each county can be a popup when alongside paragraph with corresponding scrollytelling text.
3. CA Fracking Wells 
All fracking wells will be shown in one color and symbolized by a circle that re-adjusts in size as the map user zooms in.
4. CA GW Basins 
Different colors for basins that are overdrawn versus basins not affected by fracking. 
Select GW basins will have scrollytelling text, for example, the most overdrawn GW basins (summarize report text from SGMA 2019 Basin Prioritization Plan).
