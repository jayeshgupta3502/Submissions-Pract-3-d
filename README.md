# Submissions-Pract-3-d
This is my codes

A)Calculating factorial to compute the factor by
Using Recursion


def factorial(n):

    if n == 0:
        return 1

    return n * factorial(n-1)

num = 5;

print("Factorial of", num, "is", factorial(num))

   
B)Calculating factorial to compute the factor by
Using Iteration


def factorial(n):

        res = 1

    for i in range(2, n+1):

        res *= i

    return res
num = 5;

print("Factorial of", num, "is", factorial(num))
