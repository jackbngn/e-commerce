# Internet Retail E-commerce Back End

## Description

This project is a back end application for an e-commerce website that uses the latest technologies. The goal of this project is to provide a working Express.js API that interacts with a MySQL database using Sequelize.

## Demo

[Video demo](https://www.youtube.com/watch?v=53hRehj8JkE)

## Installation

To use this application, you will need to have Node.js and MySQL installed on your local machine.

1. Clone this repository to your local machine.
2. Navigate to the root directory of the project in your terminal.
3. Run npm install to install the project dependencies.
4. Create a file named .env in the root directory of the project with the following content:

```
DB_NAME='ecommerce_db'
DB_USER='your-mysql-username'
DB_PW='your-mysql-password'
```

## Usage

1. Navigate to the root directory of the project in your terminal.
2. Create database using mysql SOURCE db/schema.sql
3. Run npm run seed to seed the database with test data.
4. Run npm start to start the server.
5. Use Insomnia or a similar tool to test the API endpoints.

The following API endpoints are available:

- GET /api/categories
- GET /api/products
- GET /api/tags
- POST /api/categories
- POST /api/products
- POST /api/tags
- PUT /api/categories/:id
- PUT /api/products/:id
- PUT /api/tags/:id
- DELETE /api/categories/:id
- DELETE /api/products/:id
- DELETE /api/tags/:id
