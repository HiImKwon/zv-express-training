# Zigvy Express Training Curriculums and Resources
The course is assuming that you are familar with **Javascript**, **Basic NodeJS** and **Object-Oriented Programming Concept**

## Overview
- This is a 1 week training course for building a RESTful API using ExpressJS, NodeJS, MongoDB (with Mongoose) and Babel Configuration

## Resources
- [ExpressJS Documentation](https://expressjs.com/en/starter/installing.html)
- [You don't know JS](https://github.com/getify/You-Dont-Know-JS)

## Content
- **Training 1 - Introduction to Express**
  - What is a ExpressJS?
  - Setup a simple HTTP Server using Express
  - Folder structure overview
  - NodeJS' CommonJS module
  - Config `Babel` for ES6 import/export syntax
  - Config `nodemon` for HMR
  - Config `ESLint` for code linting

- **Training 2 - Express routing**
  - Basic of Express Routing
  - The usage of `request` object
  - The usage of `response` object
  - The usage of `next` object
  - Execution order of express routing

- **Training 3 - Express middleware**
  - `use` function
  - The execution order of middleware
  - Some useful middleware (helmet, cors, morgan, etc)

- **Training 4 - Connect with the Database**
  - A quick introduction to NoSQL with MongoDB
  - Introduction to Mongo Atlas - A cloud DB
  - Install and config mongoose
  - Connecting mongoose with Mongo Atlas
  - Creating a first collection
  - Playing with Mongoose API

- **Training 5 - Very first RESTful API**
  - What is a RESTful API?
  - Four HTTP Methods used in RESTful: `get`, `post`, `del`, `update`
  - HTTP Status
  - Create a simple CRUD RESTful API

- **Training 6 - Advanced RESTful API Design**
  - Nested API
  - How to design a RESTful API more effciently?

- **Training 7 - Authenticate a user request using JWT**
  - What is Json Web Token?
  - Setup JWT library
  - How to create a JWT?
  - How to validate a JWT?
  - How to authenticate a user using JWT?

- **Training 8 - Authentication with Passport Middleware**
  - Setup Passport middleware
  - Login with Facebook
  - Login with Google
  - Login with Email + Password

- **Training 9 - Making a real-time web application using Websocket and SocketIO**
  - What is a real-time web application?
  - What is a Websocket?
  - Setup a Websocket server and client
  - Sending data using Websocket
  - Authenticating a user with Websocket
  - What is a SocketIO?
  - Setup a SocketIO server and client
  - Sending data using SocketIO
  - Authenticating a user with SocketIO

- **Training 10 - Final project**


## Guide
- Fork this repository

- Clone the forked repo

```bash
git clone https://github.com/[username]/zv-express-training
```

- Setup upstream for further resource update

```bash
git remote add upstream https://github.com/longhpzigvy/zv-express-training
```

- Read the README in training section 1, 2, 3, etc and complete the task

- To update with upstream

```bash
git pull upstream master --rebase
```

## Recommendation Readings / Videos
- [Advanced ExpressJS Topics](https://expressjs.com/en/advanced/developing-template-engines.html)
- [What is the difference between Controllers and Services in Node REST API’s?](https://www.coreycleary.me/what-is-the-difference-between-controllers-and-services-in-node-rest-apis/)
- [Why should you separate Controllers from Services in Node REST API’s?](https://www.coreycleary.me/why-should-you-separate-controllers-from-services-in-node-rest-apis/)
- [RESTful API Design - Step by step guide](https://hackernoon.com/restful-api-design-step-by-step-guide-2f2c9f9fcdbf)

## Quan Bui's version of Express Training
  - Use ExpressJS, NodeJS for RESTful API 
  - Use Handlebars as view template