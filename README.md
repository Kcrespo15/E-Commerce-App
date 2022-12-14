# E-Commerce-App

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

   ## Description
   The purpose of this project was to utilize Sequelize to build the back-end of an Internet retail application to allow database interaction. This application utilizes GET, POST, PUT, and DELETE methods to allow viewing, adding to, modifying, and deleting data from an e-commerce database.

 ## Table of Contents

  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Questions](#questions)

## Installation

  The following packages are required to run this application: express, dotenv, mysql2, and sequelize. Run the following command in the command line to initialize a new package:

  ~~~
  npm init
  ~~~
  
Then, run the following command in the command line to install the express package:
 
  ~~~
  npm install express
  ~~~

Then, run the following command in the command line to install the dotenv package:
 
  ~~~
  npm install dotenv --save
  ~~~

Then, run the following command in the command line to install the mysql2 package:
 
  ~~~
  npm i mysql2
  ~~~

Then, run the following command in the command line to install the sequelize package:
 
  ~~~
  npm install --save sequelize
  ~~~

In addition to these packages, the MySQL shell and Insomnia application are needed on the user's machine to run this application. For MySQL installation instructions, click [here](https://dev.mysql.com/doc/refman/8.0/en/installing.html). For Insomnia installation instructions, click [here](https://docs.insomnia.rest/insomnia/install).

## Usage

  Before starting the application, the user must create database schema and seed the database.

  To connect to the MySQL shell, enter the following command in the command line:

  ~~~
  mysql -u <username-goes-here> -p
  ~~~

  To create database schema, enter the following command in the MySQL shell:

  ~~~
  source db/schema.sql
  ~~~

  Now, open a new terminal. To seed the database, enter the following command in the command line:

  ~~~
  npm run seed
  ~~~

  To run this application, enter the following command in the command line:

  ~~~
  node server
  ~~~
  
Now that the application is up and running, the user can use Insomnia to view data from, add data to, modify data from, or delete data from the database.
https://drive.google.com/file/d/1XV0kNfSJkckgl6P-IhJ2jAwQ6-WZ9TT3/view

 ## License

  This application is covered under the MIT License.
  To view a description of this license type, refer to the repo or click [here](https://opensource.org/licenses/MIT).

  ## Contributing

  Ways to contribute include suggesting bug fixes.
  
  ## Questions

  If you have any questions or would like to provide feedback, do not hesitate to view my GitHub profile at [https://github.com/Kcrespo15](https://github.com/Kcrespo15) or contact me Kevincrespo15@gmail.com.
