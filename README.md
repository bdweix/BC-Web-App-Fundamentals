### Note: archiving this repo. @[Jdmcd]([url](https://github.com/jdmcd)) and I taught a weekly night class (informally) for students looking to learn web apps. We put most of our notes here: https://github.com/bc-web-apps

# BC Web Applications
The purpose of this course is to be able to understand the fundamentals of and create a fullstack web application. Subjects include the types of web requests, roles of the frontend and backend, basics of HTML, storing data, and starting and deploying an application

### Weekly Topics (tentative):
1. HTTP Requests
2. HTML/CSS
3. MVC/Laravel
4. Forms
5. Databases
6. Databases/Auth
7. Deployment
8. Building
9. Building
10. Building
11. Demo

### API Lab:
Using your unique credentials and an API developmenet enviroment (see [Postman](https://www.getpostman.com/)), you will complete weekly assignments interacting with a production API. Activities will also include basic CRUD operations and the eventual integration into your project. This will provide a solud foundation for introducing restful API's and database standards.


## 1. HTTP Requests + GitHub
Objective: Understand the basic types of web requests used to communicate and how they differ. By the conclusion of this section, students will be able to differentiate between different HTTP requests and formulate their own based on given criteria. 

- Headers
- Versions (1.1)
- Body
- Status Codes (404, 401, 200, etc)
- Routing/Paths

HW Objective: Introduce the idea of sending requests and receiving responses over HTTP. Using an API developmenet enviroment ([Postman](https://www.getpostman.com/)), students will communicate with their localhost to a simple GET + POST route in their Express application. Will integrate understanding of request types and demonstrate the fundamentals of a web app. No HTML or views will be rendered at this point.

- How to write GET and POST routes in Express
- Use Postman/Paw/cURL/Rested
- Form Data input, raw output 
- How to view headers 
- How to return different status codes

## 2. HTML + CSS
HTML Objective: Understand the basic structure of HTML documents as a function of displaying data. By the end of this section, students will feel confident building HTML pages in an IDE and rendering them in the browser without using a server.

- Ties together routes, requests, and responses with HTML
- Tags (HTML, BODY, P, A, IMG, DIV, SPAN)
- Classes + IDs
- How to structure a paage

CSS Objective: Understand how CSS can be added to an HTML document in order to control the visual styling of elements.

- Styling Options
- Class/ID Selectors
- Hover States

## 3. Laravel Basics
Objective: Learn and understand how to install and set up a fresh Laravel project. By the end of this section, students will understand how to return HTML pages with GET routes.

- Installing Laravel/Valet
- Connecting to GitHub

## 4. Forms
Objective: Understand how forms work (from an HTML perspective) and understand how they can be used to create HTTP POST requests. By the end of this section, students will understand the different types of inputs and how they relate to HTTP POST requests.
  
- Form Tags
- Action + Method Attributes in Form Tags
- Submitting Forms
- Input Types (Number, Text, Textarea, Select)

Students will then be expected to inspect the data upon form submission and make a decision based on the data. The method will then return a new view with specified data.

- Receive Data
- Modify Data
- Return Response View with Data

## 5. Databases
Objective: Understand databases as a way to persist data throughout an application. This will make it possible for students to build more complicated sequences. Each student will be given credentials to their own private database.

- Students given private database (EC2 instance with login credentials)
- Introduction of Models (no relationships)
- Using the ORM or Raw SQL Queries
- Using database data within views
- Migration Basics

## 6. Model View Controller (MVC)
Objective: Students will apply what they learned with routing and databases to create the concept of Model View Controller. This will provide a nice structure for adding additional forms and interacting with data.

- Understanding CRUDDY design
- RESTFUL API's
- What is a Model? 

## 7. Deployment (sharing with the world!)
Objective: we will show various deployment options and how to configure Heroku for your applications. We'll also get AWS set up and show you how you can use that for projects and applications.

## 8. Final Project
Students will be able to build a personal website. This will feature their picture and basic facts about themselves such as hometown, favorite books, songs, animals, etc. Information will be stored on their database and passed to their view. Students should be able to edit and delete data after they login.

We will dedicate 3 classes to covering additoinal topics or assisting in the creation of your personal websites.


## Other Topics, a plethora of other things that can **now** be taught or explained:
- React + Vue: show the use cases for this and how a virtual dom can benefit users (why reload the entire page?! It all makes sense when you just spent 3 months making painstaking webpages).
- Frontend Javascript/JQuery: adding interactivity without React + Vue
- Bootsrap: why write your own styling? Use professionally developed CSS that automatically adapts to orientation and size changes.
- Test Driven Development: building applications that think about testing from the beginning. 
- Web Hosting: going from local development to production servers and utilizing AWS and other services to host every part of your stack in the cloud
- Queues: offloading intensive tasks to background workers
- Caching: making use of Redis and the browser to increase page loads
- CDNs: distributing content around the world 
- Git Management: how to work with a larger team on Git
- Agile Development Methods
