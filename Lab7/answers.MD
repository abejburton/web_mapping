## Question 1: What data field in our layer is being used for color info and how do you know? 5 points. 

The data.properties.DIFF field is being used for color info because it is passed as the only parameter in
the getColorFor function that is called when data is loaded.

## Question 2: How would you rewrite the top part of the getColorFor function so that there is an intermediate, light-blue tier with a break at 3? 5 points. 

I would add a line like this value >= 3 ? '#92c5de' : where #92c5de is a light blue hex code in the getcolor function.

## Question 3: Reflect briefly on what elements work well here and which might confuse audiences. How might you improve this map? 5 points.

I think its strange to have discontinuous jumps in color classification when the polling data is fairly continuous. The map also doesn't show population or overall voting trends for the nation.

## Question 4: Is scaling radius by a direct value bad for symbol mapping? Why/why not? Will resulting symbols be proportional to their values?
You shouldn't scale by direct value because a circle with radius 10 will look much larger than 2x the size of a circle with radius 5. So you should scale the radius somehow as we did in Lab 2 with the Covid data which I adapted for this assignment. You could also scale by the square root of the radius.

The link for the first chloropleth map is here: ``
The link for the voting differences proportional to electoral votes is here: ``
