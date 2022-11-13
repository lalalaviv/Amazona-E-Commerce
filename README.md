# Amazona e-commerce 

## Description 
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. 

This application is an e-commerce site built using back-end. 
Using Express.js API and configuring it to use Sequelize to interact with a MySQL database. 

## Table of Contents
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Demonstration](#demonstration)
  - [License](#license)
  - [Questions](#questions)
  - [Credits](#credits)

## Installation
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)


## Usage
 To use the application locally please clone the repo to your local environment, and change the username and password in .env file to your MySQL username and password. 
 <br/>
 To view database from MySQL run the following command: 
 ```bash
 mysql -u root -p
 ````
 To seed the database run the following command:
```bash
npm run seed
```
The application will be invoked by using the following command:
```bash
npm start
```


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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

## Demonstration

The following video demonstrate how to create the schema from MySQL shell, how to seed the database and start the application from the command line:

![Starting the application with command line](https://user-images.githubusercontent.com/106384519/201514738-f67a8b74-030e-4dd6-b578-d4de9bc30490.mp4)


The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](https://user-images.githubusercontent.com/106384519/201514944-a1ae3462-7fa0-4916-ba6c-74dfd847e494.mp4)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](https://user-images.githubusercontent.com/106384519/201515012-0b1d2148-3e8e-4820-8011-74470e595d1f.mp4)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](https://user-images.githubusercontent.com/106384519/201515074-0f46a664-54f1-4dba-8441-806a4e5a9910.mp4)

The following animation shows the application's POST, PUT, and DELETE routes for tags being tested in Insomnia:

![In Insomnia, the user tests “DELETE Tag by ID,” “CREATE Tag,” and “UPDATE Tag.”](https://user-images.githubusercontent.com/106384519/201515254-86aba042-dce3-45b6-ac16-66801c4b2cd8.mp4)

The following animation shows the application's POST, PUT, and DELETE routes for products being tested in Insomnia:

![In Insomnia, the user tests “DELETE Product by ID,” “CREATE Product,” and “UPDATE Product.”](https://user-images.githubusercontent.com/106384519/201515187-ffc11a1b-1b9f-4226-baa5-931265fbc38a.mp4)


## License 
![License](https://img.shields.io/github/license/lalalaviv/Amazona-E-Commerce)


## Questions

  Feel free to reach out if you have any enquiries
  <br/>
  GitHub: [@lalalaviv](https://github.com/lalalaviv)
  Email: lalala.viv@hotmail.com


## Credits

  Vivian Lee