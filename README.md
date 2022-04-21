# Smooth Sales: An e-Commerce Back End Application 
## Purpose
This application is the backend portion of an E-Commerce website. Express.js was used for the server and MySQL for the database along with Sequelize as the ORM to run SQL models and queries. The SQL database includes tables for products, categories, tags, and product tags. RESTful API routes are used to make requests and updates from the database which are joined through Sequelize queries.

## Technologies Used:
* Javascript ES6
* Node.js
* Express.js
* MySQL
* Sequelize (npm pacakge for integrating MySQL and Node.js)

## Installation 
Once MySQL is installed on your local computer, you simply clone this repository into your local computer, and in the root folder e-commerce type into your command line interface, npm install. This will run your node package manager and give your dependencies the files they need. We need to connect our server and create the database that will hold your data. The video below demonstrates this. Running mysql -u root -p will instantiate MySQL. This creates a User of root and you will be prompted to enter the password you created for your MySQL server. Then enter source db/schema.sql, this will create the database ecommerce_db from the schema.sql file. Once this is done, simply type exit.

Also, the password and username for your MySQL should be placed in a file in the root of the project called .env this is a .gitignore file so it will not be publicly displayed. Use the following template: DB_NAME='YourDatabaseNameHere',DB_USER='root',DB_PW='YourPasswordHere'. The dotenv will place those variables in your connection.js file without public display automatically.

## Screencastify Video Walk Through: 
https://drive.google.com/file/d/1NO3IEbLo2Fsh2_GjO_n-1EzQ52PyDwru/view

## Example API requests: 
#### GET request:

![image](https://user-images.githubusercontent.com/75647359/157578500-929cc663-2a47-4b73-9a08-f74502bdd353.png)

#### POST request: 

![image](https://user-images.githubusercontent.com/75647359/157578593-2ecd179b-8c5c-4b4a-82d7-b7c2442fa7cd.png)

