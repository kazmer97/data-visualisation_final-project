# Astronouts Data Project Brief

The project started off from the [tidytuesday challenge](https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-07-14). The visualisations rely on the datasets found there and completed with one about the mission success and nasa budget.

The project explores the timeline of the space race between the USSR and USA, which reveals some interesting trends that the Russians kept on heavily investing in going to space for quite some time after Americans have landed on the moon. It also reveals they sent a women to space early on in the space race which then was not repeated for tens of years, which makes it questionable if they did it for gender equality reasons. 

It also reveals the rate at which each country was burning their resources while the race was on, not minding high failure rate during launches in the early days as well as the loss of human lives. In the US the moment of moon-landing marked the turning point in public interest as the number of launches steeply declined and NASA's budget was cut. While becoming an astronaut still remained cool as new astronaut numbers increased up until the 90s.

From this trend we can visualise the privatisation of space industry. Which reveals an interesting comparison between the  government's and corporation's ability to efficiently allocate resources. Since the advent of private space flight rockets have gotten significantly cheaper, due to a difference in approaches. Corporations, especially SpaceX leading the way didn't mind blowing up rockets, while NASA was seen as wasting taxpayer money every time a launch wasn't a success. Turns out just like in software, tech and other industries in rocket science fast iteration while making mistakes is a better way of making progress then trying to avoid failure. 

The presentation serves as jumping off point to help the audience think about the past and future of space and also challenge assumptions. While the decline of state launches has might indicate initially that state funded space exploration is in decline, deeper analyses reveals a lot more nuance. The United States within the last 10 years has steeply increased NASA's budget almost reaching similar budgets as during the space race. Combining insights from multiple datasets helps us place into context, revealing the private and state funded space agencies are working in synergy. 
Reasons of NASA's budget increase could be multiple and the data needs to be placed into context with global news. Is it because China is increasing their presence in space? Is it national pride, as for years the US was unable to send astronauts to space without russian rockets? Is it finding ways to combat climate change? The reasons are probably a combination of these, but having data to start of with allows us to place related news into better context.

While space walking hours between US and Russian astronauts may seem like a simple visualisation, it reveals an insight about differences in state approaches. Russia holds the record, while the US has a higher total man hour in space. This could indicate that the US maintains more satellites and telescopes in space as those are the main reasons to go on a space walk. 

These visualisations while seemingly branch out tie into a cohesive story about the history and potential future of space exploration, based on the available datasets. 

## Note to any readers

These were our teams thoughts around the topic, but we hope we can spark a conversation through the visualisation we've chosen, so feel free to share out dashboard with your friends. 

## Data Sources
Tidy tuesday challenge link: https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-07-14

**Astronouts**: https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-07-14/astronauts.csv

**launches**: https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-01-15/launches.csv

**agencies**: https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-01-15/agencies.csv

**mission success**: https://www.kaggle.com/agirlcoding/all-space-missions-from-1957

**NASA budget dataset**: (https://www.planetary.org/space-policy/planetary-exploration-budget-dataset)

# Project Proposal
AM10 Data visualisation repository for final project

Group 11 Proposal for Final Group Project

Our database contains information about all astronauts who participated in space missions before 15 January 2020. The data is collected from NASA, Roscosmos, and other related websites. 

There are 22 columns in the data. The columns include astronaut name, sex, date of birth, nationality, military status, occupation, information about each mission such as mission durations and mission year. 


What issues or questions are you addressing? 

Countries: 
Which countries are dominant?
Is there a country that is significantly increasing the number of astronauts? (New entry to market kind of thinking)

Background of Astronauts: 
Age: 
Age of astronauts possibly by country
Which countries send the youngest/oldest people to space?
What’s the age trend of astronauts: are more young people becoming astronauts?

Gender:
Which countries have more female astronauts
Female/male ratio over time

Occupation:
Distribution of occupation and status of the astronauts 

Missions:
What do typical missions look like? 
How long do they stay in orbit? 
How long do they get out of the spaceship for? 
Which teams have stayed the longest? 

Missions by periods of time ⇒ are there moments where space missions were popular / moments when no one was in space ? 

Total mission duration over time, possibly faceted by gender or country
Duration of extravehicular activities during the mission (eva_hrs_mission) over time, possibly faceted by gender or country




What is the source of the data you will be using? 
TidyTuesday summary on Astronaut database published on 2020-07-14. 
The data comes from Mariya Stavnichuk and Tatsuya Corlett, and was prepared by Georgios Karamanis.
https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-07-14/readme.md#astronautscsv

TinyTuesday 2019-01-15
Principal data came from the Jonathan McDowell's JSR Launch Vehicle Database, available online at http://www.planet4589.org/space/lvdb/index.html
https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-01-15



What statistical techniques do you think you may be using? 

Some statistical techniques that we will use are confidence intervals and hypothesis testing to accompany our visualizations and show significance.  

Clustering to determine if there are distinct types of astronauts we can identify.

Explore correlations between space agency and rocket technology used between the length of mission and space walks.

Possibly a model to predict/understand how factors like country, age, etc affect/predict the number of missions an astronaut will go on.




