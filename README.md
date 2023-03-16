# commercewithme
This is the repository for the thirteenth bootcamp challenge (e-commerce backend).

## CommerceWithMe

## Description
This project is the module 13 challenge, an Object-Relational Mapping (ORM) Challenge for an e-commerce back-end. The challenge is to build the back-end for an e-commerce site by taking a working Express.js API and configuring it to use Sequelize to interact with a MySQL database.

## Walkthrough Video
Watch the walkthrough video: https://drive.google.com/file/d/1OB9jrE6fo2BDjZo6o5AopZAZ-j8hxBt4/view?usp=sharing 

## Table of Contents
* Installation
* Usage
* Routes
* Models
* Contributing
* License

## Installation
To install this project, you need to clone the repository from Github, install the dependencies by running npm i, and create an environment file with the following variables:

* python

DB_NAME='ecommerce_db'
DB_USER='your_mysql_username'
DB_PW='your_mysql_password'

## Usage
To use this project, you need to have MySQL installed and running on your machine. After setting up the environment variables, run the schema.sql file in the db folder to create your database using MySQL shell commands. Then run the following command to seed the database:

npm run seed

## Finally, start the server by running:

* sql
Copy code
npm start

## Routes
The API has the following routes:

-- Category Routes
-- Product Routes
-- Tag Routes

## Contributing
If you would like to contribute to this project, please fork the repository and create a pull request. This project was made by Jarrett Jennings and has a One Piece theme.

## License
This project is licensed under the MIT License.
