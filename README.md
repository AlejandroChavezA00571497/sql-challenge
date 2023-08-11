# sql-challenge
Module 9 Challenge for the Tec de Monterrey Data Analysis Bootcamp, Introduction to SQL

ERD and SQL Scripts that perform data analysis into the information of employees at "Pewlett Hackard" from the 1980s and 1990s. First an ERD is created to show the conceptual relations between the elements in the 6 CSV files provided, then a SQL file is queried in order to create the appropriate tables with the relations defined previously, and finally queries are made through another SQL file in order to find answers to specific questions.

The ERD was made using the following tool: http://www.quickdatabasediagrams.com/
Then, the sql-challenge-queries.sql file is used in order to create the tables and their definitions in SQL, in this case using the pgAdmin4 software. Once the 6 tables are created, they are popualted with data residing in the provided CSV Files.
Finally, the sql-challenge-table-schemas.sql file is used to query the answers to the following questions:

1.- List the employee number, last name, first name, sex, and salary of each employee.
2.- List the first name, last name, and hire date for the employees who were hired in 1986.
3.- List the manager of each department along with their department number, department name, employee number, last name, and first name.
4.- List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5.- List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6.- List each employee in the Sales department, including their employee number, last name, and first name.
7.- List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8.- List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).


The main files for this challenge, sql-challenge-queries.sql, sql-challenge-table-schemas.sql and ERD_Image.png all exist within the EmployeeSQL directory, which is located at the same level as the README and the data directory, which contains the 6 CSVs used to populate the tables with data.

Contributions:
-https://www.geeksforgeeks.org/difference-between-primary-key-and-foreign-key/
-https://learn.microsoft.com/en-us/sql/relational-databases/tables/primary-and-foreign-key-constraints?view=sql-server-ver16
-Data Analysis Bootcamp Classes

