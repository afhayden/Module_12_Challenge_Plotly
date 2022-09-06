# Module 11 Challenge JavaScript
## Overview of Project
Using UFO sightings data, a dyanmic webpage was created to display user-filtered data. Users can filter data by date, city, state, country, and shape.

## Results
Users can search by more than one filter. Below are examples of each filter. Users do not need to press a button to complete the search request. Upon changing the data in the text box, the search process will be launched.

### Filter by Date
Users can filter the table of data by entering a date using mm/dd/yyyy format. Single digits cannot have a zero prefix such as '01'. This would apply to both the month and day.

![Example of Search by Date](static/images/datetime_search.png)

### Filter by City

![Example of Search by City](static/images/city_search.png)

### Filter by State

![Example of Search by State](static/images/state_search.png)

### Filter by Country

![Example of Search by Country](static/images/country_search.png)

### Filter by Shape

![Example of Search by Shape](static/images/shape_search.png)

### Filter by Multiple Criteria
Users may search by multiple values. Here is an example of searching by both the City and Shape.

![Example of Search by Multiple Cirteria](static/images/multiple_search.png)

## Summary
The use of textboxes for the input may introduce erroneous data or causes users to search for data that is not within the dataset. For some if not all of these textboxes, dropdown listboxes can be used to help let the users know what data is available. A dropdown listbox for states, countries, and shapes should be used. The textbox for the date should have a date mask to force users to use a specifc date format. The current filtering function is case senstitive. If a user were to search for "CA" for the state instead of "ca", data would not be returned. In place of dropdown listboxes, a new function was added to force Lower Case for all non-date textboxes upon keyup. 

## Resources
- Data Source: data.js
- Software: HTML, Javascript, Bootstrap 4.0.0 Styling
