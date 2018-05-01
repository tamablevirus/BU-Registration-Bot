# BU Auto-Registration Bot

With BU Ninja becoming more and more widespread, it is becoming harder to get the class you want. With this bot, however, you can beat the competition for free! (at the moment)  

*Please keep this descrete. The more people that use it, the less effective this will be.*  

Email me at `juliusf@bu.edu` or fill this form to get python source code  
https://goo.gl/forms/1fhgMlSXeFBAxT272

## Installation
Using anaconda,
`pip install selenium`  

Google and download chrome webdriver, extract, and add to path.  
Restart your computer for it to register.  
Save code to python file, edit credentials and courses, then run.

## How it works
Using the Selenium API, the script opens a browser and automatically logs you into the BU Student link. After that it grabs the cookies and closes the browser. Then it sends queries to the course browser and when your class is open, it gets the course selection ID and registers by making a request with that information.
