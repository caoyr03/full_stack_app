# My Full-Stack Web Application
Welcome to my full stack web application! This project is a Q/A platform that connects people with questions about immigration issues in America. This website aims to help cultivating a community for people with immigration status to support each other and share information and knowledge. 

## Ideation
- Users could view all the open questions online about immigration status, with a list view allowing searching function
- Users could view the question stats on the main page, including total questions, total answers, questions solved.
- Users need to log in to ask a question or answer a question 
- Users could access their profiles to view their own questions and answers

To track the progress of this application development, Trello board is used to manage the project. https://trello.com/b/fcrQoBst/qaapp

## Quick Start
`npm start`

## Wireframe Design
I used Balsamiq.com to create a logical prototype to mock the design of my front-end application. You could find it here: 

## Backend Web Services
This app used RESTful web service which consumes requests from a front-end web application and caches each request and the respective response to a database.
### Data Models and UML, Controller Logic
Spring was used to annotate each respective Controller class, which included 
- Container for the model objects to be persisted in database
- Controllers which can receive and respond to requests from the front-end application
- Back-end service used by controllers to handle business logic of web-transactions

## Front-end Implementation
This app used React to implement a client-facing application which crosses regions with the web server. Routing requests are involved to route incoming requests from backend controller to respective front-end controller endpoint.

## Database Integration and Server Cloud Deployment
This project used Heroku to create and configure a live database instance. Heroku was also used to deploy the web server on cloud, so that the it could be exposed for public use. 

## Application Cloud Deployment
The frontend of this application was deployed to a persistent container using Netlify.

