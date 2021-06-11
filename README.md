# Online-Shopping-ReCreated

Features :
	
	-> Easy to use.
	-> One can get an idea to do agriculture without use of artificial fertilizers.
	-> Doorstep Delivery.
	-> One website is enough for both acquiring knowledge and buying products.

## Requirements 

Hardware Requirements :
	
	-> Proccessor 		          - Pentium 4 or Later
	-> Memory    		            - 2 GB minimum - 4 GB maximum
	-> Screen Resolution 	      - 1280x1024 or larger
	-> Application Windows Size - 1024x680 or larger
	-> Internet connection 	    - Required

Software Requirements :

	-> Operating System	        -	Windows 10
	-> Environment		          -	NODE JS
	-> Scripting language	      -	HTML, JavaScript, CSS
	-> Database		              -	Mongo DB

## How it works

### Sign in/up

These are the main goals of this module 

	-> All major info about the user will be received 
	-> Generate user unique id for all users

These are the scripting languages and environment used in this module 

	->EJS is used to create user interface.
	->CSS is used for design the user interface.
	->NODE JS act as a intermediate between database and front end.
	->MONGO DB is the main database.
	->EXPRESS is a framework which is used to reduce manual work.

### Info Collection

These are the main goals of this module 

	->The crop selection module records the information about the crop based on land type and climate type. 
	->The crop selected by the customers. First the user need to select the climate and based on the climate list of land will be displayed. 
	->Based on list of land the user need to select the crop. 

These are the scripting languages and environment used in this module 

	->EJS is used to create user interface.
	->CSS is used for design the user interface.
	->NODE JS act as a intermediate between database and front end.
	->MONGO DB is the main database.
	->EXPRESS is a framework which is used to reduce manual work.


### Crop Suggesion

These are the main goals of this module

	->Based on climate and land category the lists of crops will be displayed. 
	->User can select the crop that they like. 
	->After selection of crop the details of crop will be displayed. 

These are the scripting languages and environment used in this module 

	->EJS is used to create user interface.
	->CSS is used for design the user interface.
	->NODE JS act as a intermediate between database and front end.
	->MONGO DB is the main database.
	->EXPRESS is a framework which is used to reduce manual work.

#### NODE JS 

This application is written in node js and in the pattern of MVC.

	->[Node.js]  (https://github.com/nodejs)
	->[Express]  (https://github.com/expressjs/express)
	->[Mongo db] (https://github.com/mongodb/mongo)

The application uses single threading in order to process events asynchronously.
	
	-> Generate user unique id for all users when they signup.
	-> Session was created when the user login to the application.
	-> Session will notify the each process and store it temporarly.
	-> When the user log out the session, Session details will be vanished. 

## Installation, Configuration and Running 

First ensure your system correctly setting up with required softwares 

These are the some third party packages used in this project

```console 
npm install -dev nodemon
npm install -save express 
npm install -save ejs
npm install -save mongodb
npm install -save mongoose
```   

This third party package used in routing

```console
npm install -dev bodyparser
```

This command is used to run the project
 
```console
npm start
```
