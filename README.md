# E-Commerce Back End

## Description

This programme involves the creation of a generic database for an online shop. The user is able to view the tables created for the various aspects of selling a product, as well as add to, alter and delete items from these tables, which, in turn, may delete linked items from other tables. 

## Installation

Running `npm install` within this applications terminal will ensure that the necessary dependencies are downloaded, installed and available to use. This includes "dotenv", "express", "mysql2" and "sequelize".

## Usage

Enter `mysql -u root -p` and then the password for your MYSQL when prompted. Running `SOURCE db/schema.sql;` will create the database then you can enter `\q` to exit the SQL shell. Running `npm run seed` in your terminal will populate the database with tables and columns, as well as enter in the example seeded data. Then `npm start` establishes the connection with the local host and allow the user to engage with the database easily via programmes such as "Insomnia".

## Sources
- https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/
- https://stackoverflow.com/questions/50354817/sequelize-decimal-data-save-with-2-decimal-points
