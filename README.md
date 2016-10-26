CatFacts
===
A simple NodeJS project to check the Twitter stream and when #catfact is tweeted, this project will tweet to the user an interesting fact.

Background Process
---
To get this project to run in the background on a linux server use the forever application

install with npm:
`sudo npm install -g forever`

move to your directory folder:
`cd /var/www/html/demo/catfacts`

and to run as a service type:
`forever start index.js`