# Online-Shopping-ReCreated

Features :
	- Its a very intractive User friendly interface.
	- Once the user surf in to the website he retrive each and every information about the product.
	- Every nook and corner of online Store has been coverd.
	- Using New technologies will help in increase the support for the web site.

## Requirements 

Hardware Requirements :
	
	- Proccessor 		    - 	 Pentium 4 or Later
	- Memory    		    -	 2 GB minimum - 4 GB maximum
	- Screen Resolution 	    -	 1280x1024 or larger
	- Application Windows Size  -	 1024x680 or larger
	- Internet connection 	    -	 Required

Software Requirements :

	- Operating System  	-	Windows 10
	- Environment		-	NODE JS
	- Scripting language	-	HTML, JavaScript, CSS
	- Database		-	Mongo DB

## How it works

### Purchase and Sales

These are the main goals of this module 

	- The details about the purchase of the raw materials are recorded. The data used are quantity, quality, amount, purchase data of the goods.  
	
	- The details of all the sales orders received are recorded.

These are the scripting languages and environment used in this module 

	- EJS is used to create fileds to get the sales and purchase information from the user.
	->CSS is used for design the user interface.
	->NODE JS act as a intermediate between database and front end.
	->MONGO DB is the main database.
	->EXPRESS is a framework which is used to reduce manual work.

### Order Processing

These are the main goals of this module 

	- The details about the  processing of the order based on the buyer order details are recorded. 
	
	- The daily amount of goods processed are used as the data of this module.
	
	- The details about  the amount of production of goods are recorded.

These are the scripting languages and environment used in this module 

	- EJS is used to create user interface.
	- CSS is used for design the user interface.
	- NODE JS act as a intermediate between database and front end.
	- MONGO DB is the main database.
	- EXPRESS is a framework which is used to reduce manual work.


### Shipment and Devlivery 

These are the main goals of this module

	- The details about the shipment of goods to the Buyers are recorded in this module.
	- All the delivery process will be notified to the user.

These are the scripting languages and environment used in this module 

	- EJS is used to create user interface.
	- CSS is used for design the user interface.
	- NODE JS act as a intermediate between database and front end.
	- MONGO DB is the main database.
	- EXPRESS is a framework which is used to reduce manual work.

#### NODE JS 

This application is written in node js and in the pattern of MVC.

	- [Node.js]  (https://github.com/nodejs)
	- [Express]  (https://github.com/expressjs/express)
	- [Mongo db] (https://github.com/mongodb/mongo)

The application uses single threading in order to process events asynchronously.
	
	- Generate user unique id for all users when they signup.
	- Session was created when the user login to the application.
	- Session will notify the each process and store it temporarly.
	- When the user log out the session, Session details will be vanished. 

## Installation, Configuration and Running 

First ensure your system correctly setting up with required softwares 

These are the some third party packages used in this project

```console 
npm install -dev nodemon
npm install -save express 
npm install -save ejs
```
These are the some third party packages used for Database connectivity 

```console
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
