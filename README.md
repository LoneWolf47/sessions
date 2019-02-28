# Sessions
   This project is backend for a simple web app with sessions implemented using Nodejs.
   
## Installing
   Run **`npm install`** in terminal from the project directory.
 
## Starting the Project

 - Run MongoDB server.
 
 - Run **`node server.js`** in terminal to start project.
 
## User Schema :
 
 - email
 
 - username
 
 - password
 
## APIs
 
 - Web Server running address **http://localhost:3000/**
 
       - Post request with all 3 parameters set in request's body will create a new user and session variable.
       
       - Post request with email and password set in request's body will carry out login process.
 
       - Get request to '/logout' page will destroy the session variable and logs out the user.
