# Python Microsoft Outlook Email Scraper
This script extracts unstructured data from Microsoft Outlook emails regarding Travel Waivers
that United Airlines sends out related to events/weather/etc. that may impact travel. I have 
attached an example image below of what a Travel Waiver looks like in my mailbox. 

The email data is cleaned and manipulated into a DataFrame that includes the Travel Waiver's
date sent, event name, severity level, cities impacted, and dates affected. 

The code can be broken down into the following 3 sections:

    1. Scrape Outlook to collect all Travel Waiver emails
    2. Create classes/functions used to parse the emails 
    3. Iterate over the data set to clean and structure it

Over time, the collection of this data may yield some interesting insights into events that impact travel.
Feel free to ask questions or leave suggestions/critique, I love to learn other's approaches to problems!

![TravelWaiverImage](https://raw.githubusercontent.com/eli64s/Python-Email-Scraper/master/travel_waiver_image.PNG)
