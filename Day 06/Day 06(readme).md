Write a query that prints a list of employee names (i.e.: the name attribute) from the Employee table in alphabetical order.

Input Format

The Employee table containing employee data for a company is described as follows:

Employee table schema
employee_ID NUMBER
NAME VARCHAR2(20)
SALARY NUMBER(18,2)
Months NUMBER(18,2)
The Name column only contains uppercase (A-Z) and lowercase (a-z) letters.

Sample Input

Employee table:
1 Joe 85000
2 Henry 80000
3 Sam 60000
4 Max 90000

Sample Output

Henry
Joe
Max
Sam

Explanation

The names of the employees are listed alphabetically, so we print each name on a new line.

