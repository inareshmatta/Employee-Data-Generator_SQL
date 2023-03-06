Employee Data Generator
This code generates employee data in SQL database. The user can specify how many rows of data they want and can choose any SQL database that is supported.

How to Use
To use this program, follow these steps:

Clone the repository to your local machine.
Enter your database connection details in the config.ini file.
Run main.py and enter the number of rows of employee data you want to generate.
The program will generate the specified number of rows of employee data in your SQL database.
Configuration
In order to connect to your SQL database, you will need to enter your database connection details in the config.ini file. The following parameters are required:

host: the hostname or IP address of the SQL database server
username: the username used to connect to the SQL database
password: the password used to connect to the SQL database
database: the name of the SQL database you want to connect to
You can modify the following parameters to generate more data:

num_employees: the total number of employees you want to generate
min_salary: the minimum salary you want to assign to an employee
max_salary: the maximum salary you want to assign to an employee
min_age: the minimum age you want to assign to an employee
max_age: the maximum age you want to assign to an employee
Supported Databases
This program supports any SQL database that has a Python connector available. Examples of supported databases include:

MySQL
PostgreSQL
Oracle
Microsoft SQL Server
License
This code is licensed under the MIT License. See the LICENSE file for details.
