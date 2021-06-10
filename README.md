# sql-challenge


EmployeeDB
----------

In this assignment, we were asked to use CSV data files to create a Database Schema using  http://www.quickdatabasediagrams.com/.

Using Quick Database Diagrams, PostgreSQL code was imported and run in pgadmin to create our database tables.  The tables were populated by imports into each database
from the original CSV files.  It was important to load data into tables with no constraints, first, followed by tables with the least constraints, and culminating with those with
the most restrictive constraints.  These constraints help to maintain database integrity, and due to the restrictions they place on data that is allowable in the tables, they will
result in import failures constrainsts are not met.

Database - Employee_db
----------------------
Table - departments
      - titles
      - employees
      - salaries
      - dept_manager
      - dept_emp
      

Queries Performed on Database
-----------------------------
      - List the following details of each employee: employee number, last name, first name, sex, and salary.
      - List first name, last name, and hire date for employees who were hired in 1986.
      - List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
      - List the department of each employee with the following information: employee number, last name, first name, and department name.
      - List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
      - List all employees in the Sales department, including their employee number, last name, first name, and department name.
      - List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
      - In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
      
      
 Outputs
 -------
      - PNG of database schema: located in images/EmployeeDB_QDBD_export.png
      - screenshot of database schema: located in images/EmployeeDB_QDBD_scrnshot_.png
      - SQL file containing Employee_db table creation: located in EmployeeDB.sql
      - SQL file containing queries performed on Employee_db database: located in EmployeeDB_queries.sql
      
      
 BONUS
 -----
      The BONUS challenge introduced us to SQLalchemy.  We were tasked to use SQLalchemy to connect to our local Employee_db database, pull some of the tables
      into Pandas, and use Matplotlib to generate a histogram to show salary concentration, and a barchart to visualize average salary by employee title.  I chose to generate
      a horizontal bar chart in order to maintain more salary ticks when running tight layout for writing to file.
      
 BONUS Outputs
 -------------
      - Jupyter notebook containing python/pandas/matplotlib code to read database and generate charts: located in EmployeeSQLtoPandas.ipynb
      - PNG file containing salary histogram: located in images/salary_histogram.png
      - PNG file containing Average Salary By Title horizontal barchart: located in images/avgsalarybytitle_barchart.png
      
      
      
      
