## Full-Stack Bad Bank

### Description

Final project for the course "Professional Certificate in Coding: Full Stack Development with MERN - July 2022".

The purpose is to demostrate a Bank's app with "full" functionality

Only a README file in this repositorie at the moment.

### Installation

It assumes you have Node (NPM), Docker Desktop, Nodemon

- Create a Docker container and start it
  * docker run -p 27017:27017 --name badbank -d mongo
  * You can test it by running: docker exec -it badbank bash
  * Once inside run: mongosh
  * Then run: show dbs
  * You should see a list of the 3 default databases
- Create a new directory, move inside and copy there all the files in this Repositorie
- npm init
- You might want to check all dependencies were installed, or confirm by running
  * npm i express
  * npm i cors
  * npm i chalk
  * npm i mongodb

### Screenshots

Soon. I only have some Mongo & Express things running:
![console](/readmeimg/console.jpg)

### Technology used

Front End: React
Server: Nodej.js Express
Database: MongoDB (in docker container)
Authentication: Firebase (hopefully I make it work)

### Features

- Create Account
- Login
- User Authorization
- Simulate "Withdraw" & "Deposit"
- View Balance
- View all data (admins only)

### License

ISC
Permissive Free Software License