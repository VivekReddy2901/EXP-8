Experiment 8: Study of For Loop in Python

Name: Vivek Reddy

Roll No: 25070123135

Aim

To study and implement for loops in Python and apply them to solve various computational problems using iteration and nested loops.

Introduction

The for loop in Python is used to iterate over a sequence such as a list, tuple, string, or range of numbers. It is particularly useful when the number of iterations is known in advance.

The range() function is commonly used with for loops to generate sequences. It can be used in the following forms:
range(stop)
range(start, stop)
range(start, stop, step)

Nested for loops (loops inside loops) are used to perform complex operations such as matrix traversal, matrix multiplication, and pattern generation.

Programs
1. Print Numbers from 1 to 6

Theory:
This program demonstrates the basic use of a for loop with the range() function to print numbers in sequence.

Algorithm:

Start

Use range(1,7)

Iterate through values

Print each number

End

2. Print Even Numbers from 2 to 10

Theory:
This program uses the step parameter in range() to generate only even numbers.

Algorithm:

Start

Use range(2,11,2)

Iterate through values

Print each number

End

3. Sum of First N Natural Numbers

Theory:
This program calculates the sum of the first N natural numbers using iteration.

Algorithm:

Start

Input value of n

Initialize sum = 0

Use a for loop from 1 to n

Add each number to sum

Display the sum

End

4. Display 3×3 Matrix

Theory:
Nested loops are used to access and display elements of a matrix.

Algorithm:

Start

Define a 3×3 matrix

Use a for loop for rows

Use a nested for loop for columns

Print each element

Move to next line after each row

End

5. Multiplication of Two 3×3 Matrices

Theory:
Matrix multiplication is performed using three nested loops, where elements are multiplied and summed.

Algorithm:

Start

Define matrices A and B

Initialize result matrix with zeros

Use a for loop for rows of A

Use a nested loop for columns of B

Use another loop to multiply and add elements

Store the result in result matrix

Display the result matrix

End

6. Permutations of Three Numbers

Theory:
This program generates all possible permutations of three numbers using nested loops and conditions.

Algorithm:

Start

Store three numbers in a list

Use three nested for loops

Check that all selected elements are different

Print valid combinations

End

7. Inverted Star Pattern

Theory:
This program prints a decreasing pattern of stars using loops.

Algorithm:

Start

Initialize number of rows

Use a for loop from rows down to 1

Print stars equal to the current value

Move to next line after each iteration

End

8. Pyramid Star Pattern

Theory:
This program prints a pyramid pattern using spaces and stars.

Algorithm:

Start

Set number of rows

Use a for loop from 1 to rows

Print spaces equal to (rows - i)

Print stars i times

Move to next line

End

Conclusion

In this experiment, the concept of for loops in Python was studied and implemented. The use of the range() function, step values, and nested loops was clearly understood.

Various problems such as summation, matrix operations, permutations, and pattern printing were solved using for loops. This experiment enhanced logical thinking and provided a strong foundation for advanced programming concepts such as data structures and algorithm design.
