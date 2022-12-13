# **R_Group_Project**
Alison Barbee, Kate Bazany, and Keke Chukwudi
R Programming Course
Dec. 14th, 2022

## *The Data*

This data was pulled from tidy Tuesday. The data files that were used for the maps include locations, brightness, and a few other metrics of Australian wildfires recorded by NASA over two weeks at the end of 2019 and start of 2020. 

There are also files on rainfall and temperature collected at weather stations around Australia.

Rainfall data was sourced from weather stations in:
  Subiaco, Sydney, Melbourne, Brisbane, Canberra, and Adelaide

Temp min/max data was sourced from:
  BoM Climate Data Online

## *Australian Wildfires*

The maps show...

The faceted temperature graphs show daily maximum and minimum temperatures (in degrees Celcius) at each weather station from 2010 to 2020. Seasonal variation patterns are clear. Trend lines were added with geom_smooth. This graph shows slight increases in temperature at most stations over the last ten years, but no major noticeable heatwave events.

The faceted rainfall graphs show the monthly total rainfall (in centemeters) collected at each weather station from 2010 to 2020. These rainfall plots indicate that there were slightly decreases in monthly total rainfall in the years leading up to the fire events in the last week of 2019 and first week of 2020.

## *Notes*

Alison = map of the fire shapes in Australia 
- Australia map 
- use leaflet and create the icon as fire
- Create maps for each station in leaflet and send to Keke
- See if there is a way

- 'crosstalk' between the map and the table or we can put metadata on the 
prescribed burns vs a wildfire on the popup in the map

Kate = time series of rainfall and temperature at different stations 
- faceted plots of rainfall and temperature data taken at different stations in Australia.
- These figures show slight increases in temperature and slight decreases in rainfall over the last ten years.


Keke = dashboard and table
- table of field stations and locations 
- Keke also did the bulk of the work setting up the dashboard, organizing figures, and making a dropdown menu for the different field station data



## *Links*


The original GitHub repository: <https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-07/readme.md>
