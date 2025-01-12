# Data Visualization Final Project Report

## Video
Here is my video of presentation on <a title="Click here for video!" href="https://youtu.be/w4lOLrg6RBU"><img width="70" alt="Yelp Logo" src="https://logos-world.net/wp-content/uploads/2020/04/YouTube-Logo.png"></a> 

## Data

The data I used to visualize for my project is from <a title="Click here for details!" href="https://www.yelp.com/dataset"><img width="70" alt="Yelp Logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Yelp_Logo.svg/256px-Yelp_Logo.svg.png"></a> 

I am interested in top-rated restaurants so I extracted all current-opening restaurants with 4 or above star ratings in Greater Boston (GB) area. Gist link can be found [here](https://gist.github.com/mingliu815/e5f4b3ff7dfeae8a9a2924b121c37468).

I am interested in exploring great food around me and I am sure that data visualization can do me a favor! <img width="50" src="https://openmoji.org/data/color/svg/1F37B.svg">

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * What cities have most great restaurants? 
 * It makes sense that Boston has the most best restaurants, but how about it's neighbors? Are all top cities around Boston, or are there any other cities that not very near to Boston but still have many great restaurants?
 * In all great restaurants, what types of food are served? What are famous food categories?
 * Given a food of interest, what cities have the best restaurants serving this kind of food?
 * Personal interest: where to get best seafood?! <img width="50" src="https://openmoji.org/data/color/svg/1F980.svg">

## Sketches

### Map of best restaurants in Greater Boston area
I am think of creating a map shows number of top-rated restaurants in Greater Boston area, like below:
![image](https://user-images.githubusercontent.com/16920899/137076241-23c96dae-22fa-412a-99f7-ba5e6a21687e.png)

From this map we should be able to see distributions of best restarutants in Greater Boston area. I would use circle size to represent the amount of restarutants in a city. A larger circle means more top-rated restarutants in this city. Therefore we can tell if neighbors of Boston have more best restarutants than other places, and if there are any cities that not very close to Boston and have many great food (question 2).

To answer my personal interest of seafood, I am thinking of creating a seafood only map. This would be similar as the map above, just showing seafood-related restarutant!

An alternative way is a bar chart including what cities have most top-rated seafood, like below:
![image](https://user-images.githubusercontent.com/16920899/137206699-ab3f1b89-e376-4154-b927-4c773584a5e4.png)

### Food categories in cities

Interactive bar chart with menu of type of food. X axis are cities.
I would like to create an interactive bar chart with menu of type of food, like below:
![image](https://user-images.githubusercontent.com/16920899/137206817-db838d9f-eb2e-4594-a36d-9d46e70454a2.png)

There would be a menu bar of food types to choose, for example, American food, Mexican food, Italian food, etc. When the user selects the food type of interests, the top cities of this type of food will show up as bars. The x-axis is city name, and y-axis is the number of restaurants serving this type of food. This graph is related with my question 4.


## Visualization

Here is a bar chart of top cities with best restaurants in GB area.
[![image](https://user-images.githubusercontent.com/16920899/137068326-1e804bb3-7e2c-4ecd-89b1-6123ae6a2501.png)](https://vizhub.com/mingliu815/a73f54d4d5ff4d3199a8ce6817b50693)

We can see that Boston has the most best restaurants (no doubt). Cambridge and Somerville also have over 100 top-rated restaurants. This graph can answer my question 1.

I also made an interactive bar chart of food categories (in terms of regions, e.g. American food, Mexican food, etc.).
[![image](https://user-images.githubusercontent.com/16920899/137072065-8efe69ba-1774-45b8-9880-c0e5f1f8a1ed.png)
](https://vizhub.com/mingliu815/05ee0a8297d24f3ba1375bd62c49d29a)

From this bar chart we can tell that these top-rated restaurants serve diverse food that come from different regions. The famous food categories include American (new/traditional), Italian and Mexican food. This graph can answer my question 3.

**To address the feedback** from the professor of stacked bar chart, I created a stacked bar chart of type of foods in each top cities as below. I didn't include Boston for this time as it has significantly more restaurants than others. Also I added tooltips to present amounts of restaurants of a type of food in a city when you place mouse onto any section on the bar.

[![image](https://user-images.githubusercontent.com/16920899/139177602-b593c612-272b-4b56-8891-2c1a8859d053.png)](https://vizhub.com/mingliu815/5829e1d28f84485fbfbc7fa9a36881cf)

### Map of best restaurants in GB area
I created a map to show number of top-rated restaurants in GB area.
[![image](https://user-images.githubusercontent.com/16920899/144357878-b04aec2f-023c-44ca-8879-d5d6a6f29b35.png)](https://vizhub.com/mingliu815/b8ab978d81fd4e9db9baa0664f65408f)

In this map, colors represents number of restaurants. Grey color is no data area, and red colors are cities with data (in GB area). A deeper red means a higher amount of top-rate restaurants. This is an interactive map that you can zoom in and hover over the cities of interests, and then the names and the numbers of restaurants will be shown in the tooltips. You can also select menu on the top to choose different types of food.

### Map of best seafood in GB area

[![image](https://user-images.githubusercontent.com/16920899/144889483-37d256bf-558e-4f98-8614-2c54bca64f5d.png)](https://vizhub.com/mingliu815/6608027674dc48c68f2aae1356ffc04c?mode=full)

To address my personal interest, I created a map of best seafood in GB area. This interactive map only contains top-rated seafood restaurants, and the city name and the correspindng number of restaurants will be shown when place mouse onto it.

## Schedule of deliverables

* Maps would be the most challenging part so I would spend more time. I expect to get maps done by the first week of November.
  * Map with circles representing amount of restaurants, by week 8.
  * Map with dots representing locations of restaurants, by week 9.
  * Try to add map tiles on the second map and polish maps, by week 10.
* Map of seafood or bar chart of seafood, week 11.
* Interactive bar chart of food categories, week 12.
* Polish the whole project and fix any issues, week 13, 14.

