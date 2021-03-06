# Mervens Victor: E-Commerce

## Guide
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

# Table Of Contents
- [Description](#description)
- [How It Works](#how-it-works)
- [Example](#example)

## Description  
This assignment was to create the backend for an e-commerce website to use. What this database does is manage GET PUT POST and DELETE requests for products in the API.

## How It Works  

**Install the needed packages using:**

`npm init`

`npm install mysql2`


`npm install sequelize`

`npm install dotenv`


**Now open the SQL:**

`mysql -u root -p` Insert password here if you have one.

`source db/schema.sql`

`quit`

**Back to node:**

`npm run seed`
`npm start`

**Open Insomnia Core and test the routes**
## Example
[ECommerceVid](https://watch.screencastify.com/v/Hsdx6n7PeP7b1tjR6NCN)
![ECommerce2](https://user-images.githubusercontent.com/82620500/136679773-4c5acfd8-c67a-4bc5-8c5b-452ed69be078.png)

## Shareable link to this repo:  

### Link: **https://github.com/Mervens/E-Commerce.**  

## Creator's GitHub Profile:  

### Creator: **https://github.com/Mervens.**

