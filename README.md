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

![Website Storyboard]()
