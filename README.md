# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step1:
Define a function.
## Step2:
Assign number_iters = 100 in the function to perform 100 iteratios.
## Step3:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
## Step4:
Return number

## Program:
 # Program to find the gcd of number using functions
 # Developed by:SANJAI S
 # Register Number:23013614
~~~
def sqrt():
    n=int (input())
    a=100
    x=0.5*n
    for i in range(a):
        r=0.5*(x+n/x)
        x=r
    print("Square root of the number:",r)
sqrt()
~~~


## Output:
![Screenshot 2023-12-19 190648](https://github.com/Sanjaichitra/Square-root-of-a-number/assets/144870518/2a526e55-0532-4eb9-9ed8-093085151070)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
