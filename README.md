# E-Commerce
Internet Retail *e-commerce*

## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

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

## Description

A backend e-commerce (internet retail) that provides information on clothing. Makes it easy for the client to understand and eventually obtain. Shows charts to keep organized for inputting. Simple, clean, and polished back-end development. 

## Installation

First git clone this repo: `git@github.com:kmarie0420/E-Commerce.git`
Then run npm i at the root of this project in your local directory.
`npm init`
   * Uses the [MySQL2](https://www.npmjs.com/package/mysql2) 
   * Uses the [Sequelize](https://www.npmjs.com/package/sequelize)
   * Uses the [dotenv](https://www.npmjs.com/package/dotenv)
   * Uses the [Express](https://www.npmjs.com/package/express)


## Usage Information

Run the following command `mysql -u root -p` at the root of your project and input your password. Once your in mysql, use `source db/schema.sql`. Next `exit`, which takes out out of mysql and returns you to the root. Additionally `npm run seed`, & `npm run start`.
App is now listening on Port 3001. 

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](assets/images/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](assets/images/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](assets/images/13-orm-homework-demo-03.gif)

Your walkthrough video should also show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.

## Contributions

Kalynn Powell

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Github Repository

https://github.com/kmarie0420/E-Commerce

## Walk-Through-Video

https://drive.google.com/file/d/1Wy5aLyB3Rdywjft3OtfM783gf545TJTi/view 

## Questions

If you have any questions or concerns, please email `kpowell0420@gmail.com` or https://github.com/kmarie0420 .

## Credits
https://www.npmjs.com/package/mysql2
https://www.npmjs.com/package/sequelize
https://www.npmjs.com/package/dotenv
https://www.npmjs.com/package/express
