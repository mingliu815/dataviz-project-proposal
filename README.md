# Data Visualization Project (draft)

## Data

The data I propose to visualize for my project is from <a title="Click here for details!" href="https://www.yelp.com/dataset"><img width="70" alt="Yelp Logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Yelp_Logo.svg/256px-Yelp_Logo.svg.png"></a> 

I extracted all current-opening restaurants with 4 or above star ratings in Greater Boston area. Gist link can be found [here](https://gist.github.com/mingliu815/e5f4b3ff7dfeae8a9a2924b121c37468).

I am interested in exploring great food around me and I am sure that data visualization can do me a favor! <img width="50" src="https://openmoji.org/data/color/svg/1F37B.svg">

## Prototypes

I’ve created a proof of concept visualization of this data. It's a bar chart and it shows the top 10 cities with best restaurants in Greater Boston area.
[![image](https://user-images.githubusercontent.com/16920899/134221241-dd7a3df4-bee5-4923-97e1-b026d8efeebb.png)](https://vizhub.com/mingliu815/a73f54d4d5ff4d3199a8ce6817b50693)

We can see that Boston has the most best restaurants (no doubt). Cambridge and Somerville also have over 100 best restaurants.
## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * What cities have most great restaurants? This could be explained by my prototype bar chart.
 * It makes sense that Boston has the most best restaurants, but how about it's neighbors? Are all top cities around Boston, or are there any other cities that not very near to Boston but still have many great restaurants?
 * In all great restaurants, what types of food are served? What are famous food categories?
 * Is there any relation between restaurants ratings vs. review counts?

## Sketches
### Map of best restaurants in Greater Boston area
![image](https://user-images.githubusercontent.com/16920899/134223648-98a37153-d4fc-448a-81d3-dc6ba7371fa2.png)

From this map we should be able to see distributions of best restarutants in Greater Boston area. I would use color shade (or the circle size) to represent the amount of restarutants in a city. The darker color (or a larger circle) means more best restarutants. Therefore we can tell if neighbors of Boston have more best restarutants than other places, and if there are any cities that not very close to Boston and have many great food (question 2).

### Food categories in top rated restaurants
![image](https://user-images.githubusercontent.com/16920899/134223587-cf54a772-f3f2-4690-bd46-876684c24301.png)

I would do either a bar chart or a pie chart to show distributions of food categories among these top rated restaurants. A taller bar in a bar chart, or a larger area in a pie, represents more restaurants serving this type of food. From these visualization we should be able to tell what types of food are served in these best restaurants, and what are the most famous food categories (question 3).

## Open Questions

* I am not sure how to deal with the map. I found a MA state map and was able to successfully show it up, but I was not sure how to color it, or put circles on it using data from here. I tried to play with sample code of adding circles of population on world map, but failed as I was not sure how to customize it based on my needs, especially there is no projection thing for the state map, I think..? 
* Also there are many states don't have any data, as the map is for the whole state while I only have data about Greater Boston area. I was not sure how to deal with these missings on the map.
* I haven't figure out a best way to visualize relations between restaurants ratings vs. review counts (question 4). I did a [scatter plot](https://vizhub.com/mingliu815/7146aad892d64c95844fa6d889cf78df) before while I don't think that really makes sense.
