# Restaurant Reviews App–Stage1
Converted a static website to a mobile-ready, fully responsive web application. <br/>
View the site here: https://karen91013.github.io/RestaurantReviewsAppStage1/ <br/>
Note: the site will not be fully accessible with the link above, follow the instructions below to see the full thing!

# Instructions
1) Clone or download the zip file. 
2) Open the folder from where you saved it. Double click the index.html file, this will open the project locally on your computer.
3) Start up a HTTP server to serve the site files on your local computer. Use Python as it's the easiest way to do so.
Check the version of Python you have by running "python -V" in your terminal. If you have Python 2.x, use the command "python -m SimpleHTTPServer 8000" (or another, if port 8000 is already in use.) For Python 3.x, you can use the command "python3 -m http.server 8000". If you don't have Python installed, navigate to Python's website to download and install the software.
4) With your server now running, visit the site: http://localhost:8000
5) Voila! you now have access to a site that is fully responsive, acccessible, easy to use and ready for offline use!

# Dependecies
- [Leaflet](https://leafletjs.com/), a JavaScript library for interactive maps.
- [Mapbox API] (https://www.mapbox.com/), an open source mapping platform for custom designed map. To use this API, replace the text <your MAPBOX API KEY HERE>inside of main.js with your key. I have removed my personal API key.
- Various Udacity Grow with Google Scholars Slack channels helped me in understanding the service worker, as well as troubleshooting my errors all the way through the completion of this project. 
- Additionally, reading through Matthew Crawford's article on accessibility and following along really helped: https://matthewcranford.com/restaurant-reviews-app-walkthrough-part-3-accessibility/
