# 30DayMapChallenge
All of my maps for #30DayMapChallenge 2022. Kudos to Topi Tjukanov for running this awesome mappy event. See more info here: https://github.com/tjukanovt/30DayMapChallenge.
## Day 1: Points
My very first submission to the #30DayMapChallenge ever. This one was done using the Advanced Editor in MapTiler Cloud. Data on the cities population come from [Natural Earth](https://www.naturalearthdata.com/) and were tiled with MapTiler Desktop. You can also upload a GeoJSON directly withou tiling it.
I used this expression for the circle radius in the JSON code:
```
"circle-radius": 
    [
      "sqrt",
      ["/", ["get", "POP_MAX"], 100000]
    ]
```
![](maps/01_points.png)
## Day 2: Lines
When thinking of lines, the biking routes in Brno, Czechia (where I partly live now) came to my mind immediately. You can find the open data for the "Bike to work" event [here](https://data.brno.cz/datasets/mestobrno::dopravn%C3%AD-intenzity-cyklist%C5%AF-do-pr%C3%A1ce-na-kole-traffic-intensity-of-cyclists-of-bike-to-work-event/explore?location=49.164481%2C16.640643%2C9.62) in a variety of formats. There even more awesome datasets at https://datahub.brno.cz/. The Carto Dark Matter basemap was pulled to QGIS by the [MapTiler plugin](https://plugins.qgis.org/plugins/qgis-maptiler-plugin/).

![](maps/02_lines.png)
## Day 3: Polygons
This submission was inspired by the landing map on the [MapLibre project](https://maplibre.org/), I just tweaked the colours. The code for the color styling is available here: https://github.com/maplibre/demotiles/blob/gh-pages/style.json.

![](maps/03_polygons.png)
## Day 4: Green
I decided to do all color Fridays with remote sensing data as it used to be my favourite subject at uni (that I finished this year, yay!). The green one is the confluence of the Alaskan rivers Susitna and Yentna. Processed with [Sentinel Hub](https://www.sentinel-hub.com/) in SWIR, where the green stands out nicely.

![](maps/04_green.png)
## Day 5: Ukraine
For this submission I didn't have enough time so I created a yellow-blue variant of the Toner style in MapTiler Cloud, then cut it in the Inkscape by the dove shape from Freepik.

![](maps/05_ukraine.png)
## Day 6: Network
I found this cool dataset about the Roman Road Network from DARMC: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/TI0KAU and went to try an old map style in QGIS. Didn't turn out quite as I anticipated, but lesson learned!

![](maps/06_network.png) 
## Day 7: Raster
I wanted to explore the David Rumsey's Map Collection and found [this](https://www.davidrumsey.com/luna/servlet/detail/RUMSEY~8~1~345354~90112811:Jizni-Pol%25C3%25A1rn%25C3%25AD-Kraje-%3D-Southern-Pola?sort=Pub_List_No_InitialSort%2CPub_Date%2CPub_List_No%2CSeries_No&qvq=q:czechoslovak%20academy%20of%20science;sort:Pub_List_No_InitialSort%2CPub_Date%2CPub_List_No%2CSeries_No;lc:RUMSEY~8~1&mi=7&trs=301) awesome map from 1965 by the Czechoslovak Academy of Science. Then I georeferenced and overlayed it with the #REMA contours from Living Atlas in ArcGIS Pro. 

![](maps/07_raster.png) 
## Day 8: OpenStreetMap
I work with OSM data on regular basis, be it work, school, or personal projects. The maps I love the most with OSM are these kind of minimalist road networks. I downloaded all the cities from https://download.geofabrik.de/, 100% recommend. Layouts were made in ArcGIS Pro.

![](maps/08_osm.png) 

## Day 9: Space
Space = Star Wars! This one was created with Natural Earth world countries (be careful to select the worldview with Ukraine mapped correctly, such as the US). Filming locations can be found on the wiki: https://en.wikipedia.org/wiki/List_of_Star_Wars_filming_locations. Also, I used this [Star Jedi](https://fontmeme.com/fonts/star-jedi-font/) font for the title, cool stuff.

![](maps/09_space.png)

## Day 10: A bad map
No words needed.

![](maps/10_bad_map.png)

## Day 11: Red
Once again I used the [Sentinel Hub](https://www.sentinel-hub.com/) and looked for beautiful rivers in Alaska in NIR. The contrast of snow-covered and regular Nushagak River surroundings is quite a look.

![](maps/11_red_snow.png) ![](maps/11_red.png)
