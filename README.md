# Expense Tracker

## Setup

Install docker desktop [Download link](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe)

`docker pull alexpujolcomet917/expense-tracker:back`

`docker pull alexpujolcomet917/expense-tracker:front`

## Run App

Edit *docker-compose.yml* by changing `changeme` to your database name. (Example: AlexDB)

`docker-compose -f .\docker-compose.yml up`

Open [application](http://localhost:3000/)


### ARM user's

`docker pull alexpujolcomet917/expense-tracker:front-arm`

Edit *docker-compose.yml* by changing `:front` to `:front-arm`


### Extra resources
[excell with bank movements](https://docs.google.com/spreadsheets/d/1-8L_fA8xpOU24aJi4RckAZ0T0FP_p_s9/edit?usp=sharing&ouid=109836800309591523741&rtpof=true&sd=true)
