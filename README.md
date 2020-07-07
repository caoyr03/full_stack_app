# My Full-Stack Web Application
Welcome to my full stack web application! 

## Ideation
To track the progress of this application development, Trello board is used to manage the project. 

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
