# testdudeassignment3
#Task 1: Calculate Factorial Using a Function 
def fact(n):
    if n <2:
        return 1
    else:
        return n * fact(n-1)
    
x= int(input("Enter the number: "))
print(f"The factorial of {x} is : ", fact(x))


#Task 2: Using the Math Module for Calculations

import math

n=int(input("Enter a number"))

print("Square root:" ,math.sqrt(n))
print("log:" ,math.log(n))
print("Square root:" ,math.sin(n))
