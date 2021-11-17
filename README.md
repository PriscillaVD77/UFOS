# UFOS
## Overview
In this analysis, we utilize html and JavaScript to build a dynamic webpage that allows users to shift through the information our client has provided.
### Purpose
Our new client is a data journalist who has the opportunity to write about UFOS in her hometown. Our client has a JavaScript file that is filled with sighting information. They have requested our help to display the data as a table and allow user manipulation of the data in a tidy html webpage.
### Results
In our code, in our app.js file, we were able to add a filter that allow users to sift through data using specified criteria. We used the following code:

![filter_code](resources/filter_code.png)

This code allows the page to detect when a user has entered input. When input is changed, they press enter, or switch to add a new input, the data is updated to only the data the user has filtered. <br>

![search_date](resources/search-date.png) 

This image shows that once the user begins to search in the filter, the table is updated. The user can also search mulitple criterias at once. The following image shows how users can do so with this exmample searching two or even three filters at a time. <br>

![search_two](Resources/search_two.png) 


![three_filters](Resources/three_filters.png)

Users can search using all the filters or just some of the filters and the data will be updated and changed accordingly.
### Summary:
#### Drawbacks
One drawback of this webpage is that it has very limited features. There is a lot of information to scroll through and unless the user is looking for something specific, it would be time consuming to look through each of the filters to browse. The filters are also very specific so if the user doesn't know a certain date or how a city is spelled, the user will not be able to filter for that result. <br>
#### Potential Development
One future development that I would investigate adding would be discussion boards. Especially with this type of content, it would be a great addition for users to have the option to talking about what is listed and add their own experiences. <br>
<br> 
Another development for the site would be links to possible photos or videos for each sighting. We could scrape another website that might have these available and connect it to the table. We could also create a data set with links for each image and/or video and add links to the table for each sighting. It would also be beneficial to add an option to save or favorite certain sighting in case the user wants to come back to it and forgets which filter they used to originally find the sighting.
