# JOINS-PRACTICE
COMPANY: CODTECH IT SOLUTION

NAME: PAYAL SANJAY KHADE

INTERN ID: CT08WBX

DOMAIN: SQL

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

This SQL script demonstrates various types of JOIN operations between two tables: EMPLOYEE and DEPARTMENT.

Creating Tables and Inserting Data: • EMPLOYEE Table: The EMPLOYEE table has columns for empId, name, and dept_id. o Five employee records are inserted. • DEPARTMENT Table: The DEPARTMENT table has columns for dept_id and dept_name. o Five department records are inserted.
SELECT Queries: • INNER JOIN: This query selects employees and their respective department names by matching dept_id in both tables. Only employees who have a matching department are included in the result. • LEFT JOIN: This query selects all employees and their respective department names. If an employee does not have a corresponding department (NULL dept_id), the result will still include the employee with a NULL department name. • RIGHT JOIN: This query selects all departments and their respective employees. If a department does not have any employees, the result will still include the department with a NULL employee name. • FULL OUTER JOIN: This query selects all employees and all departments. If an employee does not belong to any department, their dept_name will be NULL, and if a department does not have any employees, the employee information will be NULL. Summary of JOIN Types: • INNER JOIN: Returns only matching rows from both tables. • LEFT JOIN: Returns all rows from the left table (EMPLOYEE) and matching rows from the right table (DEPARTMENT). • RIGHT JOIN: Returns all rows from the right table (DEPARTMENT) and matching rows from the left table (EMPLOYEE). • FULL OUTER JOIN: Returns all rows when there is a match in one of the tables, with NULLs where there is no match.
This script helps demonstrate the different types of joins and how they affect the output when combining data from two related tables.

OUTPUT: 

![1ST](https://github.com/user-attachments/assets/9a853f62-894c-4ad1-8beb-53bdc4a9e825)

![2ND](https://github.com/user-attachments/assets/e9bcf3b0-0af3-49ef-9428-ca19ca97cc7a)

![3RD](https://github.com/user-attachments/assets/cde4e604-f14f-4b51-a787-86f6b0f2aa87)

![4RH](https://github.com/user-attachments/assets/0c481835-152e-4aa3-9983-4a386aefd19b)

![5TH](https://github.com/user-attachments/assets/97de3311-3cf2-4644-bfd8-eac28ba136fb)

![6TH](https://github.com/user-attachments/assets/2d183d58-fe0b-419f-b205-1704b8a57e81)



