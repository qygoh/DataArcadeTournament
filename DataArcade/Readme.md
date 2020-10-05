# PassionFruit's attempt for [Data Arcade Tournament 2020](https://sites.google.com/dsaid.gov.sg/dat2020)

DAT is an annual visual analytics competition exercise for officers serving in the Singapore Public service. This is our submission for #DAT2020! 

Theme for this year's tournament is "More Than Meets the I". We know it's cheesy but this page is our more than meets the I, showcasing all the behind the scene work that we did for data cleaning and preparation. 


### Our Chosen Theme: Female Representation in Corporate Boards

As women battling it out in the corporate world, we decided to work on this topic as this is something that resonated with us on a personal level. We also saw a potential to go deeper than the typical analysis. We all know that there is not enough female representation on corporate board, but what if we compared it between the often reported listed companies' boards with public sector boards? Or better still, tried to explore the topic from the angle of double hatting, or industry subsectors of the companies? 

We attempted to do just that for our submission, and it's been a fun journey working on this. No doubt we did it a little last minute (oops), but boy, we're proud of this!

### Organization of this Repo

- **Tableau Submission_PassionFruit.twbx** : The output of the project, a Tableau story that showcases the data we have scraped and the analysis
- **sgdi-scrape** : The scraper built for scraping the Singapore Government Directory 
- **Private_Scraper_1.ipynb, Private_Scraper_2.ipynb** : The scrapers built for scraping SGX and Google search results respectively


### Data Cleaning and Processing

There are two sets of data collected. One set for public sector board and another set for private sector board. 

Shermaine was in charge of scraping [Singapore's Government Directory Website](https://www.sgdi.gov.sg/ministries) to obtain the names and designation of members of the board, while QY worked on that for SGX listed companies.

Below are some highlights from the public and private sector board data cleaning. 

**For public sector data**: 
- For sherms to add in

**For the private sector data**: 
- The final data that made it to the notebook are that of 67 SGX Mainboard listed companies, and data were manually extracted from manual googling based company name outputs from Private_Scraper_1. Sadly, ran out of time to be able to crack and automate the process for all SGX listed companies.  
- The first scraper, Private_Scraper_1, churned out a total of 1892 SGX listed companies' information. Of these, 1025 were listed on SGX Mainboard and was registered in Singapore. 
- To overcome the problem of each company storing the board of directors information on differing tabs/segments in their own coporate webpage, the idea was to come out with another scraper to retrieve the direct link from Google Search result (see PrivateScraper_2.ipynb). Thereafter, to use BeautifulSoup or any other scraping library to store all the HTML parsed information, potentially converting it all to text and use relevant python packages to extract keywords of interest. Definately ran out of time for this ambitious endeavour, but will continue to work on it in the future. 

