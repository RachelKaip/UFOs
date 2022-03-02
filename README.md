# UFO Sightings 
## Overview 
In this assingment, we built and designed a webpage with JavaScript, HTML, and Bootstrap that holds a dynamic table that allows users to filter through hundreds of reports of UFO sightings.  

We started building this page with a basic HTML template in the index.html file and added a navigation bar, jumbotron header, and two rows to hold the opening paragraph, the table and its filters.  Then, with our data in a js file (data.js), we created app.js and began writing funtions to build the table, update the filters, and fianlly, loop through the filters inputted by the user and display the requested information.   

## Results
##### How to Use the Application 
Need information on UFO sightings fast?  This easy to use table is just what you need!  

After reading the opening paragraph, scroll down to the table- you'll notice you can scroll inifinitely through *hundreds* of UFO sightings.  If you have an idea of what sighting you're looking, the filters on the left hand side will be your friend!

![basic table](https://user-images.githubusercontent.com/94569240/156275726-612c2511-ad01-410b-bcd6-3f3b8f96c0aa.PNG)

Under "Filter Search," use the placeholder prompts to guide your entries as you narrow down your search by any of the following:
- date
- city
- state
- country
- shape

![filters](https://user-images.githubusercontent.com/94569240/156275752-569e0486-8ad2-4678-a482-e897ef8778c6.PNG)

You do not need to use all the filter options- as you'll see below, you can filter by one, or any combination, of the filter- the table will automatically adjust!

![city-filter](https://user-images.githubusercontent.com/94569240/156275770-009673a8-a912-4f00-9c0a-d8ac2c54d8f9.PNG)

--

![date-state-filter](https://user-images.githubusercontent.com/94569240/156275792-91edc6df-190d-499e-936b-53ba84cf47b8.PNG)

Want to clear your filters?  Just clear the search criteria and the table will automatically adjust itself back as well.    

## Summary

Overall, the creation of this webpage was successful and will undoubtedly keep UFologigsts busy for hours.  

However, one drawback of the finished product is that the filters are case-sensitive  Thus, users must input everything in lowercase form in order to get the results their want.  One reccomendation I have for if someone is to develop this application further is to add a dropdown list with options for each filter.  You can do this by adding a **datalist** html element within your li elements- this will allow you to keep the free-form text box but also have the ability to see all your filter options. This will aid our users by giving more insight into what they can search for and how to search for it.  

If someone is to continue developing this site, I also reccomend complimenting the dark background in the body with lighter backgrounds on components like the filter list and table elements in the index.html file.  This will help make our table and filters pop agianst the dark background and showcase the striped effect of the table.


