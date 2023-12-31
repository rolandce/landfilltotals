For this interactive choropleth map I wanted to show the total number of landfills per state/territory in the United States. Each state/territory has a suprising, or almost unexpected number of landfills. North Carolina obtains 123 landfills as of 2023 (EPA), which is compartively higher than other US states. I found these statistics particularly interesting to analyze and map. 

I obtained this data from the US Environmental Protection Agency website (linked in the footer of my map). The EPA provided operational projects, candidate landfills, and all landfills for each state/territory. This information is relevant as it was collected in July of 2023. Additionally, I added landfill information for Alaska, Puerto Rico, and Hawaii which can be viewed on my interactive map. 

With this I was able to utilize a US states shapefile by implementing the new landfill data to create a new geojson file. 

For my symbolization, I utilized 9 classes (grades) ranging from 0 to 301 (0, 10, 25.5, 36, 47.5, 55.5, 76, 124, 301). This quantile class break provided the best overall visual impact. I also used the 'OrRd' chroma scale to accurately depict the range of landfills among the states/territory. 

I feel that my design provides an interesting experience to the map reader. The range of colors expresses the diversity of landfill locations among areas in the United States. 