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
Find a dataset you can analyze for your final project (or a related topic, if you haven't yet assembled data that you need for your project or decided on a topic). Clean the data as needed, then use Pivot Tables in Excel to answer an interesting question in the data.

### Link to the original dataset

### Steps taken to clean it

### The interesting question answered and why it meets standards of newsworthiness

### The steps we took to answer it, and how we built our pivot table

### The answer to the question.



# Story research 
One of the first steps in taking on any enterprise story is seeing what's been done already.

On your own or in your group, look for any examples you can find of news reports that are similar to the story you'll be working on for your final project.

Write a summary for your editor (me) of what has already been done and -- more importantly -- what hasn't been done that you hope to tackle. For example, if you're doing a story on increasing police budgets, you might find several articles about inflated police department budgets in cities across the country, but maybe it hasn't been done in DC? Or maybe you're seeing lots of reports on budgets going up -- but you want to see where have police departments actually shrunk, and how that's affected public safety?

In your summary, include links to the stories you find on your topic.

In addition to searching for other stories that have been done on this topic, please identify at least three high-quality datasets you could use in your story (you can change your mind on these later, but this is just to get you thinking about what's out there). For each, please write why the data source is trustworthy and what (if any) limitations it might have.

Be prepared to discuss with me and the class what you find.

You only need to turn in one assignment for your group, but it would be helpful for me if everyone had a link to it in their Github repo for grading purposes. So it should work something like this:

One person in group uploads the written markdown file to Github
That person shares the URL of the file with other students
Other students in group link to that file as part of their assignment3.md
