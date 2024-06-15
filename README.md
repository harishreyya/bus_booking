# bus_booking

## Introduction
A backend stack application for managing bookings of bus.The application allow users to create, get details of users,buses,booking details.

## Features
The key features of application.

- validation and error handling for API requests
- APIs for retrieving task statistics, such as getting details, creating details tasks

## Deployed link
[link](https://deploy-backend-bus.onrender.com/users)
note- U can check or test with this link as well in postman or browser 
(https://deploy-backend-bus.onrender.com/users)
(https://deploy-backend-bus.onrender.com/buses)
(https://deploy-backend-bus.onrender.com/bookings)

## Installation or How to run the app
I created cloud database using MongoDb Atlas. So, if you want to run our code then please read the instructions below :
- Clone our repository `https://github.com/harishreyya/bus_booking`
- Open the code in your VS code, open Backend folder in the terminal by running `cd Backend`
-Now run `npm install` or `npm i` which will install all the required packages of node
- After installation, now run `npm run server` and  you will see `server is listening on 5991` 
- Open MongoDb compass and url `mongodb://localhost:27017/busbooking` which will create database collection named busbooking
- Now you see app running, you can explore more.






## API Endpoints
Backend Applications provide a list of API endpoints
- GET /users - retrieve all users
- POST /users - create a new user
- GET /bookings - retrieve all bookings
- POST /bookings - create a new booking
- GET /buses - retrieve all bus details
- POST /buses- create a new bus detail


## Technology Stack
List and provide a brief overview of the technologies used in the project.

- MongoDB
- Express JS
- Node JS
 
 ### Dependencies and packages

#### Backend
- `express` <br/>
   used for handling backend
- `mongoose`<br/>
  connecting MongoDB to the Node js server
- `nodemon`<br/>
  It monitors your project and automatically restarts when detects any changes.

#### Cloud Deployment

- `render`
used render for deploying
