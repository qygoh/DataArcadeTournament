# WGS84's attempt for [Data Arcade Tournament 2021](https://sites.google.com/dsaid.gov.sg/dat2021)

DAT is an annual visual analytics competition exercise for officers serving in the Singapore Public service. This is our submission for #DAT2021! 

The theme for this year's tournament is "Before & After". Before diving into our project proper, would like to warmly welcome Shan Yi into our group this year! Together we form the merry trio of Wong-Goh-See, so we named our group after a famous geographic coordinate system WGS84 :) 

## Our Chosen Topic: All about that Double Digit Day Sales Hype

As frequent and at times, irrational online shoppers, we decided that it would be fun to try to answer a nagging question that occurs everytime we get bombared with a monthly Double Digit Day Sales Advertisement: 

![99 Sale Advertisment gif](https://steadycompounding.com/wp-content/uploads/2021/08/https___bucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com_public_images_99060ebb-1c53-462e-9b01-eac42541dbce_640x360.gif)

**"Are Double Digit Day Sales really worth it? Am I getting good value in such sales?"** 

We set about answering the loaded question above by analyzing the sales before and after the Double Digit Day Sale. For the purposes of this competition, we have narrowed down the scope to cover the following: 
- Shopee Double Digit Day Flash Sales on 8/9/2021 (before), 9/9/2021 (during) and 10/9/2021 (after)

## Some insights from our Data Cleaning and Processing

A lot of data gathering and processing is needed to make this analysis possible. QY and Sherms had to first create webscrapers to collect real time information from webpages. Then, Shan Yi helped to set up and run the automated scraping during the event period. Data collected had to be further processed before being utilized for tableau visualization by the team. 

In total, approximately 14k rows of data was scrapped from the webpages over three days. This was done using two separate webscrapers, which utilized a combination of Selenium and BeautifulSoup. The first scraper was designed to collect relevant pricing information and links to products. The second scraper then read through the collected links to retrieve more information such as brand and product categories. 

## Organization of this Repo
  
- **Tableau Submission_WGS84.twbx** : The output of the project, a Tableau story that showcases the data we have scraped and the analysis
- **Scrapers Folder** : Contains the two webscrapers as aforementioned
- **Data Cleaning Folder** : Contains all the ipynbs created for the purposes of data cleaning and processing
