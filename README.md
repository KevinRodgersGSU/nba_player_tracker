# NBA Player Tracker
NBA Player Tracker is a web application that allows users to keep track of some of your favorite basketball players. Using the NBA_API to retrieve up to date data on current players.
## Setup Instructions
1. `pip3 install -r requirements.txt`
2. Create a `.env` file in the top-level directory and enter the following as its contents:
```
export HEROKU_POSTGRESQL_IVORY_URL="<YOUR HEROKU POSTGRESQL DB URL>"
export SECRET_KEY="<YOUR SECRET KEY>"
```



Heroku Link: `https://limitless-lake-88828.herokuapp.com/`
Note - we realized Friday night that the nba_api that we use has heroku blacklisted. We are currently looking into solutions to this problem.

## Linting

Collaborators: Rayaan Chowdhury, Miles Phillips, Inesh Raj, Kevin Rodgers
