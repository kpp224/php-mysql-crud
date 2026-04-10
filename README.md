# Employee Management CRUD Application
A simple PHP + MySQL employee management system with full CRUD functionality. This project lets users create, read, update, and delete employee records from a MySQL database using a clean Bootstrap interface.

## What this project does
- Displays all employee records in a table
- Adds new employee entries with a form
- Edits existing employee details
- Deletes employee records
- Uses PHP for backend logic and MySQL for data storage
- Uses Bootstrap for responsive layout and simple UI

## Features
- Create employee records
- Read employee list
- Update employee information
- Delete employee records
- Easy-to-use forms and buttons
- Built with PHP and MySQL without frameworks

## Files in this project
- `index.php` - Main page showing the employee list
- `create-new-employee.php` - Form page to add a new employee
- `edit-employee.php` - Form page to edit an existing employee
- `delete-employee.php` - Script to remove an employee

## Technology stack
- Frontend: HTML, CSS, Bootstrap, JavaScript
- Backend: Core PHP
- Database: MySQL

## Setup instructions
1. Copy the project files into your web server folder (for example, `htdocs` or `www`).
2. Create a MySQL database and table for employees.
3. Update the database connection settings in the PHP files as needed.
4. Open `index.php` in your browser to start using the app.

### Example database structure
```sql
CREATE DATABASE employee_management;
USE employee_management;

CREATE TABLE employees (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100) NOT NULL,
  email VARCHAR(100) NOT NULL,
  phone VARCHAR(20) NOT NULL,
  department VARCHAR(100) NOT NULL,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

## How to use
1. Visit `index.php` to view the employee list.
2. Click **Add New Employee** to open the create form.
3. Fill in employee details and submit to save a new record.
4. Click **Edit** on a row to update the details.
5. Click **Delete** on a row to remove the employee.

## Screenshots
The images below show the app interface and workflow:

![Employee list view](https://github.com/mdtalalwasim/php-mysql-crud/assets/91146041/7b9187bc-c32b-4d5b-9b45-c9ab34ed8d2c)

![Add new employee form](https://github.com/mdtalalwasim/php-mysql-crud/assets/91146041/f04bbda7-46aa-441c-9538-5d31c461fd39)

![Edit employee view](https://github.com/mdtalalwasim/php-mysql-crud/assets/91146041/dfdbda99-36be-4d69-951d-d678dac1bf62)

## Notes for the reviewer
- This project is intended as a learning example of PHP + MySQL CRUD operations.
- It uses plain PHP files without a framework for easy understanding.
- The README now explains the purpose, setup, and usage clearly.
