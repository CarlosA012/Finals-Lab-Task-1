# Finals-Lab-Task-1

We use MySQL basics that our prof send to us to learn proper code and execute them properly to do our task.

## Task 1: Create the employees table

- Define employee_id as a unique integer, auto-increment, and primary key.
- Define employee_name as a VARCHAR (up to 255 characters), and make it not null.
- Define manager_id as an integer, which will be a foreign key referencing employee_id from the same table.

## Task 2: Create the departments table

- Define department_id as a unique integer, auto-increment, and primary key.
- Define department_name as a VARCHAR (up to 255 characters), and make it not null.

## Task 3: Create the employee_departments table

- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define department_id as an integer, which will be a foreign key referencing department_id in the departments table.
- Set a composite primary key on the combination of employee_id and department_id.

## Task 4: Create the employee_projects table

- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define project_name as a VARCHAR (up to 255 characters), and make it not null.

## Task 5: Create the managers table

- Define manager_id as a unique integer, auto-increment, and primary key.
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.



# Query Statements

## 1st step is to create employee table
<img src="images/create employee table.png" alt="Alt Text" width="400">

## 2nd step is to create department table
<img src="images/create departments table.png" alt="Alt Text" width="400">

## 3rd step is to create employee department table
<img src="images/create employee department table.png" alt="Alt Text" width="450">

## 4th step is to create employee project table
<img src="images/create employee project table.png" alt="Alt Text" width="450">

## 5th step is to create managers table
<img src="images/create managers table.png" alt="Alt Text" width="450">


# Table Structures

## employee table structure
<img src="images/employee table structure.png" alt="Alt Text" width="450">

## departments table structure
<img src="images/departments table structure.png" alt="Alt Text" width="450">

## employee departments table structure

<img src="images/employee departments table structure.png" alt="Alt Text" width="450">

## employee project table structure
<img src="images/employee project table structure.png" alt="Alt Text" width="450">

## managers table structure

<img src="images/manager table struccture.png" alt="Alt Text" width="450">

# ERD of Task 1
<img src="images/task1 erd.png" alt="Alt Text" width="450">
