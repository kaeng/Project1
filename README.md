Project1
========

Project Group: Ben Brintz, Katie Eng, FangWu Wei, Lu Wang

The function `plotfunc("state.abrv")` will produce a state's mean profile of average hourly income by educational attainment level from years 2000-2012. It will also construct profile plots for the proportion of respondents that reported working within the last year, again by educational attainment, as a measurement of "unemployment." An example can be found in the .png file [here](https://github.com/kaeng/Project1/blob/master/Example%20Output%20Oregon%20Profile%20Plots.png).

If you would like to try out the function yourself, see the [tryout] (https://github.com/kaeng/Project1/blob/master/Tryout%20Function%20Code) code. Do note that the function will download the relevent American Community Survey (ACS) data (.zip) to the current working directory, so `setwd()` to your preferred location.

Future improvements could include plotting arguments to show median hourly income, indications of variability in hourly income (as experimented with using`testfunc("state.abrv")`, and dynamic/interactive graphics to visualize both the longitudinal and spatial nature of the ACS data. Creating an argument to indicate whether or not to download data from ACS or to fetch data saved locally would significantly cut down on run time.

The `testfunc("state.abrv")` function profile plots the first, second, and third quartiles, in addition to the top 1 percentile for the years 2001 and 2002. This is an unfinished attept to visualize variability. Future plots may be inspired by the profile plots created in this [NYT article](http://www.nytimes.com/2014/04/23/upshot/the-american-middle-class-is-no-longer-the-worlds-richest.html?src=me&ref=general&_r=0). (Thanks, Alix!)
