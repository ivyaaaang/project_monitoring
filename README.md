# Lou Ge Project Monitoring
The Lou Geh Project Monitoring stores each employee’s name (first, last, MI), Social
Security number (SSN), street address, salary, sex (gender), and birth date. An
employee is assigned to one department, but may work on several projects, which are
not necessarily controlled by the same department. Lou Geh Project Monitoring also
keeps track of the current number of hours per week that an employee works on each
project. The direct supervisor for each employee (who is another employee) is kept.
Lou Geh Project Monitoring also keeps track of the dependents of each employee for
insurance purposes. Each dependent’s first name, sex, birth date, and relationship to
the employee is also kept.

---------------------------------------------------------------------------------------

# Installation / Set up

- clone / download this repository
- extract the downloaded folder
- import the project_monitoring.sql to the mysql database
- copy the extracted folder to xampp registry
- launch in browser  (http://localhost/project_monitoring)

---------------------------------------------------------------------------------------

# Notes

-to login as administrator
-input the default account for administrator 
-username/ssn          = admin
-password/project code = admin
 
- an administrator can add new employee, department, projects and such
- can view / check activity logs
 
 
-to login as employee
-username/ssn          = 111223333
-password/project code = 2020001
  
-username/ssn          = 111223333
-password/project code = 2020002
  
-username/ssn          = 222334444
-password/project code = 2020002
  
-an admin can create employee's account by assigning them in a project
-once employees are login, a timestamp will be automatically log in the time_in fields and 
-an employee is required to sign out, so that the timestamp will be inputed in the time_out fields
  
  
  
