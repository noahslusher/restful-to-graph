# RESTful to GraphQL

## Description
A fully functioning book search engine that was built using the MERN stack and had its RESTful API converted into GraphQL


## User Story
```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```


## Table of Contents
  * [Features](#features)
  * [Technology Used](#technologyused)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Deployed Application](#deployedapplication)
  * [License](#license)
  * [Questions](#questions)


## Features
* A user can sign up and log in to the application.
* A user can type a search term in a search box and the results appear.
* A user can save a book/books under each search result.
* A user can view their saved books on a separate page.


## Technology Used
* **Git:** Version control system to track changes to source code.

* **GitHub:** Hosts repository that can be deployed to GitHub Pages.

* **Node.js:** Used for package managment and to execute JavaScript code to build the command line tool for server-side scripting.

* **Express.js:** Express. js is a Node. js web application server framework, designed for building single-page, multi-page, and hybrid web applications. Used in this application to set middle ware for end point connection between the front end and backend.

* **Mongoose:** is a MongoDB object modeling tool designed to work in an asynchronous environment. Mongoose supports both promises and callbacks.

* **MongDB:** is a general purpose, document-based, distributed NoSQL database built for web application developers in the cloud era. It’s one of the most popular database choices for modern applications.

* **MongoDB Atlas:** is a cloud-based database service that's created and maintained by MongoDB. It works with hosting services such as AWS, Azure, and Google Cloud to help users provision, maintain, and secure new databases for their applications.

* **GraphQL** is a query language for APIs and a runtime for fulfilling queries with your existing data, giving clients the power to ask for exactly what they need and nothing more. (For this application, graphql package is used to parse GraphQL syntax in both front-end and back-end codebase.)

* **Apollo Server** is an open-source, spec-compliant GraphQL server that's compatible with any GraphQL client, including Apollo Client, the client is used in the MERN application. (For this application, the apollo-server-express package is used to integrate GraphQL into the Express.js server, and the @apollo/client package to make requests from React front end to the GraphQL API.)

* **React Router** is a collection of navigational components that compose declaratively with your application, allowing you to make single-page React applications behave more like multi-page applications. (For this application, the react-router-dom npm package is used to work with React Router.)

* **The concurrently npm package** allows you to run multiple processes, or servers, from a single command-line interface. Rather than opening multiple terminals to start the multiple servers, you can run them both at the same time. It also allows you to keep track of different outputs in one place, and will stop all of your processes if even one of them fails.

* **JSON Web Tokens** or JWTs, are an alternative to using session cookies for authentication.

* **jwt-decode** is an npm package that helps decode JWTs from their Base64Url encoding. (For this application, it is used to extract non-sensitive data such as the token’s expiration date to see if it’s expired before making a request to the server.)

* **The nodemon package** simplifies the development environment by automatically restarting the Node.js applications when file changes in the directory are detected.


## Installation
Download or clone the repository URL
To install packages run the following command:
  ```
  # using npm
  npm i //to install packages
  ```


## Usage
 Once installed, type ```npm run develop``` to run the application.

## Deployed Application

Github: https://noahslusher.github.io/restful-to-graph/

Deployed to Heroku: https://warm-cliffs-35087.herokuapp.com/


## License
![License](https://img.shields.io/badge/license-mit-blue.svg)


## Questions
If you have any questions please feel free to contact me.
** **
**Email:** slushern42@gmail.com
** **
**GitHub Username:** noahslusher