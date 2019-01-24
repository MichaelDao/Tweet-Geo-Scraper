# hashtag-scraper-to-json
scrape tweet based on hashtags for data analysis

based on this [guide](http://www.mikaelbrunila.fi/2017/03/27/scraping-extracting-mapping-geodata-twitter/)

I basically just fixed up the code so that it both uses python 3 and will now do some logging so you know whats going on.

Simply sign up for a twitter developer account and add your own credentials in. Change the hashtag to what you like and run in order
 
 - python scrapeTweets.py
 
 then when you feel like you have enough, process it into readable json
 
 - python processTweets.py
