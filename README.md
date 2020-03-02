# Python Microsoft Outlook Email Scraper
This notebook extracts unstructured data from Microsoft Outlook emails regarding Travel Waivers
that United Airlines issues when travel plans may be impeded due to events like severe weather/epidemics/etc. 

The email data is cleaned and manipulated into a DataFrame that includes the Travel Waiver's
issued date, event name, category, severity level, cities impacted, and dates the waiver is issued for. 

The code can be broken down into the following 3 sections:

    1. Data mine Outlook to collect all Travel Waiver emails
    2. Create classes/functions to parse data from email 
    3. Iterate over the data set to clean and structure it

Over time, the collection of this data may yield some interesting insights into events that impact travel.
Feel free to ask questions or leave suggestions/critique, I love to learn other's approaches to problems!

![TravelWaiverImage](https://raw.githubusercontent.com/eli64s/Python-Email-Scraper/master/email_example_image.PNG)
