# Newman_module
Generates HTML reports of Json files


# Getting started with Newman_module
Newman is built on Node.js. To run Newman, make sure you have Node.js installed.

# Installing Newman and run it from anywhere
npm install -g newman
newman run mycollection.json

# Options
Newman provides a rich set of options to customize a run
newman run -h

# Converting reports to html 
newman run mycollection.json -r html

# Converting reports to Json
newman run mycollection.json -r json






