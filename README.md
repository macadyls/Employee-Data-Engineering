# Employee Database Construction

The project involves Data Engineering six csv files of employee information. A database is then created using PostgreSQL where SQL queries have been written for preliminary analysis.

## Data Engineering

Upon inspection of the 6 csv files, I designed an ERD using http://www.quickdatabasediagrams.com returning the image below.

![ERD](https://user-images.githubusercontent.com/85002751/213859336-904493ad-1fa9-48f6-bfca-4b1fb02ef7a5.jpg)

The SQL queries written to create the following tables can be found in schema.sql .
Upon completion, the 6 CSV files were loaded into the tables via PostgreSQL.

## Data Analysis

SQL queries (found in query.sql) were made to conduct the following procedures:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.
2. List first name, last name, and hire date for employees who were hired in 1986.
3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
4. List the department of each employee with the following information: employee number, last name, first name, and department name.
5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
6. List all employees in the Sales department, including their employee number, last name, first name, and department name.
7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
