# E-Commerce Back-End 

![Badge](https://img.shields.io/badge/license-MIT-green?style=plastic&logo=appveyor)

## Table of Content
#### * [Project Desctiption](#description)
#### * [Additional Requirement](#requirements)
#### * [Deployed Application](#application)
#### * [Demo Video](#video)
#### * [Installation/Technical Requirements](#installation)
#### * [Usage](#usage)
#### * [Tests](#tests)
#### * [License](#license)


## Project Description
The scope of project is to build the back end for an e-commerce site by modifying starter code y configuring the working Express.js API and using the Sequelize to interact with a MySQL database . 

### User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

### Acceptance Criteria
GIVEN a functional Express.js API:

- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file, THEN I am able to connect to a database using Sequelize.
- WHEN I enter schema and seed commands, THEN a development database is created and is seeded with test data.
- WHEN I enter the command to invoke the application, THEN my server is started and the Sequelize models are synced to the MySQL database.
- WHEN I open API GET routes in Insomnia for categories, products, or tags, THEN the data for each of these routes is displayed in a formatted JSON.
- WHEN I test API POST, PUT, and DELETE routes in Insomnia, THEN I am able to successfully create, update, and delete data in my database. 
 
 
## Additional Requirements
The application must use the MySQL2 and Sequelize packages to connect your Express.js API to a MySQL database and the dotenv package to use environment variables to store sensitive data.

## Deployed Application
N/A


## Demo Video
[Demo Video]()


## Installation/Technical Requirements
- User needs to install [node.js (version 18.15.0 LTS)](https://nodejs.org/en/).
- To use the application user has to list the following as dependencies in the package.json file:
  - [inquirer (version 8.2.4)](https://www.npmjs.com/package/inquirer/v/8.2.4),
  - [dotenv (version 8.2.0)](),
  - [express (version 4.17.1)](),
  - [MySQL2 (version 3.2.0)](https://www.npmjs.com/package/mysql2),
  - [Sequile (version 5.21.7)]().

## Usage
- To use the application, the user has to:
 - Create the DB by sourcing the schema from the DB file.
 - Populate the DB with the infromation from the Seed.js file.
 - Run npm start to initiate the connection with the local host server
 - Use request commands in Insomnia to verify that request are processes correctly. 


## Tests
At this time no Unit Tests available to test the application functionalities. 


## Contribution
Tutor


## License
Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.
