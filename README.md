# Employee Tracker

## Table of Contents
1. [Title](#title)
2. [Project](#project)
3. [Description](#description)
4. [Installation](#installation)
5. [Usage](#usage)
6. [User Story](#user-story)
7. [Acceptance Criteria](#acceptance-criteria)
8. [Video Preview of Project](#video-preview-of-project)
9. [Source](#source)

## Title :
### Employee Tracker

## Project :
### *Employee Tracker*

## Description :
* This project uses NodeJS, Inquirer, MySQL2, and npm dependencies.
* This project is a command-line application that can manage a company's employee database, using Node.js, Inquirer, and MySQL.

## Installation :
- The user needs to install Node and MySQL2 for this project. 

## Usage :
- THe user needs to install the npm dependencies by inputting `npm install` into the directory terminal. 
- Rename the `.envEXAMPLE` file to `.env` and input your MySQL password in the quotes, if you have one.
- Log in to MySQL by inputting `mysql -u root -p` into the terminal.
- In the MySQL shell input `source db/schema.sql` to run the schema file, then `source db/seeds.sql` to populate the database. 
- Run the program with `npm run start`.

## User Story :
```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## Acceptance Criteria :
```md
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 
```

## Video Preview of Project :
[Video Preview](https://drive.google.com/file/d/1NO8JOAi7Gl3GwlCsGhtB_iaUmQlAKMYr/view)


## Source :
- GitHub Link: https://github.com/jeremy-fong/employee-tracker
