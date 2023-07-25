#A high price for parks#
###A simple visual story using scrollytelling###

*Project submission for Lede Program, 2023*
[Read it here!](https://aishyv.github.io/parks-and-property/)

###Goal###
A visual analysis of the spread of public goods across the city of Bangalore, India. 

###Data###
| Data | Description | Link |
| ----------- | ----------- | ----------- |
| BBMP public goods, 2022 | A ward-wise breakdown of various public goods provided by the municipal corporation of Banagalore | [Link](https://data.opencity.in/dataset/bbmp-ward-wise-public-goods-data) |
| Property Market of Bangalore in Q3, 2022 | Property rates of popular localities in Bangalore | [Link](https://www.magicbricks.com/blog/property-rates-in-bangalore/130414.html)|
| Base map for Bangalore | A geojson file to use in Datawrapper | [Link](http://projects.datameet.org/Municipal_Spatial_Data/bangalore/)

The property rates data was available as tables on a webpage. I used beautifulSoup to scrape the data and convert to csv using pandas. The notebook for this is available in the docs folder of the repo.

###Graphics###
- Datawrapper was used to create all the maps in the story - as choropleth/symbol maps.
- These were downloaded as svgs and combined in Adobe Illustrator.
- Final step involved converting graphics into a scroll using ai2html and scrollama. I followed [this guide.](https://github.com/jsoma/ai2html-walkthroughs/tree/main/layers-scrollytelling)

###Tools I explored###
-Scrolltellly
-Datawrapper maps
-ai2html
-beautifulSoup

###Things I could not get done in time###
This was not developed to be a strong story piece - instead a simple exercise in executing scrollama successfully. I could have added more context or text explaining the analysis. 
I was also not able to accurately transfer the chart legend from Illustrator to html. 
