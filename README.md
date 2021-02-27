# UFOs
![](static/images/The_Truth_Is_Out_There.PNG)
## Project Overview
In this project we will focus on building a dynamic UFO sightings webpage by inserting JavaScript into an HTML page. We will start by building a table to hold and neatly display the UFO data we want to work with. Then we'll add filters of that table which lets users refine their UFO search on multiple elements. The table and it's filters will be inserted into, and visually displayed by an HTML page. We'll use basic HTML, Bootstrap, and CSS to build and style the page. The end result will be a presentation of data that is both visually appealing and interactive.  

## Results and Webpage Functionality 
- ***Initial webpage table:*** When we first navigate to our dynamic site we find a table containing records of 111 UFO sightings. That's a lot of data for the end user to sift through and digest all on their own. (see initial webpage below)<br/>
![](static/images/readme1.png)


- ***Filter search section:*** In the lower left of our webpage we find a "Filter Search" section (shown below). In this section we find five text input boxes that allow us to filter our table by one or even multiple free form entries.<br/>
![](static/images/readme2.png)


- ***Applying filters to our table:*** We chose to filter the table by "State" and "Shape" looking for sphere shaped sightings in the state of California. After the filters are applied to the database we find 2 results that meet our parameters (filters and final table view shown below). The results showing in the Date, City, and Country input boxes are only placeholders to help guide the end user - they do not impact the filter results.<br/> 
![](static/images/readme3.png)

## Summary and Recommendations 
Our final product accomplishes our initial goals, we are able to filter our data table on multiple elements and it is visually appealing.<br/>
One drawback of the current design is that the free form input text boxes are trial and error - the user wont know what their search options are and they dont know what format the data is in (case sensitive, country codes etc).<br/>
Recommendations for further development. 
- Add dropdown filter options rather than free form
- Include more data. The current table only contains data from the first 13 days of 2010. 
- Clean up the data format. There are several fields that are in an inconsistent format. "Duration" could be filtered on if it was in a single format. Shapes could be consolidated down (disk, sphere, and circle should likely be lumped together). 