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
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/91bf858565e5dc834373ac1b3210d871913af4d4/images/create%20employee%20table.png)

## 2nd step is to create department table
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/9cf4c4f158aebef3e0820c5818fc8d76957be324/images/create%20departments%20table.png)

## 3rd step is to create employee department table
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/9cf4c4f158aebef3e0820c5818fc8d76957be324/images/create%20employee%20department%20table.png )

## 4th step is to create employee project table
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/9cf4c4f158aebef3e0820c5818fc8d76957be324/images/create%20employee%20project%20table.png )

## 5th step is to create managers table
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/9cf4c4f158aebef3e0820c5818fc8d76957be324/images/create%20managers%20table.png)


# Table Structures

## employee table structure
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/78a1878a098fb3b8ab92e5ed83c7b047ed36a0c1/images/employee%20table%20structure.png)

## departments table structure
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/78a1878a098fb3b8ab92e5ed83c7b047ed36a0c1/images/departments%20table%20structure.png)

## employee departments table structure
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/78a1878a098fb3b8ab92e5ed83c7b047ed36a0c1/images/employee%20departments%20table%20structure.png)

## employee project table structure
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/78a1878a098fb3b8ab92e5ed83c7b047ed36a0c1/images/employee%20project%20table%20structure.png)

## managers table structure
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/fb13833f646c83dc48f6270845900dad64f50789/images/manager%20table%20struccture.png)

# ERD of Task 1
![image alt](https://github.com/CarlosA012/Finals-Lab-Task-1/blob/71214cef863d651ea93293d81a2e1c1e3e517b12/images/task1%20erd.png)
