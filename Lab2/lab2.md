# Lab 2 Answers
## Abe Burton

### Information:

The web map for this lab can be found at: https://www.abeburton.com/web_mapping/Lab2/

The repository with the code for this lab can be found at: https://github.com/abejburton/web_mapping/tree/main/Lab2

### 1. How would you add another class to your chloropleth map?
To create a new class in the chloropleth map I would find a relevant geojson file that I want to add to the map. Then I would include that as a .js file in the lab2 directory. I would read the contents in as a source in the head of the file, and name it as a new object variable in the script in the body. Then add the addToMap() method at the end to get it to display. Once it is instantiated I would add it to the layer control dictionary so that it can be toggled on and off.

I did this by adding a countries geojson and including that in the script. The borders of the countries are now included in my scipt but I didn't automatically add it to the map because it is an extra unnecessary feature.

### 2. How would you create a map where all overlay layers are toggled off by default? Why would that be useful?
All you need to do to toggle the layers off by default is leave off the addToMap() method after instantiating a geoJSON object. Then the layer control buttons can add it in but it isn't automatically loaded onto the map.
