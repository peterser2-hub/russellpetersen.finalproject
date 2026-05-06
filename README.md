# Russell Petersen
### Final Project

# Project Ideas

### Minor League Baseball Statistics Predicting Success
As a baseball player I find baseball stats very interesting. I could download a certain set of data from past minor league baseball seasons to determine if they were actually helpful in predicting major league successs.
Q: Does AVG exit velocity predict mlb success?
Q: Does K/BB rate predict how quickly a player gets called up to the major leagues?

### My Personal Trackman Data
I have access to my own personal pitching data. Velocity, Spin Rate, Movement, Location, etc. I also have access to ball flight outcomes. I could run an analysis on which of my pitches is most effective and in what locations.
Q: Does location actually have an effect on batted ball results?
Q: Which of my pitches is the most effective and where. What counts?


### Mayfly Hatches
I enjoy fly fishing, particularly understanding different fly hatches. I could look into how outside tempurature effects different fly hatches on a certain river. Deschutes, Walla Walla, etc. 
Q: Does Tempurature effect mayful hatches?
Q: Has rising global tempurature effected fly hatches in the PNW?


# Week 10 Update 
I will be completing this project on my own.
My topic is looking at the what is the most effective arsenal to have in the major leagues? Grouping pitchers by arsenal into categories, and then comparing xwOBA, K%-BB%, and Whiff%. 
I am planning on using pitch types, Walk Rate, K Rate, xWOBA, and whiff%. The pros of this data is that it is all in one website I have access to called Baseball Savant. The con is the potential size of the data as it will only be looking at starting pitcher data. 
Q1: Does Pitch arsenal effect K-BB%?
Q2: Does Pitch arsenal effect xWOBA?
Q3: Does Pitch arsenal effect Whiff rate


# Week 11 Update
https://colab.research.google.com/drive/1-pZy-RPxPNMhwLK_qUt6-7xKBy_1pcc-?usp=sharing
The data source that I decided to work with was from the website Baseball Savant. Baseball Savant houses all mlb stastical and trackman ball flight data. In order to aquire the data I put all of the information I wanted into a spreadsheet on the website, and then downloaded it as a CSV file.
Future Considerations;
- How only looking at starting pitchers, as opposed to relievers may skew my findings
- What other stastics than the 3 I chose are indicative of a successful pitcher.

The cleaning/wrangling that I still have yet to do is to group the pitchers by pitch use rate to determine distinct arsenal categories. I do not forsee any roadblocks at the moment. That is not to say any won't come up that I am not currently aware of. 


# Week 12 Update
<iframe
  src="stats.html"
  width="100%"
  height="600"
  frameborder="0">
</iframe>

I have yet to do the grouping that I intend to do for pitchers based on pitch usage, however I did create this initial interactive visualization. This 3D plot gives viewers the opportunity to see which pitchers were the most dominant in the 2025 season, to sort of confirm their ideas of who and what kind of pitchers had the most success. When looking at this visualization the first thing that you are able to determine is that Strikout Minus Walk rate appears to have a very strong correlation with xWOBA (The lead statistic I am looking at to determine a pitchers success). Another trend I am noticing in my data so far is that pitch Velocity has a very high correlation with a pitchers success. 

# Week 14 Update
I am moving into the stage of updating graphics and creating visualizations for the elementary analysis of my project. The next steps is what I am most excited about, which is making pitch usage suggestions for major league pitchers to make them more successful based on my findings. I have completed all of my data wrangling so far. 
The new technique I am looking forward to implementing in my project is a form of a visualization; I want to create a baseball field, or visualization of a strikezone, to display my data. This new technique would require some more complex python coding and packages, and would't allow me to just use the plots avaliable in pyplot. I plan on learning this technique through an article or youtube explination of how to create complex visualizations. 
I am actually super excited on how I am going to explain the narrative of this project. When we did the in class exercise on sketching visualizations, I sort of created a road map I wanted to follow with my website. First introducing the data set and elementary statistics with explinations for non baseball informed people, followed by more complex analysis and my suggestions. Like I mentioned above I hope to use the visual of a baseball field or strikezone, hopefully as my like main visualization. I hope that my website is followable enough that I can present straight from it. 
