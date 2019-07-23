# Boston_Crime_Data

Exploratory Analysis of the Boston Crime Dataset

Boston is Massachusetts's capital and largest city. Founded in 1630, it's one of the oldest cities in the US. In 2016, Boston was estimated to have 673,184 residents (a density of 13,841 persons/sq mi, or 5,344/km2) living in 272,481 housing units a 9% population increase over 2010. The city is the third-most densely populated large U.S. city of over half a million residents. Some 1.2 million persons may be within Boston's boundaries during work hours, and as many as 2 million during special events.

Crime incident reports are provided by Boston Police Department (BPD) to document the initial details surrounding an incident to which BPD officers respond. This is a dataset containing records from the new crime incident report system, which includes a reduced set of fields focused on capturing the type of incident as well as when and where it occurred. Records in the new system begin in June of 2015.

Question that will be answered ... 

- What are the most recorded offenses and least? 
- Which districts have the highest rate of offenses?
- Do certain districts have an tendency for paticular offenses? 
- Out of all the available years which have had the most offenses commited?
- Over the years has there been a change in offenses commited?
 - What were the highest commited offenses by year?
- Is there any day of the week that has a higher offense rate?
- Where are the offenses being commited?
 - Are certain locations more prime to specific offenses?
 

## Overview of our Boston Crime Data. 

Columns
 - Incident Number
 - Offense Code
 - Offense Code Group
 - Offense Description
 - District
 - Reporting Area
 - Shooting
 - Occured on Date
 - Year
 - Month
 - Day of Week
 - Hour
 - UCR Part
 - Street
 - Lat
 - Long
 - Location
 
There are 319,073 rows and 17 columns. 

Data Types

![](/images/dataTypes.PNG)

Heatmap of Null Values - We see that the Shooting column is mostly NaN values. Unfortunantley it is not clear if NaN represents no shooting or no information was recorded. 

![](/images/nullValueHeatMap.png)


## Exploratory Analysis of the Data Set

Count of all offenses commited.

![](/images/offenseCount.png)

![](/images/streetsOffenseCount.png)

![](/images/districtOffenseCount.png)

Offense Counts by District Based on Overall Top Ten Offenses

![](/images/offensesByDistrict.png)

Heatmap of Overall Top Ten Offenses Commited by District

![](/images/districtsOffenseHeatMap.png)


![](/images/)
![](/images/)
![](/images/)


## Citations

_https://en.wikipedia.org/wiki/Boston_

 _"Population and Housing Occupancy Status: 2010 – State – County Subdivision, 2010 Census Redistricting Data (Public Law 94-171) Summary File". United States Census Bureau. Retrieved March 23, 2011._

_https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system_
