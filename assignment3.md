# DC Crime Data Within 1 Mile of AU

[All data used for this assignment](https://github.com/shmcminn/au-datajour-fall25/blob/master/class3/dc-crimes-AU-mile.csv)

### 1.) The interesting question you answered and why it could meet standards of newsworthiness for AU's audience.

I wanted to figure out what the block where the most crime happens within a mile of AU was. I also wanted to distinguish violent from property crime. This could be newsworthy for AU's audience because, in my experience, students at AU care about safety around campus.

### 2.) The steps you took to answer it, including how you built your pivot table.

First, I added a new column to the original data labled "IS_CRIME." I then gave each row a value of 1 in the column "IS_CRIME," this allowed me to quantifiably add up all of the crimes on each block.
Then I went to build my pivot table, I used both "BLOCK" and "offense group as my rows so that I could sort all crimes into the block they happened on, as well as whether or not they were violent crimes.
I then used the column I created, "IS_CRIME," in the values section of my pivot table in order to add all crimes that happened on each block.

### 3.) The answer to the question.

#### The three blocks with the most ammount of reported property crime.

* 3700 - 3749 block of newark street nw: 70 reported property crimes

* 4500 - 4537 block of wisconsin avenue nw: 45 reported property crimes

* 4800 - 4899 block of massachusetts avenue nw: 20 reported property crimes

#### The three blocks with the most ammount of reported violent crime

* 4500 - 4537 block of wisconsin avenue nw: 2 reported violent crimes

* 4200 - 4349 block of massachusetts avenue nw: 2 reported violent crimes

* 4100 - 4199 block of wisconsin avenue nw: 1 reported violent crime




# Final project data

### [Link to the dataset](https://crimecards.dc.gov/)

### Steps taken to clean it
The data was, for the most part, clean upon downloading it. The only cleaning I did was the removal of certain columns which were not relevant. This just reduced visual clutter when looking at the data and made it easier for me to single out newsworthy data and trends.

### The interesting question answered and why it meets standards of newsworthiness
I took the number of crimes comitted in each Ward of DC and compared it with the population of each Ward, giving a proportion of crimes commited in a particular ward compared with its population. This is newsworthy because it gives people a more accurate analysis of the crime commited in different wards, rather than just say which wards commit the most crime, this proportion puts it into perspective with the population.

### The steps we took to answer it, and how we built our pivot table

I started by collecting the data, both the crime data (linked above) and the [population data](https://mchb.tvisdata.hrsa.gov/Narratives/Overview/258318d0-8dbe-46fd-9a77-385b6753e1c7). Once I had that, I was able to start asking the data questions. I added a new column to the crime data and titled it "IS_CRIME," I set the value of each row in this column to 1 so that I would be able to add the number of crimes in my pivot table. I then created my pivot table using "WARD" as my rows and the sum of "IS_CRIME" as my values. After this, I brought in the population data, matched each ward with its population, and used the function "=B4/C4" to divide the number of crimes by the population which resulted in the final proportions. Finally, I sorted each row by descending crime proportion to find the ward with the highest crime rate in comparison to its population.

### The answer to the question.

Here is an image showing the spreadsheet listed with each Ward in order of its respective "crime proportion."
<img width="394" height="178" alt="image" src="https://github.com/user-attachments/assets/886939eb-0048-4235-84f9-2f040572b686" />


# Story research 


Links:
[https://usafacts.org/answers/what-is-the-crime-rate-in-the-us/state/washington-dc/](https://usafacts.org/answers/what-is-the-crime-rate-in-the-us/state/washington-dc/)

[https://www.npr.org/sections/npr-public-editor/2025/08/21/g-s1-84193/just-how-bad-is-d-c-crime-news-coverage-fails-to-answer-the-question](https://www.npr.org/sections/npr-public-editor/2025/08/21/g-s1-84193/just-how-bad-is-d-c-crime-news-coverage-fails-to-answer-the-question)

I am coming to realize that this project may be rather difficult. Our original idea revolveed around the mapping of DC policing rather than crime. However, when looking for geographic policing data we were unable to find any (probably because MPD dosent release the locations of their officers 24/7). In terms of existing reporting on the issue, there is very little on the geography of policing in DC (likely for simillar reasons described above), however there is some reporting on the distribution of crime and crime rates througout DC. Much of this reporting is in response to the President's deployment of the National Guard. These articles also do not often mention the geographic distribution of the crime. Our project would (if we did not go down the policing road and instead focused on crime) likely overlay another map with more data to compare crime rate with another statistic.


## Three high-quality datasets you we could use in our story and why the data source is trustworthy as well as any limitations they may have.
[DC Crime Data](https://crimecards.dc.gov/)

This data is trustworthy because it is coming directly from MPD. One possible limitation could be the fact that this data only gives us crime location, if we are trying to report on policing, this may not be very helpful. 

[Ward Population](https://mchb.tvisdata.hrsa.gov/Narratives/Overview/258318d0-8dbe-46fd-9a77-385b6753e1c7)

This data is trustworthy as it is coming from the US Department of Health and Human Services. One possible limitation is the fact that the data is from 2017 and thus may not be the most accurate to the present moment.

[Voter Registration by Ward](https://cdn01.dailycaller.com/wp-content/uploads/2025/08/Data-Statistics-Report-1_2025.pdf)

This data is trustworthy because it is coming directly from the District of Columbia Board of Elections. One possible limitation of this data could be that DC is incredibly democratic and thus may not have the most nuanced data.
