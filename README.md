# UFOs using Javascript and HTML
### Website link - https://akshaya-kamble.github.io/UFOs/

## Overview of the project
In this project we are helping Dana to build a website using javascript and HTML to allow users to filter multiple criteria at the same time. We will       have the filter criterias as date, city, state, country and shape.We will also use Bootstrap elements to enhance the appearence of the website.

## Results
To build the website we use HTML and to add functionality to the filters on the website we use Javascript.We also use Bootstrap 3 elements for enhancing the asthetic looks of the website.In the Javascript we create two functions, the first function named updateFilters() saves the element, value, and id of the filter that was changed. The second function named filterTable() will loop through the dataset and keep only the results that match the search criteria.The webpage will be updated with the search criteria after pressing "Enter". The filter is also capabale to hold the filters selected so that the search can be narrowed down.Below images can be refered how the filters work.

### 1. The Date filter
    By typing the date in the input field we can have the data filterd as per the selected date.Multiple criterias can be added too after the date is selected. 
    The image shows data selected with the date "1/1/2010".
   [Image for selected date][1]

### 2. The City filter
    By typing the name of the city in the input field we can have the data filterd as per the selected city.We can again select multiple criterias after the city is selected     and depending on the second criteria the data will be filtered and displayed.
    Since the data is already filtered with the date "1/1/2010" we can now filter a city "el cajon" from this list. The image shows data filtered with date and city.
   [Image for selected city][2]  

### 3. The State filter
    By typing the state in the input field we can have the data filterd as per the selected state.Multiple criterias can be added too after the state is selected.
    The image shows data filtered with selected state "ma"
   [Image for selected state][3]

### 4. The Country filter
    By typing the country in the input field we can have the data filterd as per the selected country.Multiple criterias can be added too after the country is selected.
    The image shows data filtered with selected country "us"
   [Image for selected country][4]

### 5. The Shape filter
    By typing the shape in the input field we can have the data filterd as per the selected shape.Multiple criterias can be added too after the shape is selected.
    The image is filtered on date "1/1/2010 ,city "el cajon" and shape "triangle"
   [Image for selected shape][5]



## Summary
Building website can have drawbacks depending on the data it loads and how we would like the data to look.Below points mention the drawbacks that were captured in the project and also some recomendations for further development.

### A. Drawback of this website

#### 1. If the data that we type in the filter does not exist in our database the website will not display anything. So building a dropdown list for selection of available           options or an error message saying "data not available for selected criteria" can help.

#### 2. The data is case sensitive so it does not allow to filter if anything is not written in the same case as the data.

### B. Recommendation for further development.

#### 1. Pagination can be added as this can help display in an organized format when the filtered data is very long.

#### 2. Clear button can be added to clear all the selected fields in order to start with a new search.

#### 3. A reference website link can be provided from where the data was collected in order to make the website authentic with facts.

#### 4. The above mentioned drawbacks can also be rectified and incorporated by using the dropdown list and error message display.

[1]:https://github.com/Akshaya-Kamble/UFOs/blob/main/Challenge/Reference%20images/Date.PNG
[2]:https://github.com/Akshaya-Kamble/UFOs/blob/main/Challenge/Reference%20images/City.PNG
[3]:https://github.com/Akshaya-Kamble/UFOs/blob/main/Challenge/Reference%20images/State.PNG
[4]:https://github.com/Akshaya-Kamble/UFOs/blob/main/Challenge/Reference%20images/Country.PNG
[5]:https://github.com/Akshaya-Kamble/UFOs/blob/main/Challenge/Reference%20images/Shape.PNG
