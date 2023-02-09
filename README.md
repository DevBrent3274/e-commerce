# Object-Relational Mapping (ORM): E-Commerce Back End

## Description

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

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

## [Mysql Command Line Walk Through](https://drive.google.com/file/d/1YA95ktPmUgaBx8KYf3EQJl2GeNmpF8fu/view)

## [Insomnia Test Walk Through](https://drive.google.com/file/d/1F5v9tZ0gWZIKGdOlJVQIPykykm2V4vTb/view)

## Installation

### Use the following in command line to run application:

```
mysql -u root -p
  
DROP DATABASE IF EXISTS ecommerce_db

SOURCE db/schema.sql

Quit

npm run seed

npm start

```
## Credits

Gary Almes and Katy Vincent

## License
![GitHub License Badge](https://shields.io/badge/license-MIT-green)

Copyright (c) [2023] [Brent Johnson]

Do what you like, the world is yours!

## Questions
### Contact:
Github: [https://github.com/DevBrent3274](https://github.com/DevBrent3274)

Email: <brentjohnson3274@gmail.com>
