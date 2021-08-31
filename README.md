# SQL-Challenge

## UTSA Data Analytics Bootcamp 2021

This repository contains the following scenario:

## Employee Database: A Mystery in Two Parts

In this repository, the major task is a research project on employees of a corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

We will design the tables to hold data in the CSVs, import the CSVs into a SQL database(Postgres), and answer questions about the data. The two major tasks are:

1. Data Engineering/Data Modeling

2. Data Analysis

<h4 style="color:#F09789">Data Modeling</h4>

Inspect the CSVs and sketch out an ERD of the tables. We use the <a href="https://app.quickdatabasediagrams.com/#/" target="_blank" style="color:#6990A4">Quick Database Diagrams</a>.

(SQL-Challenge/EmployeeSQL/ERD) insert ERD image here

<h4 style="color:#F09789">Data Engineering</h4>

* Create a table schema for each of the six CSV files.

    * For the primary keys check to see if the column is unique, otherwise create a composite key. 

    * Create tables in the correct order to handle foreign keys.

* Import each CSV file into the corresponding SQL table. Note to be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors. 

<h4 style="color:#F09789">Data Anaylsis</h4>

1. List the followng details of each employee: employee number, last name, first name, sex and salary.

![Query1](SQL-Challenge/EmployeeSQL/ERD)

2. List first name, last name, and hire date for employees who were hired in 1986.

insery Query2 image

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

insert Query3 image

4. List the department of each employee with the following information: employee number, last name, first name, and department name.
 
 insert Query4 image

 5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

 insert Query5 image

 6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

insert Query6 image

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

insert Query7 image

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

insert Query8 image

## Submission

* <a href="https://github.com/ashleylynnl/SQL-Challenge/blob/main/EmployeeSQL/ERD.png" target="_blank" style="color:#6990A4"> Create an image file of your ERD</a>

* <a href="https://github.com/ashleylynnl/SQL-Challenge/blob/main/EmployeeSQL/schema.sql" target="_blank" style="color:#6990A4"> Create a .sql file of your table schemata. </a>

* <a href="https://github.com/ashleylynnl/SQL-Challenge/blob/main/EmployeeSQL/query.sql" target="_blank" style="color:#6990A4"> Create a .sql file of your queries. </a>
