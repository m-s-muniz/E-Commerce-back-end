# E-Commerce Back-End ORM (Object-Relational Mapping) 
![Github license](https://img.shields.io/badge/license-MIT-mediumblue.svg)
## Description
E-Commerce Back-End ORM (Object-Relational Mapping) is used for an e-commerce website. It provides an interface between the website and a database, allowing the website to store, retrieve, and manipulate data related to products, orders, customers, and other entities.

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)

* [License](#license)

* [Contributing](#contributing)
* [Testing](#testing)
* [Questions](#questions)


## Installation
To install and use this ORM, you need to:
1.	Clone this repository or download its source code as a ZIP file and extract it to a directory on your computer.
2.	Open a terminal or command prompt and navigate to the directory where you extracted the source code.
3.	Run the command npm install to install the required dependencies.




## Usage
1.	Make sure you have Mysql installed and run by typing Mysql -u root -p 
2.	Create a new MySQL database by runnig the schema.sql file by typing SOURCE schema.sql; located in the db directory the type USE ecommerce_db; to use this database.
3. Next type quit to exit Mysql.
4. Now type npm run seed to setup and seed the tables.
5.	Create a .env file in the root directory of the project with the following content: <br>
 -	DB-Name = 'ecommerce_db'
 -	DB_USER = ‘root’
 -	DB_PASSWORD = 'Whatever your password is in here' <br>
6. Now type node server.js to initiate the Application.
7. You can now use Insomnia to test and manipulate the data in the database.
## License
        Licensed under the MIT license.
## Contributing
If you would like to contribute to this repository, please feel free to discuss the change you wish to make via Email, or GitHub with me before making a change.
## Testing
```
NA
```
## Demonstation Video Link






## Questions
* Github - [m-s-muniz](https://github.com/m-s-muniz/)
* Email - someone@somewhere.com