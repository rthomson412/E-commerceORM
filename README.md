## Description
Simple back end application that allows users to view, create, update and delete the products, tags, and categories that populate the inventory of this e-commerce business. Products are linked to categories and tags. Express.js is configured with Sequelize to interact with a MySql database, its models and associations.

## Installation 
After cloning the repository, install the relevant dependencies with 'npm install'.
Then, to connect to the database: 
- run `mysql -u root -p` and enter password from .env file. 
- Source the schema with command 'source db/schema.sql', and then 'quit' the mysql shell. 
Back in the command line, seed the file in the command line with `npm run seed`. 
- Then, connect to the server by executing `npm start`.

This application requires Node.js, Express.js, and Sequelize and a Dotenv file for security.

## Usage
The app allows the user to view, add, edit, and delete categories, products, and tags.

## Walkthrough videos
MYSQL create schema and seed the database.
https://watch.screencastify.com/v/xbZgcJjbOgm2NvDnA2HF

API routes via Insomnia application.
Categories: https://watch.screencastify.com/v/OzObCHn9e71vGe1dx58I
Products: https://watch.screencastify.com/v/zGiUAt3HUYOtrXbygxct
Tags: https://watch.screencastify.com/v/BWEjKxJ6mA0rC8dIFymi

