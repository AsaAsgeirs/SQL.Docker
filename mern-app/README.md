# SQL and Docker
Module 5

Tutorial from Ellert Smári:

PERN stack with Docker for beginners - (https://faun.pub/the-pern-stack-with-docker-for-beginners-9fa76e574d82)

SQL Lessons: (https://sqlbolt.com/lesson)

  # Screenshots of the Project:
  ![pgAdmin  localhost pgAdmin, React app](https://user-images.githubusercontent.com/89387153/150159981-2428ad1b-c453-416e-8c98-0f77c299eebe.png)
  
  <img width="1269" alt="Docker Desktop-running" src="https://user-images.githubusercontent.com/89387153/150159973-5037d078-9c04-4352-996c-ab2b265c52d3.png">


**Project description:** 

**DOCKER**

When working in a large team or even a small team with ever changing members it gets very hard to get the project up and running on different devices. I believe you have already felt it in your group work and this becomes an even larger problem when you are dealing with both front-end and back-end.

Docker solves this problem by running a light-weight virtual machine that anyone can pull from the cloud and run the project in the same way on all computers. These machines are normally running Linux with some tools set up for you (like NodeJS or database server.) Therefore it can be handy to use docker to try out new tools without needing to go through the process of installing all the tools necessary.

Since it is important in open source projects and in large corporate projects to be able to start a development environment in a quick and easy way, Docker has become very popular in the industry and it is very likely that you will encounter it in your career path.

To sum it up the for NoSQL:

**SQL**

SQL (or Structured Query Language) is the programming language used to query and work with all the most common relational databases. Most systems have some relational database behind them and almost all older systems (like banks and institutions). The most common open source relational databases today are MySQL, MariaDB, PostgreSQL and SQLite. Some common closed source relational databases are Oracle and Microsoft SQL Server.

**Topics:**

Docker
- Docker containers 
- Docker images
- Linux
- Web servers

SQL
- Tables
- Columns
- Rows
- SELECT FROM
- INSERT INTO
- UPDATE TABLE
- Relational databases


Assignment:

**Knowledge**
- How to use Docker images? (To build a container, pull command in terminal is used to get a Docker image from Docker repository)  (Docker pull <imgaeName>:<tag>:pulls an image from DTR) (Docker push <imgaeName>:<tag>:pushes an image from DTR)
- Know how to get data from a relational database
- Know how to insert data into a relational database
- Know how to update data in a relational database
- Know how to delete data from a relational database

**Skills**
- Be able to create a Docker container out of a Docker image
- Be able to use relational databases as a storage for a web application

----------------------------------
What is Docker / Recap:
- Docker File creates a Docker Image using the build command
- A Docker Image contains all the project’s code
- Using Docker Image, any user can run the code in order to create Docker Containers
- Once a Docker image is built, it’s uploaded in a registry or a Docker Hub
- From the Docker Hub, users can get the Docker Image and build new containers
  
  ![Components of Docker](https://user-images.githubusercontent.com/89387153/150159840-30b0e4eb-8513-4549-8a0e-bb80c4e260c7.png)

  
  
  














---------------------------------------------------------------------------------
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
