# NBA Player Tracker
NBA Player Tracker is a web application that allows users to keep track of some of your favorite basketball players. Using the NBA_API to retrieve real-time data on current players.

Tools used: Python(Flask), HTML5, CSS, pandas, SQLAlchemy, bcrypt

<img width="952" alt="search (2)" src="https://user-images.githubusercontent.com/77468658/192356026-bd0b5e4e-9720-42d8-8024-2276e13d7d78.PNG">

<img width="952" alt="Capture" src="https://user-images.githubusercontent.com/77468658/192355198-0c77e0f8-8475-4d2a-bb83-84e1a659ba41.PNG">

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
