# UFOs

## Overview:

The purpose of this analysis is to build a webpage that provides information on UFO sightings. The webpage contains an article and a table of data on UFO sightings. The table can be filtered for sighting date, city, state, country, and shape. The data for this table can be found in the javaScript file located in static/js/data.js. Functions to retrieve and filter the data are written in javascript and can be found in static/js/app.js. index.html contains the code to display the webpage. By opening index.html, you will be able to see the title, an article, an image, and a table that can be filtered.

## Results: 

Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

To filter the table for data of interest, navigate to 'Filter Search' at the bottom of the webpage. There are five filter options and the results of the filtering process are displayed in a table to the right. Below is a screenshot of the filters with their default settings and the table without any filters applied. 

![screenShot_anchorageCityFilter.png](https://github.com/charliuden/UFOs/blob/main/screen_shots/screenShot_noFilters.png)

You have the option to perform both specific and broad searches on this dataset. For example, if you are only interested in UFO sightings reported to be a 'triangle' shape, then you can simply enter 'triangle' into the shape filter and view all sightings with a triangle shape. The screenshot below shows this filter output.

![screenShot_circleShapeFilter.png](https://github.com/charliuden/UFOs/blob/main/screen_shots/screenShot_circleShapeFilter.png)

If, on the other hand, you were interested in finding out information about sightings on a specific date at a specific place, then you could apply more filters. For example, you may wonder what sightings have occurred in Anchorage, Alaska on January 1st, 2010. Filter results for this search are shown below. *Note that the 'triangle' shape that is entered is the default text for that search field but was not applied for this particular search.*

![screenShot_anchorageCityFilter.png](https://github.com/charliuden/UFOs/blob/main/screen_shots/screenShot_anchorageCityFilter.png)

## Summary: 

A drawback to this webpage is that it looks simply at individual data points but does not explore trends or relationships between variables. To add an analytical element to this webpage, I would create a few plots to display above the table. For example, a plot of time by frequency of sightings and a plot showing the spread of UFO shapes. Users would be able to view both the individual UFO sightings and UFO trends. 

