#### Saira Gurung
##### Explaination of visualizations created

The charts below illustrate trends and effects of the installation of speed camera in safety zone, which are boundaries within 1/8th of a mile around any Chicago parks or schools. In order to uncover trends, data from 3 different source were utilized. An inner join between Speed Camera Violations data and Ward Offices data on the column Ward, and a left join on the data set Ward Offices and Chicago Public Schools location data on the column Zipcode was performed to connect the datasets.


### Chart 1

![ ](https://github.com/syragrg/IndividualProject/blob/master/Visualizations/1..png?raw=true)

A line chart was approriate in this instance which illustrates that there is an overall trend of an increase in the number of cameras being installed from years 2014-2019. 

### Chart 2

![](https://github.com/syragrg/IndividualProject/blob/master/Visualizations/2..png?raw=true)

### Chart 3

![](https://github.com/syragrg/IndividualProject/blob/master/Visualizations/4..png?raw=true)


When we plot the graph for average violations for every zip code we must consider the number of cameras in that specific zip code, we can observe that the top five zip codes with highest number of cameras have lower average violations, this suggests that a greater number of speed cameras in any area would reduce the number of speed violations. 

Thus to determine the number of areas where we need to install more speed cams we’ll have to look at the areas with high avg violations.


Data used

* [Chicago Public Schools Data](https://data.cityofchicago.org/Education/Chicago-Public-Schools-School-Locations-SY1819/8vyn-k2j3)
* [Ward Offices Data](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Ward-Offices/htai-wnw4)
* [Speed Camera Violation Data](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4)
