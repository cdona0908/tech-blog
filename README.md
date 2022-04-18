# Tech-blog


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Tech-lbog is a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well

<img width="1440" alt="screenshot" src="public/images/14-mvc-homework-demo-01.gif">


## Installation

1. Clone the repository from GitHub. 
2. Run `npm i`  To install the neccesary dependencies:
   - dotenv: to use environment variables to store sensitive data, like your MySQL username, password, and database name.
   - express, mysql2 and sequelize: to connect to the database.
   - bcrypt: to handle password encryyption
   - connect-session-sequelize and express-session: to create and manage user sessions
   - express-handlebars and handlebars: to render web pages from templates.
3. Run `mysql -u root -p` and enter your mysql password to connect to the database
4. Use the schema.sql file in the db folder to create your database using MySQL shell commands
5. Run `npm run seed` to seed data to the database
6. Run `npm start` to connect to the server 

## Usage  

Once the application is connected to the server, the user will be able to get, create, edit and delete posts, create an account and log into it and add comments to posts.

## Links

Deployed application:

 https://limitless-taiga-60188.herokuapp.com


## Programming Languages

  * JavaScript
  * HTML
  * CSS

## License

  This project is licensed under MIT license. 

## Contributing
  
  If you like to contribute to this application, please refer to the following guidelines:

  Please refer to the Contributor Covenant v2.1 in the following  website: https://www.contributor-covenant.org for guidelines details on how to contribute
