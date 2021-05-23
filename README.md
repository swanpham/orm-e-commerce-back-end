# E-COMMERCE-BACK-END

## As A Manager

  * I want to to generate a webpage that displays my team's basic info
  * So that I have quick access to my Employees's emails and GitHub profiles
  
## Sample HTML file generated 

![Alt text](/src/images/website.JPG?raw=true "Optional Title")

## Installation

  * Clone the repository to your local machine
  * Navigate to the designated folder in bash
  * Execute npm install to install dependencies
    * [Inquirer](https://www.npmjs.com/package/inquirer) npm package will be installed along with its own dependencies
  * To install dev dependencies, execite npm install --dev
    * [Jest](https://jestjs.io/) npm package will be installed along with its own dependencies
    
## Usage

* GIVEN a functional Express.js API

* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file,
  THEN I am able to connect to a database using Sequelize
  
* WHEN I enter schema and seed commands,
  THEN a development database is created and is seeded with test data
  
* WHEN I enter the command to invoke the application,
  THEN my server is started and the Sequelize models are synced to the MySQL database
  
* WHEN I open API GET routes in Insomnia Core for categories, products, or tags,
  THEN the data for each of these routes is displayed in a formatted JSON
  
* WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
  THEN I am able to successfully create, update, and delete data in my database

## [Walkthrough video](https://drive.google.com/file/d/1q66UZrD1MjCbw15WcaWpLzbmsHb_sRyH/view?usp=sharing)

## Contribution

 * This project is not open for contribution
## Tests

* Ensure npm install --dev has been run after cloning the repo
* Tests are run using the [Jest](https://jestjs.io/) npm package
* run npm test to test all suites, or to test individually:
  * npm test Employee
  * npm test Manager
  * npm test Engineer
  * npm test Inter
  
## Built With

- CSS
- Javascript
