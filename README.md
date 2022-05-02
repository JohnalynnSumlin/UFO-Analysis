# UFO-Analysis

![7](https://user-images.githubusercontent.com/94920551/166290114-4c73c011-c164-4cd8-9581-f9420e4b7ef2.png)

## Background/Overview
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## What You're Creating
This new assignment consists of one technical analysis deliverable and a written report. You will submit the following deliverables:

* Deliverable 1: Filter UFO sightings on multiple criteria
* Deliverable 2: A written report on the UFO analysis (README.md)

### Results
Dana was able to successfully read in the Javascript data file with hundreds of UFO sightings. She wrote 3 different functions in Javascript to be able to accomplish this:
1. Build the table
2. Update the filters
3. Filter the table based on the appropriate filters

Her HTML code accomplished the following to deploy a successful site:
1. Used bootstrap for site formatting
2. Read in a css styling sheet to add background color, images, and text color
3. Read in the D3 library to be able to listen in on code and react to user input for filtering
4. Read in the Javascript file to properly build the table
5. Added HTML tags to be able to display text for the site title and summary as well as to display the table

### Summary
This webpage gives a great overview of UFO sightings in the US, but here are a few shortcommings.
* Instead of "UFO Sightings" reset link, we can add some functions which will reset page automatically. Also provide some "TOP" and "BOTTOM" functions to scroll page up and down to make it user friendly.
* It does not have the functionality to add live data.
* The data that is a part of the "data file" will stay the same unless and until someone change it.

#### Future Recommendations
One recommendation to improve our webpage would be to modify our filter textboxes to take both upper and lower case letters, as our data table lists all data in lower case (even city and state names as examples). 
Currently, if the user entered "MO" instead of "mo", nothing would be displayed in our data tables because our dataset only contains lowercase data. Therefore we could edit our code to allow the filters to take both upper and lower case letters in our filter textboxes to filter through our dataset to display the correct or appropriate data in our table.
