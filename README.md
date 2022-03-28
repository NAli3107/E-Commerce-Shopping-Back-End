# E-Commerce-Shopping-Back-End

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contact Information](#contact)

## Description

This application is the back end of an E-Commerce site that allows users to control their products, categories and tags. The user can view all the products associated with a category and tag, the categories together with their tags and the tags with all their associated products. Furthermore, users are able to create, update and delete products, categories and tags.

## Installation

- node.js needs to be installed prior to use
- open terminal
- clone the repo: `https://github.com/NAli3107/E-Commerce-Shopping-Back-End`
- cd into new directory
- download JSON packages by entering `npm i`
- create `.env` file 
- to connect to the database run `mysql -u root -p` and enter password from .env file
- source the schema.sql
- seed the data by running `npm run seed`
- enter `npm start`

## Usage

This application will allow users to view, create, update, and delete categories, products, and tags.

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

```

## Examples

Screenshot of Database:

![Database-Screenshot1](./assets/images/DB2.png)

Screenshot of Postman:

![Postman-Screenshot](./assets/images/Postman.png)

[E-Commerce Video 1](https://drive.google.com/file/d/1i530MRSVTAw4hM89hDeXnHi25cYZvoeb/view)

[E-Commerce Video 2](https://drive.google.com/file/d/1XLpnTX3Jdtnm5hKcwILuvHRxLAjKbBTj/view)

[E-Commerce Video 3](https://drive.google.com/file/d/1Ulyc91PmgGJc0CIoRkLVJpDF0nW-GPzt/view)

## Contact

Email Address: Nadiraali188a@gmail.com

Linkedin Profile: [LinkedIn](https://www.linkedin.com/in/nadira-ali-09a182106/)

Github: [Profile](https://github.com/NAli3107)

Github: [Repo](https://github.com/NAli3107/E-Commerce-Shopping-Back-End)
