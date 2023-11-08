# ElectroMarket Express

Project Description: ElectroMarket Express is a functional Express.js API that leverages Sequelize to interact with a MySQL database, providing a robust foundation for building e-commerce platforms in the electronics industry. This project allows businesses and consumers to conveniently engage in online buying and selling of electronic products.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Testing](#testing)


## Installation

- Clone or download the project repository.
- Install the required dependencies using `npm install`.
- Create an environment variable file (`.env`) and configure your MySQL database settings.

## Usage

ElectroMarket Express provides a powerful back-end system for e-commerce websites. It allows businesses and consumers to create, read, update, and delete products, categories, and tags. The application is configured to use Sequelize for managing data and offers API endpoints for interacting with your e-commerce database.

## Database Setup

- Add your database name, MySQL username, and MySQL password to the environment variable file (`.env`).

## Getting Started

- Execute schema and seed commands to create a development database and seed it with test data.
- Start the application with the command `npm start`.
- The Sequelize models are synced to the MySQL database upon application launch.

## API Endpoints

- Use POSTMAN or a similar tool to interact with the API.
- The following API endpoints are available:
  - GET `/api/categories`: Retrieve a list of categories in formatted JSON.
  - GET `/api/products`: Retrieve a list of products in formatted JSON.
  - GET `/api/tags`: Retrieve a list of tags in formatted JSON.
  - POST `/api/categories`: Create a new category.
  - POST `/api/products`: Create a new product.
  - POST `/api/tags`: Create a new tag.
  - PUT `/api/categories/:id`: Update an existing category.
  - PUT `/api/products/:id`: Update an existing product.
  - PUT `/api/tags/:id`: Update an existing tag.
  - DELETE `/api/categories/:id`: Delete a category.
  - DELETE `/api/products/:id`: Delete a product.
  - DELETE `/api/tags/:id`: Delete a tag.

## Testing

- The project has been tested to ensure the following functionalities:
  - Connection to the database using Sequelize.
  - Schema and seed commands to create a development database.
  - Successful server startup and model synchronization.
  - Successful data retrieval and display via API GET routes.
  - Ability to create, update, and delete data using API POST, PUT, and DELETE routes.


