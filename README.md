# Bruins Windows Phone 8 App Server
---
* PHP API
* GMT time
* Pulls data from another site and stores in a database
  * http://live.nhle.com/GameData/RegularSeasonScoreboardv3.jsonp
  * http://riccomini.name/posts/game-time-baby/2012-09-29-streaming-live-sports-schedule-scores-stats-api/
  * http://www.livescore.in/free-livescore/
  * http://www.xmlteam.com
* Potential routes for consideration:
  * /roster -Up to date player roster with stats
  * /liveScore -Scores from the game going on right now
  * /schedule -Upcoming game schedule
  * /history -Game history?
  * /nextGame -Info for the next game
* Tokens for the app?
* Allow others to pull data?
---
# To Do List
[ ] Secure external API access
or
[ ] Set up so scores and data can be entered and stored manually
[ ] Provision and configure VPS
[ ] Decide on infrastructure
  [ ] Ruby on Rails
  [ ] PHP
  [ ] Python
[ ] Register domain name
[ ] Create high-level website 
[ ] Set up email address?
[ ] Decide on data format
[ ] Create initial API
[ ] Set up other API routes
[ ] Start polling and collecting data