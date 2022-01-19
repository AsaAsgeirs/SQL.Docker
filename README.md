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
