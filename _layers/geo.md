
<link href="style.css" rel="stylesheet">

{% include navbar.html %}

<p style="margin: 60px 0px 0px 0px;" />

# Geographical layers

NinJo visualizes meteorologic and oceanographic data on maps. The geographical background and references are provided by five different layers:



There are three geographical layers available: one for raster data, one for vector data and one for displaying the grid of parallels and meridians.

For raster data, different data sets are available (height/elevation, landuse, satellite images, ...). Vector data contains information about coastlines, boundaries, cities, roads, rivers, airports, etc. Which data shall be displayed and with which colors, lines and line attributes, can be configured by the user.

NinJo supports an intelligent level-of-detail display, that means, the more the user zooms in, the more data he sees. The resolution of the images is adapted automatically. 
