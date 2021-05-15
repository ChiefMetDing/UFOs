# UFOs
Data analytics M11

## Overview of Project
The purpose of the project is to create a webpage that is capable of displaying existing historical UFO sighting records. The users of the webpage are able to filter the displayed records by changing:

-	Date
-	Location information including city, state and country
-	Shape of the UFO

## Results
Once the webpage is opened, all available historical UFO sighting records are displayed. To narrow the results displayed, the users can use the filter panel on the left side of the page, where the users can filter the table by specifying date, city, state, country and shape of the UFOs.

Before the users input any specifications, the panel (_figure 1_) shows example of input data format. This guides the users to type in data in the right format.

![default_filter_panel](https://user-images.githubusercontent.com/78275082/118370750-2b78ba00-b577-11eb-8f7a-e4ed2fd1531e.png)

(_figure 1: default filter panel_)

After the user has finished the input by either pressing “enter” or “tab” or clicking elsewhere on the page, the data table will be filtered. New displayed data matches the specifications that the user has entered (_figure 2_).

![filter_panel](https://user-images.githubusercontent.com/78275082/118370766-3a5f6c80-b577-11eb-84d1-ddd0d0068c99.png)

(_figure 2: filter panel and record display_)

The user can move to the next filter category and make the filter more specific. The new filter will be applied to the top of previous filtering.

To display the entire available sighting data, the user need to reload the webpage.

## Summary
The main drawback of the webpage is that the filter does not allow the use to cancel filters that have been applied. Once a filter is applied on the table, the user can only change the criteria but not remove the filter.

For further development, there are two recommendations listed below:

-	Bring back the “filter” button. This way, users can type in multiple filter criteria without changing the display and applied the filters all at once.
-	Create cancel button for each filter category. This way, users can easily remove a filter without reloading the entire webpage and filtering again.
