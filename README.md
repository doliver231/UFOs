# UFOs

## Overview

The objective of the project was to create a website that displays a dynamic table with UFOs sightings in different parts of the United States and Canada. The page contains a form to input and filter data.

The website was created using HTML for the basic structure and Bootstrap to control the look of the site. There is also a `style.css` file that works in combination with Bootstrap to complete the decoration and feel of the website.

The site shows a table with the data of the sightings. The data comes from a file called `data.js` that contains an array with the keys of the sightings (datetime, city, state, country, shape, durationMinutes and comments). Here is a snippet the array from `data.js`:

```js
  {
    datetime: "1/7/2010",
    city: "west boylston",
    state: "ma",
    country: "us",
    shape: "light",
    durationMinutes: "approx. 1 sec.",
    comments: "Bright Florissant-green&#44 circular light arching downward with a trail of the same color.  ((NUFORC Note:  Possible meteor?  PD))"
  },
```

The page also has a form in which the visitor can input different values that are then used to filter the data of the table.

After the values of the form are entered, a Javascript file called `app.js` controls the behavior of the page.

## Resources

* Data Source: [UFO data](https://github.com/doliver231/UFOs/blob/main/static/js/data.js)

* Software/Language: HTML/CSS, JavaScript, Visual Studio Code 1.74.2, BootStrap

## Results

The following image is the storyboard for the website:

![Website Storyboard](https://github.com/doliver231/UFOs/blob/main/Images/Storyboard.png)

A user friendly webpage was created that provides UFO sighting information in a table format. This information can be filtered by date, city, state, country or shape. The table is dynamically filtered as data is entered, with the capability of accepting multiple input criteria at once. The following is our UFO webpage:

![Webpage Homepage](https://github.com/doliver231/UFOs/blob/main/Images/Webpage.png)

Here is what data is displayed when applying a DATE filter:

![Date Filter](https://github.com/doliver231/UFOs/blob/main/Images/dateFilter.png)

Here is what data is displayed when applying a CITY filter:

![City Filter](https://github.com/doliver231/UFOs/blob/main/Images/cityFilter.png)

Here is what data is displayed when applying a STATE filter:

![State Filter](https://github.com/doliver231/UFOs/blob/main/Images/stateFilter.png)

Here is what data is displayed when applying a COUNTRY filter:

![Country Filter](https://github.com/doliver231/UFOs/blob/main/Images/countryFilter.png)

Here is what data is displayed when applying a SHAPE filter:

![Shape Filter](https://github.com/doliver231/UFOs/blob/main/Images/shapeFilter.png)

Here is what data is displayed when applying a multiple filters simultaneously!:

![Multi Filter](https://github.com/doliver231/UFOs/blob/main/Images/multiFilter.png)

## Summary

Although visually appealing, the webpage has room for improvement. One drawback of this design is that it is difficult for the user to know what parameter to use for the filtering. One would have to skim through the data in the table to see what options are to choose from. The search is also case sensitive which makes it even harder to search for something specific in mind. There is also no filter reset option after each query is made. To address these drawbacks, one could provide a dropdown list instead of having to input a search criteria. The dropdown list will have all the items to search for and makes it much easier. Having a button to click to reset the filters would also be ideal, and would be located under the last filter input section. Also allowing to make data range searches would allow to make specific queries that the current webpage doesn't allow.