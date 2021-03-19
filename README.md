# Finance Tracker

## Intro

This project has authentication features like signup, login/signout, edit profile. Users can: track stocks, up to 10 per user, their profile page will display all the stocks they are tracking with the current price. can search for stocks, add and remove stocks from their porfolio, can search for friends, or other users by name or email, can view the portfolio of stocks their friends are tracking for investing ideas, this app was made using Ruby on Rails (RoR) framework with focus mostly on backend functionalities but it includes a basic view to use.

## Check this app at:

https://tranquil-sea-85295.herokuapp.com


## How users can get started with?

### Pre-requisites

Before starting, it is necessary to have already installed and configured in your system:
  - Git ver. 2.11+
  - Ruby ver. 3+
  - Ruby on rails ver. 6.1.3+ (running on port 3000)
  - SQLite3 ver. 3.31.1+
  - NodeJS ver. 14.16.0+
  - Yarn 1.22.10+

### Start

Clone the repository to have the local project:
``` sh
git clone git@github.com:SneyderHOL/finance-tracker.git
```

Get inside the path of the project:
``` sh
cd finance-tracker
```

Installing dependecies:
``` sh
yarn install
```
``` sh
bundle install
```

Create tables in database:
``` sh
rails db:migrate
```

Running app:
``` sh
rails s
```

Checking app from browser at:

localhost:3000