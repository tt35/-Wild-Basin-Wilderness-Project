# Wild Basin Wilderness Project

**Project Overview**

This project was conducted by four students at Calvin Univesrsity to study the effect of urban development on Golden-cheeked Warblers in TX.

Authors: David Vasquez, Tomoki Takeuchi, John Hong, Jose Hernandez

**1. Project Partner**

Our project partner is Professor Proppe, who is doing research on Golden-cheeked Warblers. The Golden-
cheeked Warblers are an endangered bird species in Texas, though common in some other places, has a very
narrow habitat in central Texas. The ultimate goal is to preserve this species in central Texas and prevent
them from going extinct in Texas. He is seeking to investigate the effects that urban development, highways
and housing developments in particular, may be having on the behavior of the Golden-cheeked Warblers as
Austin develops into west, the habitat of the Warblers. The mission is to determine whether if there is any
trend in the Warblers within the reserve in response to development around the reserve.

**2. Goals and Deliverables**

- Goals
1) Are there things that are driving the golden-cheeked warbler out of the area (housing, roads, etc.)?
2) Are golden-cheeked warblers moving west away from development?
3) How do spatial trends change over time?

To answer those questions, we will first need to find the data about urban development. We can combine the
data with the shapefiles of birds observations. One idea that we have is making a grid. In this way, we can
compute the number of dots (birds observation) in each grid, and how it changed over time. In addition to
making grids, we could also use longitude and latitude as response variables to study where their habitat has
been shifting over years.

- Deliverables
1) Statistical model and results that contains information about the location of the birds with relation
to the level of development in the area. The response variable of the model would be the number of
Warblers. This would be done through the use of cells that subdivides each of the properties, so that we
can compare the number of Warblers in a region of the property across years. The predictor variables
would be level of development around a particular cell as measured by the mean level of impervious
surface within a 1km buffer around the cell, the property, year, and the (scaled) UTM location of the
cells.
2) Map of data points from 2011, 2013, 2016, and 2019, showing the points where the Warblers were
observed by property. This would also include a heat map of the locations of the Warblers.
These would be in the form of Rmd files with annotations, graphics, and a map for the second deliverable.
We will also be providing presentation slides detailing the process of data processing, graphics, and modeling
completed during the project.


**3. Data**

Data will be shared on Google Drive. We will have access to data from the city of Austin in the form of
shape files. We will search for road map shape files and use the national land cover database to find land use,
housing density, and other development-related shape files.
Dr. Proppe also mentioned he has created a shapefile of a grid in ArcGIS representing spatial cells. We can
see how many birds are present in a specific cell each year or if there is even a presence (0,1). We can add
attributes to those cells (distance from road, housing, lat/long, habitat, etc.) and do data analysis.

**4. Data Prep**

Dr. Proppe mentioned how data was collected using a variety of methods. So, he will filter out the data he
wants use to use. In addition, the shape file of the warbler data expands beyond the boundaries of the nature
preserves, so our group will have to clip the layer to match the boundaries using GIS. We then have to find
other shape files containing habitat and development variables and extract that data. We will then have
to extract the data from the shape files of the warbler data and then create a new data set including both
variables. We can then determine which statitical model to use.

**5. Background**

- Noise and bird spatial: https://www.ace-eco.org/vol15/iss2/art4/
- Scholar profile Dr. Proppe: https://scholar.google.com/citations?user=tBZOipYAAAAJ&hl=en&authuser=1
- Golden-cheeked Warbler biology: https://www.allaboutbirds.org/guide/Golden-cheeked_Warbler
- Scholar profile Dr. Morrison: https://scholar.google.com/citations?user=yNnoxfgAAAAJ&hl=en&oi=ao
- Scholar profile Dr. Reidy: https://scholar.google.com/citations?user=gk5UxY4AAAAJ&hl=en&oi=sra
and John and Jose will work more on statistical parts.
