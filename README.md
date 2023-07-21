# E-commerce Back End

This is a Node.js application that utilizes Express.js, Sequelize, and MYSQL to run the back end functionality for an e-commerce website. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Links](#links)

## Installation

1. Clone the repository: git clone https://github.com/josejrod07/ecommerce-backend.git
2. Run 'npm install' in the command-line to install the necessary dependencies.
3. Run the command 'mysql -u root -p' and enter your mysql password.
3. Run 'source db/schema.sql' to create the ecommerce_db database.
4. Run 'npm run seed' to seed the database with the seeds folder.
5. Run 'npm start' to start the server.

## Usage

- Work with the api endpoints specified using Insomnia Core to explore the application's CRUD operations for Categories, Products, and Tags.

## Features

- Database Connection: You can connect to your MySQL database using Sequelize by adding the database name, MySQL username, and MySQL password to the environment variable file. This ensures secure and convenient database access for the application.

- Database Creation and Seeding: By running the provided schema and seed commands, a development database is created and populated with test data. This allows you to work with real data during the development and testing phases.

- Server Initialization: Upon invoking the application, the server starts, and the Sequelize models are automatically synced with the MySQL database. This ensures that your application is ready to handle API requests and interact with the database seamlessly.

- CRUD Operations: The Express.js API provides API endpoints for Categories, Products, and Tags. You can use the API routes in Insomnia Core to perform CRUD operations on these entities.

- Formatted JSON Responses: When you access the API GET routes for categories, products, or tags in Insomnia Core, the data is displayed in a formatted JSON format. This makes it easy to read and understand the responses from the API.

- Create, Update, and Delete Data: Insomnia Core allows you to test API POST, PUT, and DELETE routes, enabling you to successfully create, update, and delete data in the MySQL database. This ensures that your application's data can be managed effectively through the API.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Links

Repository: https://github.com/josejrod07/ecommerce-backend.git

Video Link: https://drive.google.com/file/d/1S-BExVyhwcfG0RAIo1-_QtEQ0_Vrivf8/view