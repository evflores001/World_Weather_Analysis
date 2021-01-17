# World_Weather_Analysis
---

## Purpose
---
The main objectives for this challenge are as follows:
- Create 2,000 random latitudes an longitudes to use with the citipy module to find the nearest city to the zipped coordinates. Using the names of these cities, an API call to Open Weather was used to match weather records with matching cities from our coordinates. Specific records were imported from the API call such as wind speed, cloudiness and max temperatures and others. These records were used to create a clean and full dataframe. The dataframe was then exported as a CSV file and used in the Vacation_Search and Vacation_Itinerary files.

- For the Vacation_Search, the user is asked to input a min and max temperature that is appealing to the user. Using these values, the loc method was invoked upon the preferred_dataframe from the previous deliverable to return a dataframe with "Max Temp" withing the values entered by the user. Using Google Places API, an API call was performed for each city in the preferred_dataframe to find the closest hotels to each city. Finally, a marker_layer was created to place markers on each coordinate in our dataframe.

- The final deliverable was to create a directions layer map using Google's direction_layer. Four destinations were selected and a driving direction_layer was placed connecting the selected cities.  
