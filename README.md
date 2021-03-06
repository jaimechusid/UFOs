# UFOs

## Overview of Project
In this project, I was given a UFO sightings data set in the form of a JavaScript array, and was tasked with assisting Dana in creating a visually appealing webpage consisting of this data. The webpage was to include a header, an article about UFOs, and a table containing the JavaScript data, where users could filter results by date, city, state, country, or shape. To create this webpage, I utilized JavaScript, CSS, HTML, and Bootstrap components.

## Results

### Navigating Through the Web Page
When you first open the webpage, you will see a title, a header with an image of space in the background, and an article. The title of the article is on the right, and the article itself is on the left. This article is a brief introduction to the potential that aliens do exist, and that they are trying to contact us humans here on Earth. Below the article is the table that consists of UFO sightings, including when and where they took place, the shape of what was seen, the duration, and any comments. On the left of the article is a series of filters that can be used to narrow the user's search.

### Filtering the Data
There are multiple criteria off which users can filter the UFO sightings: date, city, state, country, and shape. Users can filter by as little or as many criteria as they wish. To use the filters, users can just type what they want to filter by in the corresponding field, making sure that it follows the format shown, and press enter to filter the data. If a user filters by one criteria first and wants to narrow the search further, their filter will remain in place and they can add others. Additionally, to clear any filter users can just delete what they typed, emptying the text box, and press enter. I've walked through an example of filtering by several criteria below:
- Before any filters are applied:
- ![All data](all_data.png)
- Filtered by only date:
- ![Date](date.png)
- Filtered by date and state:
- ![State](state.png)
- Filtered by date, state, and shape:
- ![Shape](shape.png)

## Summary

### Drawbacks
One drawback of this new design may be the lack of a filter button. While it seems rather self-explanatory for some, users may be confused what they are supposed to do once they type in the data they would like to filter. The same applies to clearing the filters. 

### Recommendations
The first recommendation is to add buttons for "Apply Filters" and "Clear Filters" to improve clarity and user experience. These buttons would make it a lot easier for a new user to figure out what they are supposed to be doing. The second recommendation would be to change the filters from textbox form to drop down menus to prevent users from messing up the formatting or selecting criteria that doesn't exist. This would also improve ease of use of the filter component.


