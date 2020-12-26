# Economic Changes and Frustrations in the US during the Coronavirus Pandemic:  A Story in Reddit Posts

# Introduction and Motivation
1.	The onset of the coronavirus pandemic in the United States led to a disastrous level of unemployment in the United States.
    - This began a particularly disastrous end for the service-based industry and its employees.
    - To this day, there is no easy fix to this, since social distancing is crucial to the stop of the spread of the virus.
2.	Why investigate this?
    - As someone who has worked in service roles in the past, and remembering how many of my coworkers had families to support, this makes me especially worried.
      - In some states, unemployment websites were broken, and several family friends had no way to even apply for unemployment (Florida). TODO CITE
      - This unemployment benefit uncertainty is not only an economic strain but a mental health strain on those trying to make ends meet for their families.
    - some personal motivation: As a college student currently searching for post-graduation employment, I am also concerned about the state of the economy. Furthermore, my hometown of Miami, FL relies on a tourism industry to keep its economy healthy. For the first time in living memory, at least for me, neighborhood food banks are a common service.
    - But I am more so concerned about a sense of general despair in the American population. Services (including financial services) make up 68% of the US Economy TODO CITE,
    - While that number encompasses the most affected industries, including food and all kinds of services, it’s indicative of how service based the US is.
---
3.	Where Did I Source the Data From?
    - I sourced it from popular job seeking and advice forums on Reddit, a social media website, for several reasons.
        - It is free to make an account on Reddit – anyone can go on it seeking for advice.
        - Reddit is home to just under 30 million American users, and I am most concerned with the American economic impact in this data story.
    - In particular, I chose two popular subreddits – R/Jobs and R/CareerGuidance. These are field agnostic (not tech job subreddits, which are also common on the website), and workers from the service economy frequently post on it looking for job search advice.

# Questions and Analysis

## Landscape of Top 1000 Posts:

### **An Interesting Pattern from R/CareerGuidance**:

I scraped the top 1000 posts of all time (top 1000 posts with highest number of upvotes, or likes, since the inception of the subreddit) and found an interesting pattern:

2020 dominated the landscape of the top 1000 posts of all time in R/Careerguidance. In fact, we have that a whopping *547* of the posts in the Top 1000 list (so the majority by many standards) were from 2020! Only *383* were from 2019, *67* were from 2018, and *3* were from 2017. 2016 saw no share in the Top 1000. 

This figure illustrates this disparity in popularity of the posts between years:

![2020 Outperforms in Subreddit](img/fig_1.png)

This fact is particularly impressive considering that the top 1000 group consists of the top 1000 posts of all time since the inception of the subreddit, which was in *2011*!

To me, this means that 2020 saw more user engagement or a form of user "agreement" - likes and upvotes are, after all a way of agreeing with the sentiment of a post - than any other year. I would really like to attribute this to the arrival of the pandemic to the US and its disastrous effects on employment, but we can't be sure. 

### Another Interesting Result from R/Jobs:

Doing the same analysis for r/jobs, I found that the 2020 presence wasn't as strong in the Top 1000 posts of all time as it was on R/Careerguidance. However, 2020 still overperformed. 

In fact, *393* of the posts in the Top 1000 were from 2020, *308* were from 2019, *157* were from 2018, *41* were from 2017, and *35* were from 2016. 

This figure illustrates this disparity in popularity of the posts between years on r/Jobs:

![2020 Outperforms in Subreddit](img/fig_2.png)

This is still impressive, considering that 2020 isn't even over yet. 


### Was there An Increase In Activity After the Arrival of COVID-19 to the US?

I was first most curious about the overall landscape of the top 1000 posts of all time in these subreddits. Did activity go up on these subreddits after the beginning of the Covid 19 Lockdown? What about  I investigated (spolier: it did, a bit, in CareerGuidance)
- The data can be found in data/raw folder.
- - I scraped the top 1000 posts of all time (most votes and comments) and found interesting patterns:
- For r/careerguidance, after subsetting the data by month, I found....




### March 2020 in R/CareerGuidance

This table shows that the statistics from r/CareerGuidance from March. Note that the March statistics are being compared to a database containing the top 1000 posts of all time (at least since the forum was founded in 2011), so an average statistic from March 2020 which is close to the average statistic from the general top posts is quite impressive!

It's clear that the average post scores in March were much higher than the average post scores in Top 1000 posts of all time. Furthermore, I would venture to say that there was a lot more user engagement in March, since we see a higher average number of comments in March 2020.

| Statistic   | March Posts | --Top 1000 Form Posts of All Time--
| ----------- | ----------- | ----------- |
| Number of Posts  | 50       | 1000 |
| Average Post Score | 267.42* | 208.5 |
| Average Number of Comments| 99.98* | 77.01*
| Highest Number of Comments on Post | 457*  | 579 |
| Highest Post Score | 772 | 1484 |

### April 2020 in R/CareerGuidance
 In April, something interesting happened.

  - Users began feeling anxiety regarding quitting or losing their jobs during the pandemic. It became an economic threat as well as a health threat.
  - From the data we find that the highest ranking post in April in r/careerguidance was directly related to losing your job during the coronavirus pandemic:      QUOTED HERE: 
    -  > "Are you seriously trying to quit your job during a global pandemic and impending recession? o_O
    -  >  (Advice) This will probably be downvoted to hell. That’s okay. But really, there has been an uptick in people posting about quitting their jobs. This isn’t to berate you. If you aren’t happy, you really should find a way to leave. ...Where I am, the depression from the lockdown restrictions alone has led to a rise in suicides. Quitting your job and then finding yourself in the cold may put you in a worse off position. This is sounding harsh but it is coming from a good place. Things are going to work out. We just don’t know when. In the meantime, hang in there. Take this global lockdown time to plan your exit meticulously, save up and start skilling up for the jump. Good luck!"
    -  From this top post, we can see tension is rising regarding job security amidst the pandemic.
    -  This had the highest number of upvotes, meaning users upvoted this post more than any other post made in April in 2020.



- The table of statistics for April in the same forum, r/CareerGuidance, shows a massive spike in post scores, and a realtively high top scoring post (it actually turned out to be the second highest scoring post on the subreddit ever, second only to one post, this was exciting since we )

- In contrast, the post with the highest number of comments from r/careerguidance from March 2020 (too soon for the full extent of masssive layoffs, furloughed employees, rescinded job offers) was concered with being rejected from a job despite being qualified:
    -  >  "I was rejected from a position that required a high school diploma when I have a bachelor's. How am I supposed to properly handle how pathetic I feel right now?"

## Landscape of Posts Before March 2020:
1. What were the most popular types of posts before th onset of the pandemic? Which were the most popular types of posts after the onset?
    - INSERT TOP 5 SCORES FROM COVID DF FOR RJOBS VS TOP 5 SCORED FROM NON COVID DF FOR R JOBS
    - HIGHLIGHT THE TOP 5 POSTS FROM EACH in bar plot
    - From this, you can see that the focus started to shift onto digital job tools (LinkedIn, Glassdoor) and feelings regarding those tools.
    - During this time, we also see a rise in users complaining about not being able to find work, despite their best efforts:

    - take a look at the titles for May 2020's top 5 highest scoring posts

### May 2020 in R/CareerGuidance

| Top 5 Posts in May on R/CareerGuidance       | Score |  Link|
| ----------- | ----------- | ----|
| Anyone else graduated, got in a 'career' and realise there was more to life than work?       |   1147
  |  |
| Is there no place for employees that are just pretty good at their jobs?   | Text  | |
| How do I get over my deep-seated dislike of working?| |
|It's no longer enough to do your job, but you have to be above and beyond to keep it?| |
 | Lost in job hunt and life, what the hell do I do now?| |

- Interpretation:
- these are posts with a bleak interpretation of work,
- Let's compare this to the top five posts from r/jobs from May:

### May 2020 in R/Jobs

| Top 5 Posts in May on R/Jobs     | Score |  Link|
| ----------- | ----------- | ----|
|Does anyone else find LinkedIn toxic? |   1147 | |
| How will I ever go back to an office? | Text | |
| Today, I just found out that my previous job was listed online a week ago as open and is accepting applications.| |
|Has "faking it till you make it" gone too far? | | 


These tables paint a bleak picture of the state of the worker in America, both in service and non-service based roles.

# Summary + Possible Limitations of My Analysis

1. One social media site is not a faithful representation of the entire country, but drastic changes online might signal drastic changes in the US economic landscape.
2.