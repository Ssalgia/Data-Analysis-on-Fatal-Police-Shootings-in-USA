# Fatal Shootings Data from Washington Post Survey

The Washington Post's database contains records of every fatal shooting in the United States by a police officer in the line of duty since Jan. 1, 2015.


This data includes  the race of the deaths,  the different scenarios in which the shoots took place, if or not the person was armed  or faced a mental-health crisis.

The Post’s database is updated regularly as fatal shootings are reported.

## About the data

The file `fatal-police-shootings-data.csv` contains data about each fatal shooting in CSV format. The data contains approximately 7.2k rows and 17 features, out of which not all of them are used in the analysis. The file can be [downloaded at this URL](https://raw.githubusercontent.com/washingtonpost/data-police-shootings/master/fatal-police-shootings-data.csv). Each row has the following variables:

`id`: a unique identifier for each victim

 The `threat column` and the `fleeing column` are not necessarily related.

`body_camera`: News reports have indicated an officer was wearing a body camera and it may have recorded some portion of the incident.

`latitude` and `longitude`: the location of the shooting expressed as WGS84 coordinates, geocoded from addresses. The coordinates are rounded to 3 decimal places, meaning they have a precision of about 80-100 meters within the contiguous U.S.

`is_geocoding_exact`: reflects the accuracy of the coordinates. `true` means that the coordinates are for the location of the shooting (within approximately 100 meters), while `false` means that coordinates are for the centroid of a larger region, such as the city or county where the shooting happened.

The other columns include 'name', 'age' , 'Gender', 'Race', 'City', 'State', 'armed', 'signs of mental illness' and a few others. 
