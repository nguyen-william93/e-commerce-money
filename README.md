# e-commerce-money
This project created back-end routes to handle https request. The project used Express, Node, SQL and Sequelize.
The database has 4 tables: products, tags, product_tag and categories. Products, tags, and categeories can handle get, put, post, and delete http's request. For security, the project ultilzed "dotevn" package to conceal any sensitive informations about the code enviroment. 
Furthmore, all 3 tables are linked together through their ID, and the table product)_tag.
Future improvement: provide a front end application to ultilize the http route.

# User-story
    AS A manager at an internet retail company
    I WANT a back end for my e-commerce website that uses the latest technologies
    SO THAT my company can compete with other e-commerce companies

# Criteria
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

# Info
Name: william nguyen
github: nguyen-william93
MIT license
All Right reserve