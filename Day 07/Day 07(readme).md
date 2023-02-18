Write a query identifying the type of each record in the TRIANGLES table using its three side lengths. Output one of the following statements for each record in the table:

Equilateral: It's a triangle with  sides of equal length.
Isosceles: It's a triangle with  sides of equal length.
Scalene: It's a triangle with  sides of differing lengths.
Not A Triangle: The given values of A, B, and C don't form a triangle.

Input Format

The TRIANGLES table is described as follows:

TRIANGLES table schema

A: The length of side A
B: The length of side B
C: The length of side C

Sample Input

TRIANGLES table:
3 4 5
3 4 4
3 3 3
3 4 6

Sample Output

Scalene
Isosceles
Equilateral
Not A Triangle

Explanation

The first triangle is a Scalene triangle because the lengths of all three sides are different.
The second triangle is an Isosceles triangle because the lengths of two sides are equal.
The third triangle is an Equilateral triangle because the lengths of all three sides are equal.

