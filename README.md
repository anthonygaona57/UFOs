# UFOs

Project Overview
All of the analysis in the world, no matter how accurate or sophisticated, is useless if it cannot be communicated. Data visualizations allow us to tell a story with data in a way that is clear, accessible, and cohesive. Visualizations allow even those with limited data fluency to interpret data.

JavaScript is a well-established coding language designed to improve webpages by enhancing the user experience. Javascript enhances websites by providing front-end functionality, customization, dashboards (such as maps or graphs), and allows for user input to create dynamic web pages. Javascript enables websites to be visually appealing and interactive.

In this repository, we will use Javascript to create a table that organizes UFO data that is stored as a JavaScript array, or list. This table will have the ability to filter data based on certain criteria and will be created using JavaScript as the primary coding language.

Coding Goals
Build and deploy JavaScript functions, including built-in functions.
Convert JavaScript functions to arrow functions.
Build and deploy forEach (JavaScript for loop).
Create, populate, and dynamically filter a table using JavaScript and HTML (convert a Javascript array into an HTML Table)
Project Deliverables
Deliverable 1: Filter UFO sightings on multiple criteria
Deliverable 2: A written report on the UFO analysis (README.md)
Results
The webpage created is a fairly user-friendly display of ufo sighting data with a filter table that allows users to easily filter on various criteria such as date, city, state, and shape of the UFO sighting. A global unfiltered view can be seen below.
The displayed results are dynamically filtered as you update the form field entries. There is no needed Submit or Refresh button as the tables update in real time. Filter selection can be broad such as only selecting a country and state like the United States, California.

Summary
Our current webpage has one main advantage in that users can search upon multiple criteria at one time and there is no submit button needed. However, there are also some drawbacks. The main draw backs all have to do with the fact that the search options don't provide much idea as to available options to search on. The current fields are all text boxes and these can allow for a lot of user errors or just simply misinterpretation. This makes the data analysis ineffective and time consuming.

Drawbacks

The filter method is case sensitive. Therefore if a user entered any items in upper case, the search results would not return properly. For example, if the user entered a city as "Ventura" instead of "ventura", the city would not return in the filtered data.
The user may not know exactly what period the data is from, so the user might type in dates that we don't have data for. For the date filter, the user should be able to click through a calendar.
The same issue with the Shape field, without knowing what the shape options are, the user will not know what terms to search for.
Recommendations for further development:

Remove case-sensitivity in all the textbox search fields.
Add a calendar selection option instead of textbox field for the Date search.
Add a drop down menu for the Shape field. This would be more user friendly as a drop down option than the textbox.
The text in the Comments section should be parsed and cleaned as there are strange symbols that can appear. These should be eliminated to make reading the comments more user-friendly.
