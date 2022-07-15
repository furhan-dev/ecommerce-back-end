# Note Taker App

![License Badge](https://img.shields.io/badge/License-MIT-green)

## Description

A simple retail e-commerce back-end written with Node, Express, Sequelize, and MySQL.

The back-end provides the following API endpoints:

`/api/products`

`/api/categories`

`/api/tags`

## Table of Contents

* [Installation](#Installation)
* [Usage](#Usage)
* [Contribution](#Contribution)
* [License](#License)
* [Questions](#Questions)

## Installation

```terminal
touch .env

# open the .env file and add your db credentials
# be sure to include the DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='root'
DB_NAME='ecommerce_db'

# install all dependencies
npm i

# open the mysql shell and source the db schema
SOURCE db/schema.sql

# after exiting the mysql shell, seed the db if you want test data, otherwise start the server
npm run seed # optional
npm start
```

## Usage

Use a front-end or your favorite API client (e.g. Insomnia or Postman) and make CRUD requests to the API endpoints

## Contribution

Fork repo and create a pull request

## License

This project is covered under the MIT License

## Questions

* Email: [contact@furhan.dev](contact@furhan.dev)
* GitHub: [furhan-dev](https://github.com/furhan-dev)
