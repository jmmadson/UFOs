# UFOs

## Overview of Project: 

The purpose of this project was for me to help Data Journalist, Dana, write about Unidentified Flying Object (UFO) sightings. Her hometown of McMinnville, Oregon is well known for sightings of UFOs so she wants to share this information with the data science world. She has a JavaScript file full of sighting information from all around the world. She wants to display that information in a filterable table to allow users to find specific information about sightings based on Country, State, City, Shape and Occurrence date. 

## Results:

When someone comes to the page we've built together, there are few things they can do. Initially they can learn why the page exists. 
Dana has written an insightful summary with information from a Ufologist to introduce the site visitors to some philosophical questions about extraterrestrial life and the information of sightings they can filter through.

That information can be seen above the table in the screenshot below: 
![Website Screenshot](https://github.com/jmmadson/UFOs/blob/main/static/images/web_screenshot.png?raw=true)

When they are ready to search for existing information, visitors can use the filtering form we've set up on the left-hand side of the page as highlighted in the image below.

![Filter Options](https://github.com/jmmadson/UFOs/blob/main/static/images/Filters.png?raw=true)

<h3>How to Filter UFO Sighting Data</h3>
<ol>
<li>Enter the requested information in the form fields (as shown above) that they would like to filter on</li>
<li>Hit Enter or Tab on the keyboard to see filtering based on that first input</li>
<li>Enter additional filtering information in any of the other fields (Date, City, State, Country and/or Shape)</li>
<li>Hit Enter or Tab on the keyboard after each filter input</li>
<li>Your filtered data will display after each input.</li>
</ol>

The following screenshot shows an example of filtering by date and country and the results that appear. 

![Filter by Date and Country](https://github.com/jmmadson/UFOs/blob/main/static/images/Filtered%20Results.png?raw=true)

To clear the table, either click "UFO Sightings" in the upper left-hand corner of the site, or simply clear all the fields

## Summary: 

The filters we've created allow users to manipulate and make sense of a lot of data, in manageable filtered subsets. There are however some drawbacks to the way it was designed in that it is not explicitly laid out how to use the filtering tool. Additionally as the filter is case senstive, you may finds yourself getting zero results if you for example, capitalize the Country. 

Some additional updates we could make to this tool to improve the functionality and user experience include: 
<ul>
<li>Directions: As it exists, there are no instructions for how to use the filtering on the page. While it is pretty self-evident - some simple written instructions regarding using multiple filters and how to clear the filters would make it a more user friendly experience.</li>
<li>Clear Search: We could add a Clear Filters button to clear out the filters so that a user doesn't have to erase all of their inputs or know that clicking on the "UFO Sightings" headline clears the data</li>
<li>Better filtering using RegEx: right now the search is an exact match, so if a user uses a capital letter for US, they will get no results. We can use regular expressions to better validate the user input and return like results.</li>
<li>Save or Share: Right now, the user can filter the data, but not save or share without manually copying it out of the page. We could modify the app create custom URls with the filtered search to allow for easy digital sharing and/or allow users to download a csv of filtered data for the same purpose.</li>
</ul>
