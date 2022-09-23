# Pewlett-Hackard-Analysis

## Overview of Pewlett Hackard Analysis

### Purpose
1. Determine the Number of Retiring Employees by Title.
2. Identify Employees Eligible for the Mentorship Program.

### Resources
- SQL
- VSC
- CSV files:
[departments.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634126/departments.csv)
[dept_employees.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634127/dept_employees.csv)
[dept_manager.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634129/dept_manager.csv)
[employees.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634130/employees.csv)
[salaries.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634131/salaries.csv)
[titles.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634132/titles.csv)


## End Results

### Retiring Employees by Title

To determine which employees were eligibale to retire, I created a table for retiring employees that shows the employees titles that were born between Jan. 1, 1952 & Dec. 31, 1955 

<img width="680" alt="Screen Shot 2022-09-23 at 8 21 07 AM" src="https://user-images.githubusercontent.com/109354592/191970384-25767011-95d6-4d62-9ce7-422c44d023e5.png">

Using the DISTINCT ON statment I removed the duplicates in the list, returning the most recent title of each employee.

<img width="682" alt="Screen Shot 2022-09-23 at 8 29 08 AM" src="https://user-images.githubusercontent.com/109354592/191971367-b7e5b4b0-eef6-47b4-9555-96ec79a04c21.png">

I then created a Retiring Titles table showing the number of employees retiring by title and age using the COUNT function.

<img width="350" alt="Screen Shot 2022-09-23 at 8 31 52 AM" src="https://user-images.githubusercontent.com/109354592/191971969-91e429ba-fca2-4f88-942b-e54226d78cb1.png">

Results table of the # of employees by Title.

<img width="214" alt="Screen Shot 2022-09-23 at 8 37 19 AM" src="https://user-images.githubusercontent.com/109354592/191972731-885943b8-04c9-444d-8a04-674a1e14a916.png">


