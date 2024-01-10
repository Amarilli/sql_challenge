# sql_challenge

My task is to do a research project about people whom the company Pewlett Hackard employed during the 1980s and 1990s. 

All that remains of the employee database from that period are six CSV files.

I need to:
 - design the tables to hold the data from the CSV files (data modeling),
 -  import the CSV files into a SQL database (data engineering),
 -  answer questions about the data (data analysis).

## Data Modeling

Here, I sketched an Entity Relationship Diagram of the tables:

![erd](https://github.com/Amarilli/sql_challenge/blob/main/EmployeeSQL/QuickDBD-Entity%20Relationship%20Diagram%20of%20the%20tables.png)

## Data Engineering

I used the provided information to create a table schema for each of the six CSV files and I specified:

- the data types,
- primary keys,
- foreign keys,
- other constraints.

Also, I imported each CSV file into its corresponding SQL table.

[Schema](https://github.com/Amarilli/sql_challenge/blob/main/EmployeeSQL/ERD_schema.sql)

## Data Analysis

I selected the data to get:

1. The employee number, last name, first name, sex, and salary of each employee,
   
2. The first name, last name, and hire date for the employees who were hired in 1986,
   
3. The manager of each department along with their department number, department name, employee number, last name, and first name,

   
4. The department number for each employee along with that employee’s employee number, last name, first name, and department name,

5. First name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B,

6. Each employee in the Sales department, including their employee number, last name, and first name,

7. Each employee in the Sales and Development departments, including their employee number, last name, first name, and department name,

8. The frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

[Analysis](https://github.com/Amarilli/sql_challenge/blob/main/EmployeeSQL/analysis.sql)
