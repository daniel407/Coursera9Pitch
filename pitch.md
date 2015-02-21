Reproducible Pitch Presenation
========================================================
author: Daniel
date: Sat Feb 21 10:31:13 2015
transition: rotate

Shiny Application to compute gravitational force
========================================================
Outline of this presenation

- Motivation
- Description of the App
- Calculations and data used

Motivation
========================================================

There are numerous situtations in every day life in which it is useful to know the gravitational force that acts upon an object of a certain mass when located on the surface of a certain planet. 

In a growing number of instances, not knowing the precise values of gravitational forces has had unpleasant consequences to individuals. For instance, inviduals that are not able to answer simple questions on gravitational force are more likely to be made fun of and also more likely to get de-friended on important social networks like Google+ or Instagram.

Furthermore, the number of businesses worldwide which received low ratings on yelp because their employees were not able to assist in customers' inquiries on gravitational forces has doubled every year since 2013.


Description of the app
========================================================

In order to use the gravitational force calculator follow the steps:
- open the link to the web page
- select a mass in the slider bar on the right
- choose a planet in the drop down menu
- the gravitational force will be displayed in units of Newton


Calculations and data used
========================================================


<small>
The gravitational force is the product of an object's mass and its acceleration which is on the planet earth a g-value of 9.81 m/s2. Here is an example calculation:</small>

```r
mass=150;g_value = 9.81
force = mass * g_value; force
```

```
[1] 1472
```
<small>
The gravitational constants (g-values) used by the app are:</small>

```
   planet      g
1   earth  9.807
2    moon  1.625
3    mars  3.711
4 jupiter 24.790
```
