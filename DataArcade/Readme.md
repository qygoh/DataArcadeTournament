# PassionFruit's attempt for [Data Arcade Tournament 2020](https://sites.google.com/dsaid.gov.sg/dat2020)

DAT is an annual visual analytics competition exercise for officers serving in the Singapore Public service. This is our submission for #DAT2020! 

Theme for this year's tournament is "More Than Meets the I". We know it's cheesy but this page is our more than meets the I, showcasing all the behind the scene work that we did for data cleaning and preparation. 


### Our Chosen Theme: Female Representation in Corporate Boards

As women battling it out in the corporate world, we decided to work on this topic as this is something that resonated with us on a personal level. We also saw a potential to go deeper than the typical analysis. We all know that there is not enough female representation on corporate board, but what if we compared it between the often reported listed companies' boards with public sector boards? Or better still, tried to explore the topic from the angle of double hatting, or industry subsectors of the companies? 

We attempted to do just that for our submission, and it's been a fun journey working on this. No doubt we did it a little last minute (oops), but boy, we're proud of this!


### Data Cleaning and Processing

There are two sets of data to be collected. One set for public sector board and another set for private sector board. 

Shermaine was in charge of scraping Singapore's Government Directory to obtain the names and designation of members of the board, while QY worked on that for SGX listed companies.



### Organization of this Repo

- **Tableau Submission_PassionFruit.twbx** : The output of the project, a Tableau story that showcases the data we have scraped and the analysis
- **sgdi-scrape** : The scraper built for scraping the Singapore Government Directory 
- **Private_Scraper_1.ipynb, Private_Scraper_2.ipynb** : The scrapers built for scraping SGX and Google search results respectively
