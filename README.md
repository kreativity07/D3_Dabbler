# Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

Welcome to the newsroom! 

Here's a data visualization challenge for a major metro paper that features stories about the health risks facing particular demographics through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml). It includes data on rates of income, obesity, poverty, etc. by state.

### D3 Dabbler

Create a scatter plot that represents each state with circle elements between two of the data variables. I have picked the variables `Obesity` and `Income` for my visualization. I have also refined the `data.csv` to `new_data.csv` to remove variables that are not relevant to my visualization.

Using D3 techniques, code this graphic in the `app.js` file and pull in the data from `data.csv` by using the `d3.csv` function. 

* Include state abbreviations in the circles.

* Create and situate the axes and labels to the left and bottom of the chart.

* Use `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in the web browser.

* I have included the tooltip feature as an add-on to the scatter plot that will display the `income` and `obesity level` for each of the states in the US on mouseover.
