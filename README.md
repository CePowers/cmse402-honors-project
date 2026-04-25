# How to make a Connection Map using kepler.gl

kepler.gl is a powerful tool to make geospatial visualizations. It allows the user to create interactive maps with very large datasets and is more focused on geographical visualizations than an interactive tool like plotly and allows more interactivity than a tool like geopandas. The interactivity aspect allows you to create visualizations that can be a part of an audience driven narrative (Segel 2010) where the audience can pick and choose which aspects of the data to investigate. It also has a user interface that makes the tool more beginner friendly and requires less python or coding knowledge.

kepler.gl has an online hosted interface, but can also be used in jupyter notebooks. The kepler.gl documentation has some basics on how to use it in a jupyter notebook but lacks any specific tutorials/examples on how to make specific types of visualizations. My tutorial is aiming to help fill part of this gap by providing a specific example of how to work with kepler.gl within a jupyter notebook. I chose to create a tutorial on how to create a [Connection Map](https://datavizcatalogue.com/methods/connection_map.html). kepler.gl is great for this type of visualization since its interactivity allows the user to hover over individual connections and learn more information. It is also easy to make the map in 3d, so the 3 dimensional aspect of the arcs is more easily viewable. Despite this being a very useful tool, the official documentation for keplergl does not contain an explicit tutorial for how to make this visualization in a jupyter notebook.

For this example visualization I used data from New York City citibikes which can be found [here](https://s3.amazonaws.com/tripdata/index.html)

## Tutorial
[View the tutorial notebook](tutorial.html)
The tutorial is contained within the html file linked above. Unfortunately, kepler.gl maps are built as widgets and require a live kernel to render properly. The maps mentioned within the tutorial can be found below.

## Interactive Maps
- [Tutorial map_1](map_1.html)
    (Map referenced as map_1 in the tutorial, containing the full dataset)
- [Tutorial map_2](map_2.html)
    (Map referenced as map_2 in the tutorial, containing the aggregated dataset)