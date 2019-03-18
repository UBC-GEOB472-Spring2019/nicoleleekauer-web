# Crime Rate and Income of Vancouver

# Reflective Analysis
I designed the map for city planners and the city council of Vancouver. I wanted to map out the correlation between family income and density of crime rate. As a result, I found that there is a higher occurrence of crime in the downtown area, Olympic village and mount pleasant area. Initially, I wanted the hover box on the top right corner of the map to display the type of crime and income. However, I didn’t understand my data and mapbox GL JS to do so. 
To create this map, I followed a two part tutorial on mapbox (https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-2/). 

I first made a choropleth map using ArcGIS and Mapbox studio. This process was the most time consuming because I initially tried to import tabular data into Mapbox directly. I thought I could somehow match the name of neighbourhoods it is associated with the neighbourhoods in Mapbox Studio. After several trials, I found that I needed to join the tabular data with a shapefile. To create the choropleth effect, I added stops to the data to classify breaks. I then overlay crime as point data, which I used a red opaque symbol. I did this so that when the map is zoomed out, we can see the density of the point data increasing. I used different shades of purple to represent income, which made the red points stand out.
The interactive function did not work the way I expected it to. If I could improve upon this map, I would say I wish I had more time outside of class to work with Luke or another classmate to figure it out. With this in mind, however, I’ve learned a great deal about Mapbox GL JS in this process. 

# Critique session
I mostly worked on this assignment alone, with some suggestions from Luke along the way. I sent this map to my cousin who is a programmer to look at. He found the map to be aesthetically pleasing, and hoped that with some practice, I can learn to add interactivity. 

![alt text](https://raw.githubusercontent.com/UBC-GEOB472-Spring2019/nicoleleekauer-web/master/crime%20rate%20and%20income.png)

https://raw.githubusercontent.com/UBC-GEOB472-Spring2019/nicoleleekauer-web/master/interactive%20mapping%202.html
