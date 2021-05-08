# Covid dashboard

[Deploy](https://johnneon-covid-dashboard.netlify.app/)

[Online Covid-19 Distribution Map](https://coronavirus.jhu.edu/map.html). The structure and appearance of this project are taken as a guide.

This is an application for tracking the spread of COVID-19 in the world and in selected countries. The information is provided in the form of a table, a list, a graph and an interactive map.

## The structure and features of the application

1. A table that displays the following data:
     - the number of cases
     - the number of deaths
     - the number of recovered

  The table has switches for displaying data:
   - for the entire period of the pandemic and for the last day (the last date returned by the API)
   - in absolute terms and per 100 thousand population

  <details>
    <summary> Thus, a total of 12 indicators can be displayed in the table </summary>

  1. total number of cases
  2. total number of deaths
  3. the total number of recovered
  4. number of cases in the last day
  5. number of deaths in the last day
  6. the number of people who recovered in the last day
  7. the total number of cases of the disease per 100 thousand population
  8. total number of deaths per 100 thousand population
  9. the total number of recovered per 100 thousand population
  10. the number of cases of the disease in the last day per 100 thousand population
  11. the number of deaths in the last day per 100 thousand population
  12. the number of people who recovered in the last day per 100 thousand population
  </details>

  You can choose a country:
   - by clicking on an item in the list
   - by clicking on the interactive map
   - find using search

## Skills

- using RESTful API
- getting data using asynchronous requests
- different ways of displaying data on the page
- implementation of sorting and searching
- creation of a cartographic application
- work with js libraries