# Data Visualization Project Proposal

## Data

The data I propose to visualize for my project is from <a title="Click here for details!" href="https://www.yelp.com/dataset"><img width="70" alt="Yelp Logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Yelp_Logo.svg/256px-Yelp_Logo.svg.png"></a> 

I am interested in top-rated restaurants so I extracted all current-opening restaurants with 4 or above star ratings in Greater Boston area. Gist link can be found [here](https://gist.github.com/mingliu815/e5f4b3ff7dfeae8a9a2924b121c37468).

I am interested in exploring great food around me and I am sure that data visualization can do me a favor! <img width="50" src="https://openmoji.org/data/color/svg/1F37B.svg">

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * What cities have most great restaurants? 
 * It makes sense that Boston has the most best restaurants, but how about it's neighbors? Are all top cities around Boston, or are there any other cities that not very near to Boston but still have many great restaurants?
 * In all great restaurants, what types of food are served? What are famous food categories?
 * Given a food of interest, what cities have the best restaurants serving this kind of food?
 * Personal interest: where to get best seafood?! <img width="50" src="https://openmoji.org/data/color/svg/1F980.svg">

## Prototypes

My current prototypes includes a bar chart of top cities with best restaurants in Greater Boston area.
[![image](https://user-images.githubusercontent.com/16920899/137068326-1e804bb3-7e2c-4ecd-89b1-6123ae6a2501.png)](https://vizhub.com/mingliu815/a73f54d4d5ff4d3199a8ce6817b50693)

We can see that Boston has the most best restaurants (no doubt). Cambridge and Somerville also have over 100 top-rated restaurants. This graph can answer my question 1.

I also made an interactive bar chart of food categories (in terms of regions, e.g. American food, Mexican food, etc.).
[![image](https://user-images.githubusercontent.com/16920899/137072065-8efe69ba-1774-45b8-9880-c0e5f1f8a1ed.png)
](https://vizhub.com/mingliu815/05ee0a8297d24f3ba1375bd62c49d29a)

From this bar chart we can tell that these top-rated restaurants serve diverse food that come from different regions. The famous food categories include American (new/traditional), Italian and Mexican food. This graph can answer my question 3.

**To address the feedback** from the professor of stacked bar chart, I created a stacked bar chart of type of foods in each top cities as below. I didn't include Boston for this time as it has significantly more restaurants than others. Also I added tooltips to present amounts of restaurants of a type of food in a city when you place mouse onto any section on the bar.

[![image](https://user-images.githubusercontent.com/16920899/139177602-b593c612-272b-4b56-8891-2c1a8859d053.png)](https://vizhub.com/mingliu815/5829e1d28f84485fbfbc7fa9a36881cf)

### Map of best restaurants in Greater Boston area
I created a map to show number of top-rated restaurants in Greater Boston area, which is the first one I wanted to accomplish in my sketches below.
[![image](https://user-images.githubusercontent.com/16920899/144357878-b04aec2f-023c-44ca-8879-d5d6a6f29b35.png)](https://vizhub.com/mingliu815/b8ab978d81fd4e9db9baa0664f65408f)

In this map, colors represents number of restaurants. Grey color is no data area, and red colors are cities with data (in Greater Boston area). A deeper red means a higher amount of top-rate restaurants. This is an interactive map that you can zoom in and hover over the cities of interests, and then the names and the numbers of restaurants will be shown in the tooltips. You can also select menu on the top to choose different types of food.


## Sketches
### Map of best restaurants in Greater Boston area

Also I want to try to create a restaurants distribution map, like below:
![image](https://user-images.githubusercontent.com/16920899/137077356-8feed722-6c9b-4130-a848-6f8fe6f2da8e.png)

Instead of putting circles to represent amounts, here I would use dots to visualize the locations of the restarutants. Even better, I would try to add map tiles so that when I zoom in I can even tell which street that the restarutant is on.

To answer my personal interest of seafood, I am thinking of creating a seafood only map. This would be similar as the map above, just showing seafood-related restarutants!

## Schedule of deliverables

* Maps would be the most challenging part so I would spend more time. I expect to get maps done by the first week of November.
  * Map with circles representing amount of restaurants, by week 8.
  * Map with dots representing locations of restaurants, by week 9.
  * Try to add map tiles on the second map and polish maps, by week 10.
* Map of seafood or bar chart of seafood, week 11.
* Interactive bar chart of food categories, week 12.
* Polish the whole project and fix any issues, week 13, 14.

