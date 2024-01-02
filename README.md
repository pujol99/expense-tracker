# Expense Tracker

## Setup

Install docker desktop [Download link](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe)

`docker pull alexpujolcomet917/expense-tracker:back`
`docker pull alexpujolcomet917/expense-tracker:front`

## Run App

Edit *docker-compose.yml* by changing `changeme` to your database name. (Example: AlexDB)

`docker-compose -f .\docker-compose.yml up`

Open [application](http://localhost:3000/)