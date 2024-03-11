```
Last updated 03/11/24
```

# Geospatial Data & Mapping in Python

### Link to recording of this workshop
- [View on PanOpto](https://uva.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=291ecd96-3ea0-4a03-8808-b10d013e608e)
- [View on Youtube](https://www.youtube.com/watch?v=MEe_M4XfmMQ)

## **About Me**

Erich Purpur

    Research Librarian for Science & Engineering
    epurpur@virginia.edu
    Brown Science & Engineering Library room I054


I'm a part of a group called [research data services](https://data.library.virginia.edu/) and I do these things:
    
    1. Serve as Liaison to various engineering and social sciences departments
    2. Teach workshops and classes (like this one)
    3. Help people with research projects
    4. Internal Library Projects
    5. Random other things as they come up
    

## Upcoming Workshops

[See all of our workshop offerings here](https://data.library.virginia.edu/training/)

| Workshop | Date | Time |
| ---- | ---- | ---- |
| Intro to Python pt 1                                                |       Tuesday 1/30   |  12:00 - 1:30pm
| Intro to Python pt 2                                                |       Tuesday 2/6    |  12:00 - 1:30pm
| Python Data Analysis + Visualization                                |       Tuesday 2/13   |  12:00 - 1:30pm
| Intro to Version Control w/ Git + Github                            |       Wednesday 2/14 |  10:00 - 11:30pm
| Python and ChatGPT                                                  |       Tuesday 2/20   |  12:00 - 1:30pm
| Geospatial Data + Mapping in Python                                 |       Tuesday 3/12   |  12:00 - 1:30pm


## Background

My background is in Geographic Information Systems (GIS). Python is a general purpose programming language. It can do many things and it is always growing and enabling people to do more. Traditionally, GIS users have specific software such as ESRI's ArcGIS, or the open source alternative QGIS. These software packages have adopted python as their language of choice and now have fully fleged python APIs that you can use it to write scripts and automate tasks within those languages. However, those are specific use cases and a separate topic entirely. Today we are going to use python mapping and geospatial libraries that are adjacent to the stack commonly used around UVA (and academia) which includes Pandas, Matplotlib, NumPy, and so on. These libraries, specifically GeoPandas, are a nice addition to what you might already be using!

### GeoPandas

[GeoPandas](https://geopandas.org/en/stable/) is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by [Pandas](https://pandas.pydata.org/) to allow spatial operations on geometric types. Geometric operations are performed by [Shapely](https://shapely.readthedocs.io/en/stable/). Geopandas further depends on [Fiona](https://fiona.readthedocs.io/en/latest/) for file access and [MatPlotLib](https://matplotlib.org/) for plotting.

The goal of GeoPandas is to make working with geospatial data in python easier. It combines the capabilities of pandas and shapely, providing geospatial operations in pandas and a high-level interface to multiple geometries to shapely. GeoPandas enables you to do operationsin python that would otherwise require a spatial database such as PostGIS

### Folium
[Folium](http://python-visualization.github.io/folium/) builds on the data wrangling strengths of python and the mapping strengths of [Leaflet.js](https://leafletjs.com/). Manipulate your data in python, then visualize it on a Leaflet map via Folium. Folium makes it easy to visualize data that has been manipulated in python on an interactive leaflet map. It enables the binding of data to a map for choropleth visualizations as well as passing rich vector/raster/HTML visualizations as markers on the map. The library has a number of built-in tilesets from OpenStreetMap, Mapbox, and Stamen, and supports custom tilesets with Mapbox.


## **Self Help - You don't need to remember all of this!**

Honestly, you don't need to remember most of it. Here are the resources I use when looking for answers:

ChatGPT
* ChatGPT has quickly made huge changes to the programming landscape. It is a hugely powerful tool **If you use it the right way!**. I think it is a somewhat slippery slope of how to advise new programmers to use ChatGPT (or other AI tools) so I will refer to some best practices. My personal opinion is that you should use AI minimally when you are starting. When you have a better grasp of basic fundamentals, then you can include AI and greatly increase your speed. **Never accept ChatGPT code verbatim!** Always double check it before including it in your workflows.
* [How to Effectively Learn to Program w/ ChatGPT](https://towardsdatascience.com/how-to-effectively-start-coding-in-the-era-of-chatgpt-cfc5151e1c42)
* [Corey Schafer's "How to use ChatGPT"](https://www.youtube.com/watch?v=jRAAaDll34Q)

[Matplotlib Documentation](https://matplotlib.org/3.1.1/index.html)

[Stack Overflow](https://stackoverflow.com/) is a huge user community Q&A type site. Odds are very high that someone has 
asked your question before, just google something like "how to make scatter plot matlplotlib python". I'm pretty certain a 
StackOverflow thread will be one of the first few search results

*Stack Overflow Etiquette*
Don't just ask questions right away. Odds are high that for widely used packages, like matplotlib, a question and answer 
already exists. It is good practice to use that (and upvote it) if you like the answer. 

If you do ask a question, make sure it is specific and reproducible. People will downvote you and moderators will close the 
question if it is vague, incoherent, not-reproducible, or not clear in some other way. StackOverflow's purpose is to act as 
a reference guide, not as a forum to debate open ended questions such as "what is better, matplotlib or ggplot?". Go on 
Reddit if you want to do that. 

