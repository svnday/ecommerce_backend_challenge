# 13 Object-Relational Mapping (ORM): E-commerce Back End

This app is for the Module 13 challenge in my Full Stack Web Developer bootcamp. This application uses the command prompt to create an ecommerce-backend database, with tables for Products with their respective categories and tags as tables.

## User Story

```
AS A manager at an internet retail company  
I WANT a back end for my e-commerce website that uses the latest technologies  
SO THAT my company can compete with other e-commerce companies  
```

## Acceptance Criteria

```
GIVEN a functional Express.js API  
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file  
THEN I am able to connect to a database using Sequelize  
WHEN I enter schema and seed commands  
THEN a development database is created and is seeded with test data  
WHEN I enter the command to invoke the application  
THEN my server is started and the Sequelize models are synced to the MySQL database  
WHEN I open API GET routes in Insomnia for categories, products, or tags  
THEN the data for each of these routes is displayed in a formatted JSON  
WHEN I test API POST, PUT, and DELETE routes in Insomnia  
THEN I am able to successfully create, update, and delete data in my database  

```

## Technology Used
```
This project uses the following technologies:  
Javascript  
Node.js  
Sequelize  
MySQL2  
Express.js  
Dotenv  
```

## Usage Instructions

```
To use this application, first clone the repository. Make sure you have Node and MySQL installed. 
Upon cloning the repo, navigate to the /develop/ directory.
Install necessary dependencies through your command prompt with the command: npm install express sequelize mysql2 dotenv  
Open MySQL, and run the command "source db/schema.sql" and then "use ecommerce_db".  
Quit MySQL and then execute the command "npm run seed"  
Once seed is complete, execute the command "npm start"  

Once server is running, you can use Insomnia or Postman to test the routes.

```

____________________________________________________________________________________________________


Link to repository: [https://github.com/svnday/ecommerce_backend_challenge](https://github.com/svnday/ecommerce_backend_challenge)  
Link to demo video of app: [https://streamable.com/t73g6t](https://streamable.com/t73g6t)
