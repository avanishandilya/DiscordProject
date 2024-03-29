
# Discord Project
Discord is a messaging app that people use to connect with each other. It has grown in popularity over the years (Source 1). Personally, I have been a part of that growth in the past couple of years. It interested me that around the same time the pandemic started, more and more people were joining Discord.  

I became interested in the trends of Discord servers. It was very interesting to see patterns as time goes on. Therefore, I decided to create my own dataset and analyze the data with Python and Pandas.

## Goals of the Project
The goal of the project was to do an exploratory analysis. Additionally, gain new skills in data analysis.
A more personal goal was to see the interactions of people and find noticeable trends in interactions as time goes on.

## Plan for the Project
The general plan of the project was:
1. Find a question to answer
2. Collect Data
3. Demonstrate skills
4. Analyze the data
5. Answer the Question

## Question for the Project
Although there weren't any specific groups of people I wasn't giving an answer to, my main question was:

What noticeable trends are there in this group and how come they occur?

## Overview of the Data
For this study, I chose a close friends Discord Server. There are approximately 30 people in the server and there a few key demographics about the server that feels relevant to this project.

### The Demographics
1. The age group of this server is all around 19 - 21
2. Most of the group was in college in 2021
3. A few of the members were Discord bots
4. Most members are based in the United States


### Data Collection
I collected the data manually from 22 people, about 73% of the server.

The manner in which I collected the data is as follows:

1. I made an Excel sheet that listed 22 people in random order.
2. Using the Discord search bar, I used the before and after search filters to search by year and person for every year from the start of the server until 2023.
3. I put the information into the respective row in Excel.
4. Once I had found the number of messages for everyone, I then sorted the sheet from the greatest number of messages
5.  I made a copy of this Excel sheet because, for the first Excel sheet, I anonymized everyone by simply putting "Person 1, Person 2..." and so on until "Person 22".  The second Excel sheet is to keep track of the names so if I ever want to change the dataset, then I can easily and accurately update the information.


### Pros of the Data
1. Since I was able to double-check the numbers, I verified that the data was accurate.
2. The Excel sheet was created by me, so I was able to make it more useful to me.
3. Additionally, the data did not need much cleaning since I created the dataset.

### Cons of the Data
1. It is a very small dataset, so it does not represent all of the Discord population.
2. Since I was able to create the dataset, it did not provide much practice for data cleaning. Therefore, demonstration of that skill is limited.
3. It was a very time-consuming and inefficient way of collecting the data.


## Processing the Data
As already noted, data cleaning was not required. Before the processing of the data, here is an image of what the data looked like in Excel.

The year 2023 has been updated on June 11th, 2023 at 1:30 PM.

![Data in Excel](/NewGraphs/ExcelData.PNG)

I did not do much to the data once I loaded it into my Jupyter Notebook. I converted it into a DataFrame. Here are the first few rows of the DataFrame.

![DataFrame of Data](/NewGraphs/DataFrame.PNG)


### Finding Averages

First, I found the averages for each year from 2018 to 2023. To work with different types of objects, I created a Pandas series for each year. Once I found the averages for each year, I was able to graph the information to provide some overview of the messaging trends.
Additionally, in a second graph, I graphed each person's messages through the years, with the data points overlapping each other. From this graph, I was able to tell that the second graph seemed to mostly follow the trend of the overall average graph.

#### Overall Trend of Messages on the Discord Server
![Overall Trend of Messages of the Discord Server](/NewGraphs/OverallTrend.png)

#### Everyone's Messages Graphed Through the Years for Comparison
![Everyone's Messages Graphed Through the Years for Comparison](/NewGraphs/AllPeople.png)

# Analysis of the Data

## Overall Trends in the Data
From the graphs above, the data starts in 2018. Since no data could be found prior to 2018, a strong conclusion is that the Discord server was created during 2018. The low number suggests that it might have been created in late 2018 since there could only be a short amount of time to send messages until 2019.

Furthermore, the graphs demonstrate spikes during 2020. The COVID-19 Pandemic first hit the United States in January 2020 and continued raging in March 2020 (Source 2). Many people were forced to do school or work from home, leading to an increase in online activity (Source 3). Since people had to stay away from one another, many turned to social media to keep in touch. During 2020, the increase in messages in this Discord server suggests that the members decided to use Discord as a means of keeping in touch with one another. Thus, the pandemic contributed to the members messaging more during this year.

As mentioned earlier, one of the main demographics of this group is that many of them started college in 2021. The graphs display a drop in messages in 2021. Starting college may have led to a drop in messages sent due to transitioning to a new place and taking on a new kind of course load. Additionally, the members may have been reaching out to new friends to create a college social life.

As time goes on, the average number of messages per year keeps decreasing. One reason for this is that since social distancing was reducing, people met up more and did not find the need to text as much. Additionally, this Discord server was made while most members were in high school. Research shows that friends tend to grow apart in college due to physical separation, academic work, and new friendships (Source 4). As college goes on, the members are physically separated for most of the year. As a result of the separation and the academic work, members might find it harder to find time to stay connected to each other during college.

## Individual Trends in the Data
When graphing the data to find trends, it was interesting to look at individuals and see what the graph might say about them.

Some graphs displayed 0 messages sent for several years before a sudden uptick in messages, like the ones below. This indicates that some people did not join the server at the very start and that the year that has the uptick marks the year that they joined the server.

### Example 1 of a Person Joining the Server Later
![Example 1 of a Person Joining the Server Later](/NewGraphs/Person9.png)

### Example 2 of a Person Joining the Server Later
![Example 2 of a Person Joining the Server Later](/NewGraphs/Person16.png)


Though there were some trends, some graphs did not indicate a uniform trend or explanations for the way the line looked. This could be due to people inherently not being social or simply not looking at Discord.

### Example 1 of a Person with no Trend
![Example 1 of a Person with no Trend](/NewGraphs/Person22.png)

### Example 2 of a Person with no Trend
![Example 2 of a Person with no Trend](/NewGraphs/Person10.png)


# Answering the Question

## The Question
Earlier, my proposed, simple question was: What noticeable trends are there in this group and how come they occur?

### The Answer to the Question
A lot of trends pointed to years with more messages than others. A large part of the upward trend was due to COVID-19.

After the COVID year, there was a downward trend. There were several factors to this. Two main ones being college and a decrease in COVID-19.

# Conclusions
Through this exploratory analysis project, I found some trends in this specific Discord group. Since the data was so specific, it cannot be generalized to the population that uses Discord regularly. I found that I was able to work with DataFrames and Matplotlib to achieve my goals of exploring a small dataset.

# Sources
In this report, I do have information that could not be easily known or that would need evidence. As such, I have found sources to help back my claims.


1. Source 1: https://discord.com/safety/360044149331-what-is-discord

2. Source 2: https://www.cdc.gov/museum/timeline/covid19.html#:~:text=January%2020%2C%202020,respond%20to%20the%20emerging%20outbreak

3. Source 3: https://www.pewresearch.org/social-trends/2022/02/16/covid-19-pandemic-continues-to-reshape-work-in-america/#:~:text=Earlier%20in%20the%20pandemic%2C%20just,have%20changed%20since%20fall%202020

4. Source 4: https://doi.org/10.1177/0265407584013001
