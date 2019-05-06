### Saira Gurung
#### Final Version of Findings and Visualizations from the Chicago Speed Violation data. 
The charts below illustrate trends and effects of the installation of speed camera in safety zone, which are boundaries within 1/8th of a mile around any Chicago parks or schools. In order to uncover trends, data from 3 different source were utilized. An inner join between Speed Camera Violations data and Ward Offices data on the column Ward, and a left join on the data set Ward Offices and Chicago Public Schools location data on the column Zipcode was performed to connect the datasets.

## **Chart Design Overview**

All the charts have been color coded consistently to reflect red as speeding violations and blue as the number of speed camera installed. The headings that are understandable and obvious have been removed such as, for dates or days. This reduces clutter and ensures the focus of the charts are on the main point it illustrated. Throughout the charts, I have also tried to minimize the texts and kept it concise to reflect the interpretation of the graph. This ensures readability. Lastly, I have added shadings for title, worksheet, and axis to make the charts look more organized. 

## **Visualizations and Findings**

This section will evaulate 3 different charts. The section will cover how the charts were developed, its significance, and recommendations to overcome any problems related to the significance of the chart. 

### 1. 

![](https://github.com/syragrg/Chicago-Speeding-Violation/blob/master/Visualizations/A.png?raw=true)

**Development Process:**
The dashboard is also properly aligned compared to my previous dashboard, which was created under the tiled setting as I was unaware of the functions available. The headings for the single line charts were hidden as it is obvious that the axis represents years. For the dual axis chart, the font color was changed according to color scheme. The dual axis chart was a tornado chart in the previous version of the project. In the tornado form, it was difficult to interpret the relationship between number of camera and instances of speed violation as the bars were in the same line and too much time was utilized in determining any pattern. The line chart with synchronized axis illustrates any existing relationship in a clear manner.

The columns are set to year in all 3 charts. The rows are set to number of cameras, and average speed camera. For the chart showing both the number of camera and average violation, the axis were formatted to be synchronized and an additional column of zip code filtered to reflect top 5 violation occurrence was added.

**Argument and Recommendation:**
Over the years, there have been more speed camera installed and lower record of speed violation in total. However, when broken down by zip code with the greatest number of violations, it is evident that there is an overall decline in speeding offence regardless of an increase in camera. This supports Michael Claffey’s statement that the enforcement of speed camera beginning 2013 has led to a decreasing number of violations, proving the cameras to be an effective deterrent of speeding, and a slowly improving driving behavior [1]. The city should continue using this effective method of enforcing safety on the roads and aim to expand the program from the current 1/8th of a mile radius around safety zones, to throughout the city, and not restricting the implementation of speed camera to safety zones only.

### 2.

![](https://github.com/syragrg/Chicago-Speeding-Violation/blob/master/Visualizations/B.png?raw=true)

**Development Process:**
Since only 2 attributes are used, the line chart delivers the message in the simplest and clearest manner. Again, color has been used to ensure consistency within the project. The header has been hidden as the labels for the x-axis clearly states what it is. The days axis was additionally formatted to ensure the day started from Monday instead of Sunday. This changed the shape of the line from a ‘U’ shape to a line showing clearer upward trend.
The column field was set as violation dates, formatted to show only weekdays. The row field was set as an average of violation instances. The records were filtered by violation dates from 2015-2018 where the full records are available.

**Argument and Recommendation:**
During the weekend, there are more instances of people speeding. The speed camera is enforced in the safety zone around schools only on the weekdays, thus the violations come from the speed cameras around the parks in the safety zone [2]. The enforcement period during weekends for the parks are also longer, which could be the cause of the surge in average violations during the weekend [2]. To overcome this problem, more road signs could be set up around the park area, or more attempts should be made to let drivers know that the speed camera is enforced during weekends at the specific times, as drivers may assume that the cameras are only enforced during school days, and hence not abiding by the speed rules.

### 3. 

![](https://github.com/syragrg/Chicago-Speeding-Violation/blob/master/Visualizations/C.png?raw=true)

**Development Process:**
I first tried to stack a line on top of one another on the same plane to display the trend in number of cameras installed and the number of schools in 5 different zip code, using colors to illustrate the fluctuation in the total speed violations that occurred in each zip code. The 5 zip code were filtered as having the most number of speed violations. The chart(below) was not effective and took too long to analyze and show any correlation between number of schools and camera with the total violations occurred. 

![](https://github.com/syragrg/Chicago-Speeding-Violation/blob/master/Visualizations/D.png?raw=true)

Therefore, I switched the visualization and presented the same data in a bar chart format and added years from 2015 to 2018. The year 2014 and 2019 were omitted as the records were not obtained for the full year for the two years. The correlation is more visible as the chart is easier to interpret. With the color-coding implemented, it is much easier to tell apart the trends for each zip code over the year in the bar format. The color becomes lighter towards the more recent years, thereby showing that the overall speeding violation is in the decline. Within each year, the zip code producing the highest number of violations can be determined easily by the bolder color. 

The column for this chart includes violation date formatted by year and zip code. The row field includes a distinct count of camera ID and school ID. The data is filtered to include only years 2015 to 2018 and the zip code is filtered to include only the top 5 zip code based on total violation occurring. The sum of violation is added in the shelf under marks. In addition, I have added a light border on each bar to increase visibility as the year 2017 has a very low rate of violation for the 60616 and hence the bar is white.

**Argument and Recommendation:**
The relationship is more visible, and it is evident that for each zip code with the greatest number of schools, there are more violation occurring. However, for any zip code area with most violation occurring, there are not as many cameras installed in that area as compared to other zip code region with fewer schools. 

In areas with more schools, there are more occurrences of speed violations. This would potentially mean a more hazardous traffic environment for the students. In addition, one of the factors affecting camera location is speeding. Thus, more speed camera should be implemented to enforce safety for the people in area with more schools, as well as to improve driver’s awareness of school zones and the speed limit around the area.

## **References**

## **Source of Data and Charts**
* [Chicago Public Schools Data](https://data.cityofchicago.org/Education/Chicago-Public-Schools-School-Locations-SY1819/8vyn-k2j3)
* [Ward Offices Data](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Ward-Offices/htai-wnw4)
* [Speed Camera Violation Data](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4)
* [My Tableau Public Link](https://public.tableau.com/profile/saira.gurung#!/vizhome/ChicagoSpeedViolationFindings/Morespeedcamerainstalledandlessspeedviolationinstancesovertheyears_)




