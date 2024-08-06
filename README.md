# E-Commerce-Back-End

## Video link 
[Video showing how to use the application](https://drive.google.com/file/d/1wN7NaRWnCJwqelz4t9zbSMRrmhuu2Zjp/view)

## Images
![Image of the terminal showing localhost is now listening](<./images/treminal-localhost.png>)
![Image of Insomnia](<public/assets/images/Note-Taker.png>)

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Description
This application was created so that retail companies can utilize a SQL database and keep an up to date record of specific categories, products, and tags related to the sale and inventory of their e-commerce business. This application used Sequelize to interact with a SQL database. The use of an ORM (object relational mapping) dependancy rather than strictly using PostgreSQL query's helps make this particular project's code more readable and reusable, and helps further the organization of the code through deconstructing of larger files into more managable pieces.

This project is just the beginning of a complex back end application and can be interacted with through the use of tools such as Insomnia. With Insomnia users can test the functionality of API routes written into the application code which will allow them to view current data, post new data, update data, and delete data from the database.

## Installation
For this application you will need node.js installed. You can go to https://nodejs.org/en to download it. You can clone the repository on your local machine, or copy the files from the repository. Once you have the repository cloned down or copied on you local machine, open the terminal and type 'npm i' to install all of the packages needed for this application. After the packages are installed on your machine, you will need to create/ update the .env file with your PostgreSql username and password. The database will also need to be inputted into the .env file as ecommerce_db. Once this is done, the user will need to go into the databate by right clicking on schema.sql and clicking on 'Open in integrated terminal' and type in 'psql -U postgres' followed by their username and password. Once in the termainal the user will need to type '\i schema.sql' to initiate the database. Then the user can open another integrated terminal from server.js and type in npm start to start the application.

## Usage
The usage of this application, can be seen through the running and testing of the routes with applications such as Insomnia or strictly through using a PostgreSql shell. Once the database has been created, seeded, and the server spun up, users can interact with the database through routing of different api end points.

## License
![MIT License badge](<./images/MIT-badge.png>)

## Contribute
N/A