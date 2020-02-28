# coronavirus

The following repository will hold the data related to the continental US epidemic and mobility model.

Source:

The data file was created through the wolfram mathematica notebook posted in the wolfram community that
can be found in the following url:

Files:

data.mx.zip		association saved in the wolfram language serialized package format. Works only on windows computers.
data.wdx.zip	saved in platform independent file. Can be opened in MacOs for example.

Structure tree:

root
|sources		links to webpages where the data was obtained.
|+populationData
|+populationFiles
|+airTrafficData
|
|rawData		actual imported data without any processing.
|+population
|+t100market
|
|temp			repository for data transformation
|+population		population related data
|++lines		
|++numbers		
|++assocGeoPosition	GeoPosition and its related number of people.
|
|+airTraffic		contains airport and airtraffic associated data
|++header
|++data
|++airports
|+++
|
|+voronoi		contains voronoi cells and its associated properties.
|
|+aux			contains auxiliary data 
|++poly48States		meshregion of the 48 lower US states


	



