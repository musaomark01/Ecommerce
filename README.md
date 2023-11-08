# Ecommerce

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Description
I developed this backend e-commerce website to to compete with other e-commerce in the market. Using MySQL, Sequelize, and MySQL2, I established a robust database and utilized Express to facilitate data retrieval, addition, updating, and deletion. Each product is characterized by its unique combination of price, ID, name, tags, and category. Tags, in turn, possess their own distinct IDs, and categories also have unique IDs. Additionally, there's a unique ID for each product-tag.
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Technology Used](#Technology)
- [Questions](#questions)

## Installation
-Node.js (version 18.18.0.) MySQL (version 8.0) -Npm install sequelize (version 5.21.7), dotenv (version 18.2.0), express (version 4.17.1), mysql2 (version 2.1.0).

## Usage
Clone this repository.
Install all the required packages as listed above.
Change the database in MySQL to 'ecommerce_db' using the command: USE ecommerce_db;
Create a .env file and add the following information:
DB_NAME='ecommerce_db'
DB_PASSWORD='your_mysql_password'
DB_USER='your_mysql_user'
Make sure to replace 'your_mysql_password' and 'your_mysql_user' with your MySQL login credentials.
Then run 'npm run seed' after that 'npm start'
In Insomnia use 'http://localhost:3001/api/' 
After the / products, tags, and categories they only work the the Get verb
For products/:id, tags/:id, and categories/:id they get, post, put, and delete by id 

[Walk through video](https://drive.google.com/file/d/1jec2jI2A3ny7nMJMIP2JviBEQ50rSXKo/view)
## License 
This project is licensed under [MIT License](License)

## Contributing
Thank you for your interest in this project! I am not actively seeking external contributions at this time. Feel free to fork the repository and work on your own improvements, but I may not accept pull requests.

## Technology Used
-Node.js (version 18.18.0.)
-MySQL (version 8.0)
### npm packages
-sequelize (version 5.21.7),
-dotenv (version 8.2.0), 
-express (version 4.17.1), 
-mysql2 (version 2.1.0)

## Questions
GitHub: [musaomark01](https://github.com/musaomark01 )
For any additional questions, please feel free to contact me at musaomark01@gmail.com.
