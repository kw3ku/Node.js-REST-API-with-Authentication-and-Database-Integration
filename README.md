# Node.js REST API with Authentication and Database Integration

This repository contains a Node.js application that sets up a REST API with authentication and database integration using Express, Sequelize, and Passport.

## Features

- RESTful API with Express
- User authentication with Passport
- MySQL database integration with Sequelize
- Environment-based configuration
- Error handling and logging

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/kw3ku/Node.js-REST-API-with-Authentication-and-Database-Integration.git
    cd Node.js-REST-API-with-Authentication-and-Database-Integration
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and fill in the required values:
    ```plaintext
    APP=dev
    PORT=3008
    DB_DIALECT=mysql
    DB_HOST=localhost
    DB_PORT=3306
    DB_NAME=nodeAuth
    DB_USER=nodeUser
    DB_PASSWORD=nodeuser
    JWT_ENCRYPTION=jwt_please_change
    JWT_EXPIRATION=10000
    ```

## Usage

1. Start the application:
    ```sh
    npm start
    ```

2. The API will be available at `http://localhost:3008`.

## API Endpoints

- `/v1`: Version 1 of the API routes

## License

This project is licensed under the MIT License.
