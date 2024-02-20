# ShopEase

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This is an e-commerce backend application. It was developed using JavaScript, Sequelize, MySQL Workbench, Express.js, and Node.js. Insomnia was used to demonstrate the functionality of the localhost server. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Application Sample](#application-sample)
- [Reference](#reference)
- [License](#license)
- [Questions](#questions)

## Installation

To use this application locally, please follow the steps below:

- Clone the repository to your local machine.
- Fill out the .env file with the following information :

```
DB_NAME = 'ecommerce_db'
DB_USER = YOUR USERNAME
DB_PW = YOUR PASSWORD
```
- Afterward, you can use the commands in schema.sql to build your database on WorkBench. 
- Once the database, you can install the required dependencies.
- Then run this command to seed and start the system.
```
npm run seed
```
- Once seeded, please go ahead and run this command to use the application:
```
node server.js
```
Now you should be able to test out the functionality on Insomnia.

## Usage


## Application Sample

Sample image of the application shown :

1. GET all Products.

<img src="assets/images/GET Products.JPG" alt="GET all Products">

2. GET a single Product by its `id`.

<img src="assets/images/GET Products by ID.JPG" alt="GET a single Product by its id">

3. POST a new Product.

<img src="assets/images/POST Create Product.JPG" alt="POST a new Product">

4. PUT to update a Product by its `id`.

<img src="assets/images/PUT Update Product.JPG" alt="PUT to update a Product by its id">

5. DELETE to remove a Product by its `id`.

<img src="assets/images/DELETE Product.JPG" alt="DELETE to remove a Product by its id">

Click on the link to view a video demonstration of the application:

## Reference

Starter code provided by https://github.com/coding-boot-camp/fantastic-umbrella

- https://www.npmjs.com/package/inquirer
- https://www.npmjs.com/package/mysql2
- https://sequelize.org/docs/v6/core-concepts/model-instances/
- https://sequelize.org/docs/v6/core-concepts/model-basics/
- https://sequelize.org/docs/v6/core-concepts/assocs/
- https://sequelize.org/docs/v7/models/validations-and-constraints/#:~:text=Using%20the%20%40NotNull%20decorator%2C%20you,the%20query%20to%20the%20database.
- https://sequelize.org/docs/v6/core-concepts/model-querying-basics/
- https://www.mysql.com/products/workbench/
- https://insomnia.rest/

## License

MIT license was used for this application.

## Questions

For any questions, please contact me at <karina.yukting.li@gmail.com>.
GitHub Profile: https://github.com/karina-yuk
