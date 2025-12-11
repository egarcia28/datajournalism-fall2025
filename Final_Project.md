
## The pitch:

This story would incorporate two primary data sources. First, the general DC crime data can be found at the [DC crime cards](https://crimecards.dc.gov/). We would also use [police station employment data](https://mpdc.dc.gov/sites/default/files/dc/sites/mpdc/page_content/attachments/Staffing_Report_SEPTEMBER_2025.pdf). 
We would then use this data to prove which police service areas (PSAs) and which police districts are overstaffed versus understaffed in relation to violent crime. 
We have created one data visualization analyzing the staffing in each PSA, as well as a district map that displays all violent crime in relation to the size and location of all police stations.

## The steps used to analyze the data:

The steps we took to analyze this data were fairly simple. The first and main thing we had to do was clean the data that we found. 
This included taking the staffing reports and putting them into an Excel sheet first. Then, we took the crime type and PSA columns and put them into a different sheet in the same workbook. 
Finally, we conducted a v-lookup function to match each crime to its PSA. After that, we uploaded the data to Datawrapper to see if there was any correlation between our two variables.

For the map, we expanded the scope of our analysis to the larger districts, placing each crime in its respective district and matching each police station's location.

## Proposed nut graf

Data from the D.C government website shows that PSAs within two districts, three and five, do not have staff proportionate to the amount of crime in their respective areas. 
PSAs in district three, which serves central urban parts of the city such as DuPont Circle, have less staff on average for each crime committed in the district. 
PSAs in district five, on the other hand, lying in the northeast quadrant of the district, have more police staff on average for each crime committed. 
Expanding the data analysis to the larger police districts rather than PSAs, we see a different story unfold where district 2 is significanly overstaffed and district 7 is relatively understaffed.

## The data sources

[Staffing Reports from dc.gov as of Sept. 2025](https://mpdc.dc.gov/sites/default/files/dc/sites/mpdc/page_content/attachments/Staffing_Report_SEPTEMBER_2025.pdf)

[Data on exact crimes on dc.gov from 01/01/2021-09/09/2025](https://crimecards.dc.gov/all:crimes/all:weapons/dated::01012021:09092025/citywide:heat)

[Police districts vector map](https://catalog.data.gov/dataset/police-districts-7bcfc)


## Plans for how we would report and structure this story if given more time

If we were to be given more time for this story, we would first reach out to the different districts to see if we could get any information regarding how they staff their respective districts. 
We would also question how each officer gets placed in a specific PSA and, mainly, how the amount of crime in a district impacts how many officers are staffed in the area.

The main thing with our data is that we have barely scratched the surface with it. This data includes variables such as time, block, voting precinct, and more. 
We have chosen our story specifically to involve staffing and the amount of crime; however, this data could yield several other stories if we were given more time to continue digging through it.

Expanding our analysis to other data sets, we would be able also be able to compare how over and under staffing of police correlates with demographic factors such as race and economic status. 

## Two data visualizations:

The first data visualization we did was a scatterplot using the data in the snapshot above. The goal was to see the trend of police staff versus crimes, and how each PSA fell onto the trendline. 
For this, we used Datawrapper and had some notable findings. First off, police district 3 generally has fewer staff than the trendline, implying an understaffed district, although it does not prove it. 
On the other hand, District 5, on average, is much more staffed than the average. Neither of these directly implicate one district performing better or worse than the other; however, it gives us a strong direction when writing the story.

[LINK TO GRAPH](https://github.com/Smemon1313/datajournalism-fall2025/blob/main/ECAssignment1.md)

The second data visualization that we did was a map that showed where violent crimes were happening in the city while also showing the location and staffing of each police station. 
This map helped put the data from the previous scatterplot into perspective. I created this map by first referencing the crime cards data, I then cleaned variables other than the latitude, longitude, violent vs property crime, sorted by violent crime and created a new csv layer in QGIS with this data. 
I then imported the vector map of the DC police districts. The final layer was the locations of DC police stations. 
I then scaled the size of the station symbols according to the number of officers employed there. This map also allows us to expand our analysis from the individual Police Service Areas (PSAs) to the districts as a whole.

[LINK TO MAP](https://github.com/egarcia28/datajournalism-fall2025/blob/main/FINAL.jpg)

## Table
In order to supplement both of our data visualizations we also created a table with the raw data. This table allows the reader to compare staffed officers with violent crime in each district. 
This table does a simillar analysis to our first data visualisation; however, it expands the analysis to each district in its entirety rather than just the PSAs. 
This table shows how the conclusion can change when we change the scope of our analysis. The table shows district 2 as overstaffed, and district 7 as understaffed.

[LINK TO TABLE](https://datawrapper.dwcdn.net/5SxNL/1/)
