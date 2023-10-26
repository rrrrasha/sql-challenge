# sql-challenge 
For this challenge, (1) design tables to hold data from the CSV files, (2) import the CSV files into a SQL database, and then (3) write different queries to answer the following questions:

List the employee number, last name, first name, sex, and salary of each employee.
List the first name, last name, and hire date for the employees who were hired in 1986.
List the manager of each department along with their department number, department name, employee number, last name, and first name.
List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
List each employee in the Sales department, including their employee number, last name, and first name.
List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
Create a new database named employees_db then open and run the employee_schema.sql to create the following tables:

department
title
employee
dept_employee
dept_manager
salary
importing ;
start by importing the csv files :

Open and run each query for each question from the analysis_queries.sql file. Outputs of each queries are saved under the employee_analysis folder. Alternatively, you can also lookup the results via Jupyter Notebook file data_analysis.ipynb. Refer to the next section for setting up the config.py file before running data_analysis.ipynb.
