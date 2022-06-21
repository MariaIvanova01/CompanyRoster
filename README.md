# CompanyRoster

Define a class Employee that holds the following information: name, salary, position, department, email, and age. The name, salary, position, and department are mandatory while the rest are optional. 

Your task is to write a program that takes N lines of information about employees from the console and calculates the department with the highest average salary and prints for each employee in that department his name, salary, email, and age - sorted by salary in descending order. If an employee doesn’t have an email – in place of that field you should print "n/a" instead, if he doesn’t have an age – print "-1" instead. The salary should be printed to two decimal places after the separator.

Hint: you can define a Department class that holds a list of employees.

Examples
-------------
Input |	Output
-------|-------
4 |Highest Average Salary: Development 
Peter 120.00 Dev Development peter@abv.bg 28 | Sam 840.20 sam@sam.com -1 
Tina 333.33 Manager Marketing 33 | Peter 120.00 peter@abv.bg 28 
Sam 840.20 ProjectLeader Development sam@sam.com |
George 0.20 Freeloader Nowhere 18	|
6 | Highest Average Salary: Sales
Silver 496.37 Temp Coding silver@yahoo.com | Sam 610.13 n/a -1 
Sam 610.13 Manager Sales |John 609.99 john@abv.bg 44
John 609.99 Manager Sales john@abv.bg 44
Venci 0.02 Director BeerDrinking beer@beer.br 23
Andre 700.00 Director Coding
Popeye 13.3333 Sailor SpinachGroup popeye@pop.ey


