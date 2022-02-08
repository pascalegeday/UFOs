# UFO Sighting Web Page 
# Overview
In this analysis we built a table using UFO Sighting data stored in a JavaScript array. By creating filters to make this table fully dynamic by reacting to user input, and then placing the table into an HTML file for easy viewing. Finally, customizing the webpage using Bootstrap, and equip the table with several fully functional filters that allow users to interact with the visualizations. 
This way, users are able to filter through hundreds of UFO sightings. 

# Resources 
* Data source: data.js
* Programming languages & Framework: Javascript, HTML, CSS
* Tools: Bootstrap, d3 

# Results
&nbsp;&nbsp;&nbsp;In order to perform a search using this interactive table, there are five filters/criteria a user can take into consideration in order to narrow down their search of UFO Sightings: Date, City, State, Country, State. These filters allow the user to interact with the table so that only the specified criteria inputted appear. 
Below is an example of the filters without any criteria inputted, the light-grey colored text show an example of the type of information that can be inputted in each filter: 
  
  
  <img width="276" alt="filters" src="https://user-images.githubusercontent.com/94571150/153071269-0e8cfaa5-105b-4941-9fc4-187239f6b81b.png">

Below is an example of two variations of searches that a user is able to perform: 

* In the first example below only the filters for "State" and "Shape" were inputted. The user intends to filter the data to show UFO Sightings that took place in California and that were described as being in the shape of a Triangle. 
 <img width="1268" alt="ex  1" src="https://user-images.githubusercontent.com/94571150/153071345-09699de7-8850-47cb-8228-8c679c36b694.png">
* In the second example below only the filters for "Date" and "City" were inputted. The user intends to filter the data to show UFO Sightings that took place on the 1st of January, 2010 in the city of Spring Valley. 
 <img width="1258" alt="ex  2" src="https://user-images.githubusercontent.com/94571150/153071355-a375e8c2-ec1d-4ba8-99fe-c573657385f5.png">

# Summary
&nbsp;&nbsp;&nbsp;Unfortunately, this web page does have a few drawbacks. The first being, if there are no data entries with the user-specified filters the data table returns to the original list of sightings. This may prove confusing to users. 
&nbsp;&nbsp;&nbsp;It is recommended that there be the addition of a pop-up or a warning that no data entries were found under those crtieria, so that the user knows to change to valid filters. Another recommendation, the addition of a "filter button" may make the web page more user-friendly, if the user is not aware that the data table automatically loads, it may prove useful to include a "filter button" just in case the page is not loading properly. Lastly, the data used for this web page is not recent enough to merit any updated analyses. It would be best to include data from recent years, or include multiple years of sightings instead of data only from 2010. 
