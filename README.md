# UFOs

## Overview 
### Background
Dana has provided data surrounding UFO sightings in a JavaScript array.  With this, a webpage with a dynamic table was built where users were able to filter the data by date.  Dana is now looking to provide users to filter using multiple criteria at the same time.  She believes this will help provide a more in-depth analysis for them and wishes to use city, state, country, and shape as the additional filters.  

### Resources
-Data Source: [data.js](https://github.com/Bulzeye89/UFOs/blob/main/Static/js/data.js)<br>
-Software: Visual Studio Code version 1.68.1, Javascript, HTML

## Results
The website is up and running and the additional filters have been added.  We have removed the "filter" button and users will see placeholders in the five different fields that can be used to analyze the data.  
<p float="left">
<img src="https://github.com/Bulzeye89/UFOs/blob/main/Resources/UFO_readme_pic1.png" 
</p>  
Users will be able to type in one of the fields and press enter, which will prompt the data table to update.  From here users, can further filter the results by typing into the four remaining fields.  If they wish to remove a filter, they can simply delete the input and press enter.  Below is an example of a search by filtering the state as "fl" and the shape as "fireball"
<p float="left">
<img src="https://github.com/Bulzeye89/UFOs/blob/main/Resources/UFOreadme_pic2.png" 
</p>
Here is another example where the data table is filtered with the state as "ca" and the date as "1/4/2010"
<p float="left">
<img src="https://github.com/Bulzeye89/UFOs/blob/main/Resources/UFOreadme_pic3.png" 
</p>   

## Summary: 
### Drawbacks
While the website is functional and can filter the data successfully, it does have some drawbacks.
  1. The filter inputs are not the most intuitive.  It assumes users will know that the inputs are case sensitive and need to be put in all lower case and in the exact format of values of data in the table.  Some users may capitalize in the fields of city, state, and country as these are proper nouns.  Also, they may try spelling these inputs out fully instead of using the abbreviation.  
  2.  The data set is fairly limited in both timeframe and locations.  Currently, it only contains sightings from 1/1/2010 to 1/13/2010 in the United States and Canada.  
  
### Recommendations
Some recommendations to improve the sight going forward and overcome the above limitations are:
  1. The input fields/filters could be made less stringent using an autofill option as a user types or perhaps the input fields could be changed to drop down menus instead.  
  2. It would be a great addition to pull data from a global live source so that the data table is continuously updated and current as well as not limited to just the two countries.  
  
