Problem: Query the Name of any student in STUDENTS who scored higher than 75 Marks. Order your output by the last three characters of each name. If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by ascending ID.

Input Format

The STUDENTS table is described as follows:

STUDENTS table schema
ID NUMBER
NAME VARCHAR2(20)
MARKS NUMBER(3)

Sample Input

STUDENTS table:
1 Maria 20
2 James 30
3 Samantha 21
4 Jessica 33
5 Jennifer 22

Sample Output

Jennifer
Maria
Explanation

The names of the students with Marks > 75 are 'Jessica' and 'Jennifer'. As both have the same last three characters of their names, we order them by ascending ID.