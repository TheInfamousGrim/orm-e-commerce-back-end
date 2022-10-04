# E-commerce Back End Starter Code

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)
![Last Commit to Current Repo](https://img.shields.io/github/last-commit/TheInfamousGrim/orm-e-commerce-back-end)
![Commits a month](https://img.shields.io/github/commit-activity/m/TheInfamousGrim/orm-e-commerce-back-end)

A backend for an e-commerce website.

## Table of Contents 📃

1. [Description](#description)
2. [Screenshot](#screenshot)
3. [Usage](#usage)
4. [Technology](#technology)
5. [Features](#features)
6. [Credits](#credits)
7. [License](#license)
8. [Contribution Guidelines](#contribution-guidelines)
9. [Feedback](#feedback)

## Description

The purpose of this application is to create a back end for an e-commerce site using ExpressJS to create an API and configure it using Sequelize to interact with the MySQL database.

The application is a backend application that can do the following:

- Use a .env file to store the database name, MySQL username and MySQL password
- The application can use these environment variables to connect to the db
- A development database can be created using schema and seed commands
- Open API GET routes in Insomnia core to get the data for categories, products or tags
- POST, PUT and DELETE routes will perform CRUD operations on the db

### User Story 👤

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

### What did I Learn 🏫

The big take away from this project was learning how to use sequelize to create a model and link to a db with a config folder.

Other things I learned:

- Furthered my understanding of NPM scripts
- How to use environment variables
- Become more familiar with REST API's

## Installation

In order to install this backend e-commerce app and test it you need to follow these steps.

1. Ensure that you have node and npm installed

   - [Download Node](https://nodejs.org/en/download/)

   - For detailed instructions on installing node please follow [this link](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) for instructions

2. Ensure that you have mySQL installed

   - [Windows Installation](https://community.chocolatey.org/packages/mysql)

   - [Mac and Linux Installation](https://formulae.brew.sh/formula/mysql#default)

3. Clone this repository into your local repository.

   - `git clone git@github.com:TheInfamousGrim/sql-employee-tracker.git`.

4. Install the dependencies to your package.json

   - `npm install`

5. Login in to mySQL CLI

   - `mysql -u root -p` enter your password when prompted (It should be blank by default)

6. create the database locally using `source schema.sql` (Make sure the path is correct e.g. you're in the db directory)

7. log off by typing and entering `quit`

8. seed the database

   - `npm run seed`

9. Use the .env.EXAMPLE file to construct your own .env file and save that in the root of your develope folder.

If you've followed these steps correctly then the application should be good to go and can be tested using software like [Insomnia Core](https://insomnia.rest/) 😁

## Usage

For a video of how to test the application please follow [this link](https://youtu.be/rWYocO9yQ7s)

Written instructions:

1. run the application with `npm run start`
2. test the application using software like [Insomnia Core](https://insomnia.rest/)

## Technology

The technology used for the development of this app was:

[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](https://www.javascript.com/)

[![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/)

[![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com/)

[![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://dev.mysql.com/)

[![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)](https://sequelize.org/)

dev-dependencies:

- [nodemon](https://www.npmjs.com/package/nodemon)

dependencies:

- [dotenv](https://www.npmjs.com/package/inquirer)
- [express](https://www.npmjs.com/package/express)
- [mysql2](https://www.npmjs.com/package/mysql2)
- [sequelize](https://www.npmjs.com/package/sequelize)

## Features

- Use environment variables to login to a development database
- Seed the database using a npm script
- Perform CRUD operations using API

## Credits

🙏 Made with the help of:

- [University of Birmingham Coding Bootcamp](https://www.birmingham.ac.uk/postgraduate/courses/cpd/coding-boot-camp.aspx)

## License

![License: MIT](https://img.shields.io/github/license/TheInfamousGrim/orm-e-commerce-back-end?color=yellow)

[MIT License](/LICENSE)

## Contribution Guidelines

I'm open to have anyone jump in and contribute just message me on [twitter](https://twitter.com/VaporWhy)

[Guidelines for contributing](/code_of_conduct.md)

## Feedback

![Ask Me Anything](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:finchergeorge1@gmail.com)

<img src="https://avatars.githubusercontent.com/u/89855075?v=4" alt="TheInfamousGrim">

Any feedback please email [George Fincher](mailto:finchergeorge1@gmail.com)

GitHub: [TheInfamousGrim](https://api.github.com/users/TheInfamousGrim)

Twitter: [GrimFunk](https://twitter.com/VaporWhy)
