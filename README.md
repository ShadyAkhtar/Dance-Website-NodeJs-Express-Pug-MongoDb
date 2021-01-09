# NodeJs - Express - Pug - MongoDb

# Dance Project 
In this Project we define the markup using Pug as a module in node.js, Express for routing the paths.
MongoDb as a Database.
CSS for Stylesheet.

**Note :** This is not a fully-fledged website. Landing page and Contact page is funtional, other pages can also be implemented in similar way. Website is not responsive but can me done using css media query.

## app.js

- app.js is a main page we use for node.js, in this file we define different modules and package we are gonna use in project like express, pug

- app.js is the only file which is responsible to define the endpoint of the different pages in our website for routing.

- We also use app.js file for momgodb CRUD operation.

## package.json file

It consist of all our project details and dependencies used for this project.
to install the dependencies simply type.
**npm install**

## Static Directory 

It consist of all static assets like stylesheet(css) and png images and script if required.

## Views Directory

It consist of different pages created using pug. markup of the page


## module used in this project
- Express **(npm install express)**
- Pug   **(npm install pug)**
- Mongoose **(npm install mongoose)**
- body-parser **(npm install body-parser)**

## Screnshots

- Home Page
![Home Page](screenshots/Home-page1.jpeg?raw=true "Home Page")

- Home Page
![Home page ss2](screenshots/Home-page2.jpeg?raw=true "Home Page")

- Contact Form Submission
![Contact Form Submission](screenshots/contact-page-submit.jpeg?raw=true "Contact Form Submission")

- Confirming Data in Database
![MongoDb Collection](screenshots/mongo-contacts-collection.jpeg?raw=true "Confirming Data in Database")

