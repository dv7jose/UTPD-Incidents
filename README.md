# UTPD Incident Notification Scraper

Final Map View: https://incidentsutpd.netlify.app/
Data Reporter: José Martínez, martinez307jose@gmail.com

### Data Overview

UTPD has a responsibility to comply with Clery Act requirements, releasing timely warnings about reported crimes to the campus community in a manner that will aid in the prevention of similar crimes, as well as providing emergency notifications within Clery Act geography when the health and safety of the campus community is at risk. The department utilizes one or more of the following methods of communication to post warnings:  text messages, campus wide email, social media (Facebook & Twitter), UT Emergency and home page, campus siren system, desktop pop-up alert system and closed circuit television systems in residence halls and other buildings.

The excerpt above comes from the following website: https://police.utexas.edu/crimefeed

Here, UTPD publishes all the notifications they send out to students. I decided to scrape each incident using Selenium and map it with Geopy and Folium. There were multiple pages to parse through and each page had different links to open, so it required a few for loops.

There was also a lot of cleaning to do with the coordinates and summaries of each incident.

Thus, in the final map, users can look at the incident's location, date, and summary instead of going page by page which is less appealing and more difficult.
However, on the website, users are able to see all the incidents in order from most recent to the latest. Here, it's easier to navigate and and see which locations have been most prone to incidents.
