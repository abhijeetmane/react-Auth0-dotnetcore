# Project Title

This project was bootstrapped with Create React App. App will display list of books.

# Project Description

It is Single page application for the [netcore2-auth0-API](https://github.com/abhijeetmane/netcore2-auth0-API). It integrates Auth0 security services in order to access the book list provided by the API project.

### Tech

Application uses a number of projects to work properly:

* [Auth0]
* [react]
* [nodeJS]

### Running the project
you need to register to [Auth0 services](https://auth0.com/signup) and update Auth0Config.js file accordingly. Make sure  [netcore2-auth0-API](https://github.com/abhijeetmane/netcore2-auth0-API) is running
1. Start project
```
npm install
npm start
```
2. Open  http://localhost:3000 

Application will redirect to the Auth0 authentication page. Once you provide a user's valid credentials, you will get access to the book list provided by the netcore2-Auth0 Web API project.