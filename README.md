# Pewlett-Hackard-Analysis

## Overview of Pewlett Hackard Analysis

### Purpose
1. Determine the Number of Retiring Employees by Title.
2. Identify Employees Eligible for the Mentorship Program.

### Resources
- SQL
- VSC
- CSV files:
[departments.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634126/departments.csv);
[dept_employees.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634127/dept_employees.csv);
[dept_manager.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634129/dept_manager.csv);
[employees.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634130/employees.csv);
[salaries.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634131/salaries.csv);
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

### Employees Eligible for the Mentorship Program

To help identify those employees eligible for the Mentorship program, we created a Mentorship Eligibility table that shows employees born between Jan 1, 1965 through Dec. 31, 1965.

<img width="537" alt="Screen Shot 2022-09-23 at 8 45 44 AM" src="https://user-images.githubusercontent.com/109354592/191974881-6a7d5970-2546-4bc1-92db-865e5b823ca7.png">

The CSV file show a list of 1,940 employees that are eligible for the Mentorship Program.

[mentorship_eligibility.csv](https://github.com/jbailey2705/Pewlett-Hackard-Analysis/files/9634213/mentorship_eligibility.csv)

### Pewlett Hackard total HC

using the following code we can determine PH's overall HC is, we can then determine how many head it will take to backfill employees retiring from the company.

![Screen Shot 2022-09-23 at 9 05 44 AM](https://user-images.githubusercontent.com/109354592/191979256-4f6ada14-4e13-42e8-97b4-980dc92bb7bd.png)

<img width="602" alt="Screen Shot 2022-09-23 at 9 08 52 AM" src="https://user-images.githubusercontent.com/109354592/191979707-c155b47f-34cb-4296-afa4-226f7e23f3f6.png">

## Summary of Results

- 90,398 employees at Pewlett Hackard are at the retirement age, and will potentially need to be filled. 
- Engineers make up half of the eligible retirees in the file. 5% of the retiring employees are Leader or Managers, while the remaining 44% are staff         members.
- 1,940 current staff members are eligible to become mentors through the Mentorship Program.
- With a total HC of just over 300k employees, PK will need to need to potentially rehire a 3rd of of their HC to compensate for the retiring employees. 
