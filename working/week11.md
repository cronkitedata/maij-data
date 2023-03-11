---
title: Data cleaning with Open Refine 
date:  2022-03-21
draft: true
description: You've seen it's hard to fix little mistakes in R, and that we don't have a good set of tools to it in Excel. Enter [OpenRefine](https://operefine.org), a small little program you put on your computer that is designed to help find and fix inconsistencies and difficult problems in your data. We'll also touch on extracting data from PDFs. 
--- 


## Agenda

Monday: 

- Review the replication project as a whole. 
- Intro to OpenRefine to clean data

Wednesday:

~~-  Team lab: The Data Hunt. Finding and evaluating data on your beat on deadline.  A guide to a data hunt is in the class textbook: [Finding the right data for your story](https://cronkitedata.github.io/djtextbook/start-hunt.html), and a template with an old example that won't work anymore is in [this google doc](https://docs.google.com/document/d/14nxUPMIAmIGm1hwWhSBYqoVF3HSlFyk6XWiozXjeO5w/edit) . (These are the same links shared with News21 students earlier this semester.)~~

- We went over the[basics of scraping using this presentation](https://docs.google.com/presentation/d/1W4esHT93tKQVUHJLhyVM8f2je-DLWKu-MtzZ7-I6hi8/edit?usp=sharing). We'll continue with scraping using R next week.  I'm going to try to write a scraping exercise in the textbook by next week. 

## Upcoming deadlines

Sunday 3/20
{.text-dark}
Final replication project

Friday 3/25
{.text-dark}
Second self-assessment

Sunday 3/27 
{.text-dark}
Story memo proposal

## Preparation & learning materials

If you want to follow along in class, you can either use the computers in the lab, or install [OpenRefine](https://openrefine.org/download.html) on your computer -- it doesn't take up much space. Just unzip it and drag it into your applications or anywhere else you want to launch it from. I'm by no means an expert in using this, but it's invaluable for fixing city names and standardizing company names. (Windows folks: Use the "Windows kit with embedded java". )

I'll have a chapter in the textbook on it by the time we get to this section. 
### Wednesday April 27

Ethics in data journalism. There is some easy reading  and viewing to get ready for this class - it shouldn't take more than two hours, most of it in the videos. We'll look at some common cognitive biases that you should consider when working on a data-driven project, and look at some of the best practices to avoid common pitfalls. 

#### Posting raw data on your website

- "[Public information doesn't always want to be free](https://source.opennews.org/articles/public-info-doesnt-always-want-be-free/)", by Matt Waite, 2013

- Pages 174 to 181 in "[To Post or Not to Post](https://cronkitedata.s3.amazonaws.com/docs/post-or-not.pdf  )", by David Craig, Stan Ketterer, and Mohammad Yousuf, Journalism & Mass Communications Quarterly, 2017, via ResearchGate.  

#### Ethics in scraping

- "[To scrape or not to scrape: technical and ethical challenges to collecting data off the web](https://www.storybench.org/to-scrape-or-not-to-scrape-the-technical-and-ethical-challenges-of-collecting-data-off-the-web/)" Sophie Chou, Storybench, April 2016


#### Common cognitive biases in data journalism

- ["How to prevent confirmation bias affecting your journalism"](https://onlinejournalismblog.com/2020/04/07/how-to-prevent-confirmation-bias-affecting-your-journalism/) Paul Bradshaw, Online Journalism Blog. This is a particularly big problem in data journalism, since we often seek out stories in databases based on tips or broad ideas, and can often find them. If you're interested (not required),  read "[A journalist’s guide to cognitive bias (and how to avoid it](https://onlinejournalismblog.com/2020/03/24/a-journalists-guide-to-cognitive-bias-and-how-to-avoid-it/)" for other kinds of biases that we might bring to our reporting.  These include common problems in newsrooms, such as a "sunk-cost" bias or a negativity bias.

- BBC Worklife, [How ‘survivorship bias’ can cause you to make mistakes](https://www.bbc.com/worklife/article/20200827-how-survivorship-bias-can-cause-you-to-make-mistakes) (just watch the video)

- The videos # 1-4  from the Knight Center for the Americas on "Equity and Ethics in Data Journalism's" module 3.  I'm not thrilled with the pace or specific content with these videos, but they're the best single spot I've found for these common problems. Feel free to speed this up considerably. I found that 1.75 was the right speed for me! (She talks about writing data journalism stories, but she's never been a journalist of any kind. Sigh.)

   * [Common mistakes in data analysis](https://youtu.be/4ndrF2cSqVo)
   * [Causal mistakes in data](https://youtu.be/9nKs7mJukSk)
   * [Simpson's paradox in data journalism](https://youtu.be/f5gMwGfZL3g)
   * [Prosecutor's Fallacy in data journalism](https://youtu.be/0y3sco0lKzc) OR [this piece on prosecutor's fallacy](https://towardsdatascience.com/the-prosecutors-fallacy-cb0da4e9c039) by Ray Johns, 2019. 

"[Fighter pilots and firing coaches](https://faculty.mccombs.utexas.edu/carlos.carvalho/teaching/regression_to_the_mean.pdf)", Brian Burke, 2009, in Advanced Football Analytics, with an explanation of regression to the mean. (This link is to a printout of the original piece, since the website version is a little bit of a mess.) It isn't very well written, but it eventually gets around to an anecdote about fighter pilots and the concept we care about: "regression to the mean". 

#### Accuracy as the ultimate in ethics

There are a lot of bulletproofing pieces out there,  but this [email from me to Criag Silverman](https://cronkitedata.s3.amazonaws.com/docs/bulletproof-email.pdf), who at the time wrote "Regret the Error" for Poynter, goes over most of them. (The piece he wrote is no longer on the web.)

#### Additional optional reading: 

* "[Distrust your data](https://source.opennews.org/articles/distrust-your-data/)", by Jacob Harris, The Source, 2014. At the time, Harris was a news developer at The New York Times. 





## Recommendations for going further 

### OpenRefine

People who work in digital humanities, such as historians or experts in literature, often need to do many of the data cleaning chores that reporters do. That community has taken to OpenRefine, and there are a ton of good tutorials in that space. Here are a few: 

* [UCLA's Digital Humanities 201 course](http://miriamposner.com/classes/dh201w19/tutorials-guides/data-cleaning-and-manipulation/getting-started-with-openrefine/) , by Miriam Posner
* Digital humanities OpenRefine lesson from [Data Carpentry](https://data-lessons.github.io/dh-openrefine/)


### Scraping

Try doing a couple of the other tutorials listed in the textbook. Also, when you sign up for your free DataCamp account, you'll see some assignments from me. The two that relate to scraping are particularly good. 
