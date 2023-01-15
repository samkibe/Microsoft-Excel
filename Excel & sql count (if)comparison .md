# comparison

=COUNTIFS() for #excel to find a Conditioned "employee salary" and a jobtitle & SELECT COUNT (*) for #sql to do the same.

#excel
=COUNTIFS(range, criteria, range ,criteria) i.e =COUNTIFS(Salary_col, "> 5000", jobtitle_col, "Salesperson")

#sql
SELECT COUNT (*) as Total_no
FROM Employee.Salary, Employee.Jobtitle
WHERE Salary > 5000, Jobtitle = "Salesperson";

