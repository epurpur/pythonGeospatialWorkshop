```
Last updated 02/19/23
```

# Geospatial Data & Mapping in Python

## **About Me**

Erich Purpur

    Research Librarian for Science & Engineering
    epurpur@virginia.edu
    Brown Science & Engineering Library room I046


I'm a part of a group called [research data services](https://data.library.virginia.edu/) and I do these things:
    
    1. Serve as Liaison to various engineering and social sciences departments
    2. Teach workshops and classes (like this one)
    3. Help people with research projects
    4. Internal Library Projects
    5. Random other things as they come up
    

## Other Upcoming Workshops

[See all of our workshop offerings here](https://data.library.virginia.edu/training/)

| Workshop | Date | Time |
| ---- | ---- | ---- |
| Geospatial Data + Mapping in Python                             |       Wednesday 2/22   |  10:00 - 11:30
| Python and APIs                                                 |       Wednesday 3/1    |  12:00 - 1:30
| Python Web Scraping                                             |       Wednesday 3/15   |  12:00 - 1:30


## Background

My background is in Geographic Information Systems (GIS). Python is a general purpose programming language. It can do many things and it is always growing and enabling people to do more. Traditionally, GIS users have specific software such as ESRI's ArcGIS, or the open source alternative QGIS. These software packages have adopted python as their language of choice and now have fully fleged python APIs that you can use it to write scripts and automate tasks within those languages. However, those are specific use cases and a separate topic entirely. Today we are going to use python mapping and geospatial libraries that are adjacent to the stack commonly used around UVA (and academia) which includes Pandas, Matplotlib, NumPy, and so on. These libraries, specifically GeoPandas, are a nice addition to what you might already be using!

### GeoPandas

[GeoPandas](https://geopandas.org/en/stable/) is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by [Pandas](https://pandas.pydata.org/) to allow spatial operations on geometric types. Geometric operations are performed by [Shapely](https://shapely.readthedocs.io/en/stable/). Geopandas further depends on [Fiona](https://fiona.readthedocs.io/en/latest/) for file access and [MatPlotLib](https://matplotlib.org/) for plotting.

The goal of GeoPandas is to make working with geospatial data in python easier. It combines the capabilities of pandas and shapely, providing geospatial operations in pandas and a high-level interface to multiple geometries to shapely. GeoPandas enables you to do operationsin python that would otherwise require a spatial database such as PostGIS

### Folium
[Folium](http://python-visualization.github.io/folium/) builds on the data wrangling strengths of python and the mapping strengths of [Leaflet.js](https://leafletjs.com/). Manipulate your data in python, then visualize it on a Leaflet map via Folium. Folium makes it easy to visualize data that has been manipulated in python on an interactive leaflet map. It enables the binding of data to a map for choropleth visualizations as well as passing rich vector/raster/HTML visualizations as markers on the map. The library has a number of built-in tilesets from OpenStreetMap, Mapbox, and Stamen, and supports custom tilesets with Mapbox.
