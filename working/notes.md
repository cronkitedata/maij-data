## Converting class website to quarto

This is pretty straightforward. A few little things: 

1. I had trouble using the command line to create the remote github pages site. I just did it manually through Github Desktop. 
2. The scss files are where all of the customizations live. 


## Reading to put somewhere

Jon and Coulter on the covid deaths in Michigan: https://www.wsj.com/articles/coronavirus-deaths-were-likely-missed-in-michigan-death-certificates-suggest-11590073280?st=l74sw858lf9cz2o&reflink=desktopwebshare_permalink  (this is a free link for them. Don't shorten it. )



## New exercises

Shaena had the vaccination story here: https://azcir.org/news/2022/10/31/pandemic-accelerated-decline-childhood-vaccination-rates%ef%bf%bc/ and she gave me the data. It's a little overwhelming, but I can make it a little simpler. I'll compute an estimated number of students rather than percentages? Or show them how? 

AZCentral version:  https://www.azcentral.com/story/news/arizona/investigations/2015/02/03/hundreds-arizona-schools-skirting-vaccination-rule/22805897/
  https://docs.google.com/document/d/1Qp8xvsjjGN4tEOQ0M4GoD7XQ1dDvJh8TAgN3Vv-st0o/edit

  Data file https://cronkitedata.s3.amazonaws.com/xlfiles/vax_data_five_years.xlsx

 https://www.phoenixopendata.com/dataset/hiking-trail-usage/resource/aa4e2a08-c0ad-4fc4-bee9-44c2d85a58fa
  Good for practicing with dates. 

Presidential election flipped precincts. Should we do this for the spreadsheet review instead of the other? I'd like to do it with early vs. election day voters.  We don't need to make them do it themselves - I can just have them do an exercise. 

https://drive.google.com/file/d/1aHxSpEW7UkpXIAc-gVflxcrkhjByXsEU/view


reactable table of amtrak example: https://joshfangmeier.quarto.pub/table-contest-2022/





## Old hugo notes

command for doing the hugo server locally: hugo server -D -E -F --cleanDestinationDir --debug -v
to commit new version, just do the same thing without the word "server". For some reason I thought you had to "build", but it doesn't seem so. 

## Stats class

My examples: 

* Confirmation bias - On every story, I try to say, “why is what I’m saying wrong? Who would disagree and why? Is there another way to look at this, or to analyze this data?”  I don’t have to change anything, but I need to DISPROVE my findings. And example on the data we worked on in examples: phoenix claims. I found that the police spend more than others. Why might that be wrong? If I changed the years I looked at , would the answer be different? If I excluded one large case, would the answer change? 

* survivorship bias - My Drybar example. But every dataset has a survivorship bias. 

Look at your medical examiner records - although no one survived, it is an example of survivorship bias. You only get into the database is someone decides you should - what about those who never get to it? 

And regression to the mean - look at any time you’ve thought about “the law of averages”, or any time you have written about a real outlier - something very strange that has happened. Things happen! They’re true, but they’re not necessarily meaningful. 

## Notes from last semester class

Budget writing: 
"While police, fire and other public safety grew by more than $102 million, the departments charged with helping families in need and the homeless grew by only $8 million, with a lower-than-average percent increase." 

et’s talk about these “questions” - and think about two types : The first type is questions you’d have to ask the government or experts, or to obtain other documents about. — What don’t you understand. 

The second is about process - how do they come up with these numbers, what does “human services” mean? 

Hypothesis: The homeless problem in Phoenix has steadily become more severe, and I expect that the category that deals with housing and human services would rise the fastest. Did they? 

 Short declarative sentence: Police, fire and other public safety departments continue to take up more than one-third of the city’s budget, while the category of spending that includes “human services” rose the slowest. 
 
NOTE: How you characterize the numbers, how you put things in a “compared to what” idea. 

Good short story
https://apnews.com/article/virus-outbreak-ky-state-wire-ia-state-wire-ap-top-news-health-3bf753f9036e7d88f4746b1a36c1ddc4


* “ [How We Built a Database from Thousands of Police Reports](https://source.opennews.org/articles/how-we-built-database-thousands-police-reports/) ”, Mary Jo Webster, Source, Aug. 23, 2018.
* “ [Shot by Cops and Forgotten](https://news.vice.com/en_us/article/xwvv3a/shot-by-cops) ” by Rob Arthur, Taylor Dolven, Keegan Hamilton, Allison McCann, and Carter Sherman, VICE News, December 2017
* “ [How Phoenix Explains a Rise in Police Violence: It’s the Civilians’ Fault](https://www.nytimes.com/2018/12/10/us/phoenix-police-shootings.html) ”, by Richard Oppel, The New York Times, Dec. 10, 2018
* “ [Data on Use of Force by Police across U.S. Proves Almost Useless](https://www.nytimes.com/2015/08/12/us/data-on-use-of-force-by-police-across-us-proves-almost-useless.html) ”, by Matt Apuzzo and Sarah Cohen, The New York Times, Aug. 11, 2015
* Look at how the [Orlando Police Department](https://data.cityoforlando.net/Orlando-Police/OPD-Officer-Involved-Shootings/6kz6-6c7n/data) releases its use of force data, and an [example of a use of force report](https://www1.cityoforlando.net/opendatadocs/saoletters/17-075014.pdf) linked from that database. Also, the [list of data elements](https://www.fbi.gov/services/cjis/ucr/use-of-force) (highlighted on the left of that page) that the federal government will begin collecting from local agencies this year, on a voluntary basis.


Photo by <a href="https://unsplash.com/@sylwiabartyzel?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sylwia Bartyzel</a> on <a href="https://unsplash.com/s/photos/relax?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

https://drive.google.com/file/d/1aHxSpEW7UkpXIAc-gVflxcrkhjByXsEU/view
 

 THINGS TO REMEMBER: 

 ## Textbook updates

 ### Split installation of R / RStudio from the intro to it. 

 * Get the engine-car metaphor into the textbook.  ADD ANDREW HEISS'S VIDEO: https://youtu.be/cnQ-v1UUWyE

https://r4ds.had.co.nz/workflow-projects.html#rstudio-projects

and https://youtu.be/fT5xI1cmE2c


https://rmarkdown.rstudio.com/lesson-5.html

https://quarto.org/docs/get-started/hello/rstudio.html

### Convert to QMD

Change markdowns to qmd files, and then also use visual editor. 


### Create a few short videos introducing the environment and the common pitfalls. 

Andrew's is really good at showing them some common pitfalls and what they look like. 




There have been changes to the WaPo shootings data. Question: Should I just stick with the old one, or should I update the exercises and the textbook to reflect the new one? The new one is more standardized, which is good. But it has multiple categories for race/ethnicity which makes it hard. That's ok - we should just decide what to do. 

Rewrite the beginning R textbook chapter to reflect the WaPo data, not the PPP data? 

## Textbook issues

* Need more videos. On looking at it, it does have a lot that needs updating. Make the chapters shorter. Move the exercises to new chapters . More, shorter, chapters. 
* 





 
 