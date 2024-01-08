# E-Commerce Back End

## Description

This programme involves the creation of a generic database for an online shop. The user is able to view the tables created for the various aspects of selling a product, as well as add to, alter and delete items from these tables, which, in turn, may delete linked items from other tables. The localhost listens for extensions to the local server and reacts accordingly. A GET request for the "tag", "products" and "categories" will display all data from their respective lists, while the addition of specific ids following "tag/" will return only the information associated with that id. Additional functionality will be added to delete and update items, however, due to time constraints these were unable to be completed. 

## Installation

Running `npm install` within this application's terminal will ensure that the necessary dependencies are downloaded, installed and available to use. This includes "dotenv", "express", "mysql2" and "sequelize".

## Usage

Ensure you have a `.env` file in which to save the 

```
DB_NAME='ecommerce_db'
DB_USER=''
DB_PASSWORD=''
```

After installing the dependencies, enter `mysql -u root -p` and then your username and password for MYSQL when prompted. Running `SOURCE db/schema.sql;` will create the database then you can enter `\q` to exit the SQL shell. Running `npm run seed` in your terminal will populate the database with tables and columns, as well the example data. Then `npm start` establishes the connection with the local host and allow the user to engage with the database easily via programmes such as "Insomnia".

## Screenshots

Below is a video demonstrating functionality at time of submission
- https://drive.google.com/file/d/1N3lOWHWLfxEj6unAM0LdUITZwilguiRy/view

## Sources
- https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/
- https://stackoverflow.com/questions/50354817/sequelize-decimal-data-save-with-2-decimal-points
