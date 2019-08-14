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

Count of the 67 various offenses recorded in the Boston Crime Data Set. 

![](/images/offenseCount.png)

![](/images/streetsOffenseCount.png)

Washington Street ranks highest in offense rates, with Blue Hill Ave and Boylston Street making up the top three streets with the highest offenses. 

Washington Street is a street originating in downtown Boston, Massachusetts that extends southwestward to the Massachusetts–Rhode Island state line. The majority of it was built as the Norfolk and Bristol Turnpike in the early 19th century. It is the longest street in Boston, and it remains one of the longest streets in the state of Massachusetts.

Washington Streets history is similar to Colfax Ave in Denver, Colorado, Colfax was once one of two principal highways serving Denver. Today Colfax is under rejunivation but has seen its days of high offenses rates similar to Washington street in boston. 


![](/images/districtOffenseCount.png)

District B2 and D4 are in the top three and conicendently Washington Street crosses through both these districts. 

Offense Counts by District Based on Overall Top Ten Offenses

![](/images/offensesByDistrict.png)


![](/images/districtsOffenseHeatMap.png)

There are four districts with distinct offenses being commited. D4 with 7,313 Larceny offenses, B2 with 6,407 Motor Vehicle Acidents, C11 with 5,305 Motor Vehicle Acidents, and A1 with 4,704 Larceny offenses. Not surprisingly these districts are also in the top four highest offenses areas. 

![](/images/offenseByWeekdayHeatmap.png)

Motor Vehicle Accident Response take the majority of calls each day of the week, peaking on Friday at 5,852 offenses commited. Larceny is the second most offenses commited through out the week also peaking on Friday at 3,959 offenses. 

![](/images/crimesByyear.png)

Our data starts on 2015-06-15 00:00:00 and ends on 2018-09-03 21:25:00, we are missing almost the first half of 2015 and last quarter of 2018. Due to this we will not have an accurate view of overall crime rates over the years, however it will still be possible to analyze the data on a monthly and daily basis.


![](/images/topTenbyYear.png)

Top offenses over the years is no suprise and corellates with the top offenses observed earlier. 

![](/images/crimeratesTimeSeries.png)

It is evident that in the colder months (January-March) there is a significant drop in offenses, and (June-August) seeing a peak in offenses commited. 

![](/images/topTenOffensesTimeSeries.png)


![](/images/)
![](/images/)


## Citations

_https://en.wikipedia.org/wiki/Boston_

 _"Population and Housing Occupancy Status: 2010 – State – County Subdivision, 2010 Census Redistricting Data (Public Law 94-171) Summary File". United States Census Bureau. Retrieved March 23, 2011._

_https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system_

_https://en.wikipedia.org/wiki/Washington_Street_(Boston)#cite_note-1_
