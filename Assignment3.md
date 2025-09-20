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
